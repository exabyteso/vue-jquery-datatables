# datatable-integration-tutorial

jQuery datatables is a very useful library for displaying data in a tabular form.
However, Vue, and jQuery are fundamentally different in paradigm i.e. Vue is data first, so
changes in the DOM are done by changing the data wheras jQuery manipulates the DOM directly
regardless of the data.

Hence the motivation of this project which contains a brief example of how to integrate jQuery Datatables with Vue while keeping the Vue data first paradigm, and preventing conflict between
the changes that Vue makes in line with changes to data, and those made by the jQuery datatable.

## Before we begin, kindly note the following:
1. Note that this example has been tailored for Ubuntu users
2. jQuery, and jQuery datatables have not been installed with npm but instead their scripts have been added to the index.html page for speed, and simplicity
3. It's good practice to separate jQuery datatables into its own component to prevent the table from being overwritten by changes to Vue data

## Prerequisites
1. A functional internet connection
2. Ubuntu version 16.04 and above
3. npm
4. Global Vue CLI

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

## Key steps
Assuming you've created a basic vue project with using `vue create your-project-name-here`
1. Remove the unnecessary hello world component, and modify the index html titles as you please
2. Add the following scripts at the bottom of the body of the index.html page

```
    <script
    src="https://code.jquery.com/jquery-3.4.1.min.js"
    integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
    crossorigin="anonymous"></script>
    <script src="https://cdn.datatables.net/1.10.20/js/jquery.dataTables.min.js"></script>
    <script src="https://cdn.datatables.net/1.10.20/js/dataTables.bootstrap.min.js"></script>
```
3. Create a datatable component with one `<table></table>` element as shown in the example below
```
<template>
    <table id="sample-datatable" style="cursor:pointer;" class="table table-hover"></table> 
</template>
```
4. Create the component boiler plate
```
export default {
    name: 'my-component-name',
    data(){
        return {
            columns: [],
            rowData: []
        }
    },
    mounted(){
        // We'll initialize the datatable here
    }
}
```
5. Declare the columns, and data you'd like. For more information on how to do this using jQuery datatables, visit the [package documentation](https://datatables.net/examples/data_sources/js_array.html)
6. Initialize the datatable, add the data, and draw it on the DOM
```
// Initialize the datatable and store it in dtHandle for easy access
// throughout the component
this.dtHandle = $(this.$el).DataTable({
    columns: this.columns
});

// Add the row data
this.dtHandle.rows.add(this.rowData)

// Draw the table... Without this step, it won't be visible
this.dtHandle.draw()
```




