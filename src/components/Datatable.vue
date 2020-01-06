<template>
    <table id="sample-datatable" style="cursor:pointer;" class="table table-hover"></table> 
</template>

<script>
export default {
  name: 'Datatable',
  data(){
    return {
      columns: [
        {title: "First Name", data: "fname"},
        {title: "Last Name", data: "lname"},
        {title: "Date of Birth", data: "dob"},
        {title: "Height (cm)", data: "height"}
      ],
      rowData: [
        {
          "fname": "Carter",
          "lname": "Gentry",
          "dob": "2009-05-11",
          "height": 172
        },
        {
          "fname": "Virginia",
          "lname": "Carroll",
          "dob": "2007-04-03",
          "height": 170
        },
        {
          "fname": "Mira",
          "lname": "Contreras",
          "dob": "2009-06-15",
          "height": 167
        },
        {
          "fname": "Yasir",
          "lname": "Barron",
          "dob": "2008-09-21",
          "height": 165
        },
        {
          "fname": "Yuli",
          "lname": "Carney",
          "dob": "2007-08-21",
          "height": 165
        },
        {
          "fname": "Willa",
          "lname": "Zimmerman",
          "dob": "2008-05-14",
          "height": 168
        },
        {
          "fname": "Alexandra",
          "lname": "Cote",
          "dob": "2009-06-28",
          "height": 190
        },
        {
          "fname": "Arthur",
          "lname": "Tucker",
          "dob": "2009-08-09",
          "height": 184
        },
        {
          "fname": "Nash",
          "lname": "Grant",
          "dob": "2008-10-29",
          "height": 180
        },
        {
          "fname": "Darryl",
          "lname": "York",
          "dob": "2009-03-13",
          "height": 188
        },
        {
          "fname": "Lucy",
          "lname": "Rowe",
          "dob": "2009-08-28",
          "height": 161
        },
        {
          "fname": "Brenden",
          "lname": "Diaz",
          "dob": "2009-06-10",
          "height": 184
        },
        {
          "fname": "Phoebe",
          "lname": "Willis",
          "dob": "2007-10-21",
          "height": 171
        },
        {
          "fname": "Leah",
          "lname": "Sellers",
          "dob": "2008-12-03",
          "height": 162
        },
        {
          "fname": "Henry",
          "lname": "Tucker",
          "dob": "2007-04-25",
          "height": 162
        },
        {
          "fname": "Nelle",
          "lname": "Jimenez",
          "dob": "2008-03-15",
          "height": 165
        },
        {
          "fname": "Hilel",
          "lname": "Wooten",
          "dob": "2009-06-06",
          "height": 184
        },
        {
          "fname": "Lucius",
          "lname": "Sloan",
          "dob": "2007-04-16",
          "height": 184
        },
        {
          "fname": "Shea",
          "lname": "Mcmahon",
          "dob": "2007-07-02",
          "height": 160
        },
        {
          "fname": "Neil",
          "lname": "Bird",
          "dob": "2008-11-06",
          "height": 170
        },
        {
          "fname": "Alice",
          "lname": "Bass",
          "dob": "2009-10-01",
          "height": 168
        },
        {
          "fname": "Benjamin",
          "lname": "Dorsey",
          "dob": "2009-08-18",
          "height": 165
        },
        {
          "fname": "Odessa",
          "lname": "Sanchez",
          "dob": "2009-06-21",
          "height": 162
        },
        {
          "fname": "Thor",
          "lname": "Mccoy",
          "dob": "2008-10-10",
          "height": 174
        },
        {
          "fname": "Cassandra",
          "lname": "Whitley",
          "dob": "2007-12-20",
          "height": 168
        },
        {
          "fname": "Britanni",
          "lname": "Mack",
          "dob": "2008-03-18",
          "height": 163
        },
        {
          "fname": "Tamekah",
          "lname": "Haynes",
          "dob": "2007-05-01",
          "height": 183
        },
        {
          "fname": "Boris",
          "lname": "Branch",
          "dob": "2009-03-16",
          "height": 162
        },
        {
          "fname": "Petra",
          "lname": "Cooke",
          "dob": "2007-01-20",
          "height": 175
        },
        {
          "fname": "Brianna",
          "lname": "Fitzpatrick",
          "dob": "2009-02-03",
          "height": 173
        },
        {
          "fname": "Aurelia",
          "lname": "Cash",
          "dob": "2009-03-04",
          "height": 174
        },
        {
          "fname": "Kareem",
          "lname": "Pope",
          "dob": "2007-08-01",
          "height": 161
        },
        {
          "fname": "Caryn",
          "lname": "Copeland",
          "dob": "2007-05-17",
          "height": 167
        },
        {
          "fname": "Ferdinand",
          "lname": "Riggs",
          "dob": "2008-10-03",
          "height": 182
        },
        {
          "fname": "Avye",
          "lname": "Craig",
          "dob": "2007-08-29",
          "height": 169
        },
        {
          "fname": "Jaquelyn",
          "lname": "Hodges",
          "dob": "2009-02-10",
          "height": 174
        },
        {
          "fname": "Declan",
          "lname": "Clayton",
          "dob": "2008-08-30",
          "height": 169
        },
        {
          "fname": "Kirby",
          "lname": "Case",
          "dob": "2009-09-27",
          "height": 170
        },
        {
          "fname": "Hayley",
          "lname": "Briggs",
          "dob": "2007-07-11",
          "height": 182
        },
        {
          "fname": "Mara",
          "lname": "Wheeler",
          "dob": "2008-11-30",
          "height": 168
        },
        {
          "fname": "Linus",
          "lname": "Harmon",
          "dob": "2009-10-05",
          "height": 184
        },
        {
          "fname": "Quin",
          "lname": "Kirby",
          "dob": "2008-03-06",
          "height": 184
        },
        {
          "fname": "Isabella",
          "lname": "Boyle",
          "dob": "2008-01-13",
          "height": 182
        },
        {
          "fname": "Tanner",
          "lname": "Johnson",
          "dob": "2009-07-16",
          "height": 173
        },
        {
          "fname": "Emmanuel",
          "lname": "Atkinson",
          "dob": "2007-09-18",
          "height": 172
        },
        {
          "fname": "Cade",
          "lname": "Thornton",
          "dob": "2008-03-11",
          "height": 184
        },
        {
          "fname": "Sharon",
          "lname": "Bartlett",
          "dob": "2008-07-22",
          "height": 166
        },
        {
          "fname": "Reece",
          "lname": "Mullen",
          "dob": "2009-06-24",
          "height": 179
        },
        {
          "fname": "Faith",
          "lname": "Stevenson",
          "dob": "2008-11-28",
          "height": 165
        },
        {
          "fname": "Chadwick",
          "lname": "Dunn",
          "dob": "2007-10-28",
          "height": 184
        },
        {
          "fname": "Laura",
          "lname": "Bowman",
          "dob": "2008-10-09",
          "height": 187
        },
        {
          "fname": "Kay",
          "lname": "Berry",
          "dob": "2009-02-11",
          "height": 169
        },
        {
          "fname": "Mason",
          "lname": "Stokes",
          "dob": "2008-12-24",
          "height": 165
        },
        {
          "fname": "Uta",
          "lname": "Cohen",
          "dob": "2009-04-05",
          "height": 160
        },
        {
          "fname": "Sonya",
          "lname": "Austin",
          "dob": "2008-07-16",
          "height": 170
        },
        {
          "fname": "Elijah",
          "lname": "Fischer",
          "dob": "2009-04-30",
          "height": 168
        },
        {
          "fname": "Evan",
          "lname": "Kemp",
          "dob": "2008-08-22",
          "height": 172
        },
        {
          "fname": "Wyatt",
          "lname": "Whitfield",
          "dob": "2007-05-29",
          "height": 181
        },
        {
          "fname": "Wayne",
          "lname": "Montgomery",
          "dob": "2009-11-17",
          "height": 168
        },
        {
          "fname": "Timothy",
          "lname": "Joyner",
          "dob": "2009-10-19",
          "height": 161
        },
        {
          "fname": "Juliet",
          "lname": "Rocha",
          "dob": "2007-11-28",
          "height": 185
        },
        {
          "fname": "Brooke",
          "lname": "Murphy",
          "dob": "2009-07-11",
          "height": 190
        },
        {
          "fname": "Vance",
          "lname": "Fields",
          "dob": "2008-05-15",
          "height": 165
        },
        {
          "fname": "Jacob",
          "lname": "Johns",
          "dob": "2007-08-01",
          "height": 172
        },
        {
          "fname": "Keith",
          "lname": "Burris",
          "dob": "2007-06-08",
          "height": 181
        },
        {
          "fname": "Miranda",
          "lname": "Duffy",
          "dob": "2007-03-20",
          "height": 178
        },
        {
          "fname": "Rashad",
          "lname": "Buck",
          "dob": "2008-02-02",
          "height": 183
        },
        {
          "fname": "Dominic",
          "lname": "Woodward",
          "dob": "2008-02-09",
          "height": 187
        },
        {
          "fname": "Nasim",
          "lname": "Shelton",
          "dob": "2008-09-14",
          "height": 184
        },
        {
          "fname": "MacKensie",
          "lname": "Church",
          "dob": "2008-06-23",
          "height": 180
        },
        {
          "fname": "Wang",
          "lname": "Torres",
          "dob": "2008-12-08",
          "height": 171
        },
        {
          "fname": "Anne",
          "lname": "Mcdonald",
          "dob": "2008-04-29",
          "height": 176
        },
        {
          "fname": "Kelly",
          "lname": "Lawson",
          "dob": "2008-10-24",
          "height": 177
        },
        {
          "fname": "Bradley",
          "lname": "Vinson",
          "dob": "2009-11-27",
          "height": 186
        },
        {
          "fname": "Michelle",
          "lname": "Norman",
          "dob": "2008-10-06",
          "height": 163
        },
        {
          "fname": "Edward",
          "lname": "Eaton",
          "dob": "2008-06-23",
          "height": 173
        },
        {
          "fname": "Lacy",
          "lname": "Huff",
          "dob": "2009-08-22",
          "height": 161
        },
        {
          "fname": "Xyla",
          "lname": "Snow",
          "dob": "2007-05-11",
          "height": 163
        },
        {
          "fname": "Hoyt",
          "lname": "Benton",
          "dob": "2007-01-21",
          "height": 169
        },
        {
          "fname": "Imani",
          "lname": "Rocha",
          "dob": "2007-03-25",
          "height": 162
        },
        {
          "fname": "Ashton",
          "lname": "Palmer",
          "dob": "2009-02-07",
          "height": 189
        },
        {
          "fname": "Thor",
          "lname": "Page",
          "dob": "2007-01-14",
          "height": 181
        },
        {
          "fname": "Echo",
          "lname": "Carpenter",
          "dob": "2007-03-29",
          "height": 179
        },
        {
          "fname": "George",
          "lname": "Parker",
          "dob": "2007-03-24",
          "height": 176
        },
        {
          "fname": "Kasper",
          "lname": "Kemp",
          "dob": "2009-11-20",
          "height": 170
        },
        {
          "fname": "Lydia",
          "lname": "Poole",
          "dob": "2007-03-03",
          "height": 187
        },
        {
          "fname": "Uma",
          "lname": "Hansen",
          "dob": "2009-08-12",
          "height": 171
        },
        {
          "fname": "Oren",
          "lname": "Scott",
          "dob": "2007-12-16",
          "height": 166
        },
        {
          "fname": "Camilla",
          "lname": "Jimenez",
          "dob": "2008-05-06",
          "height": 173
        },
        {
          "fname": "Rachel",
          "lname": "Harding",
          "dob": "2008-12-24",
          "height": 169
        },
        {
          "fname": "Quyn",
          "lname": "Valencia",
          "dob": "2009-06-09",
          "height": 170
        },
        {
          "fname": "Stacey",
          "lname": "Fitzpatrick",
          "dob": "2007-08-14",
          "height": 162
        },
        {
          "fname": "Quinn",
          "lname": "Richard",
          "dob": "2009-11-07",
          "height": 185
        },
        {
          "fname": "Rowan",
          "lname": "Glover",
          "dob": "2007-01-27",
          "height": 184
        },
        {
          "fname": "Sage",
          "lname": "Maddox",
          "dob": "2007-01-23",
          "height": 168
        },
        {
          "fname": "Hayfa",
          "lname": "Snyder",
          "dob": "2008-07-11",
          "height": 175
        },
        {
          "fname": "Melissa",
          "lname": "Herrera",
          "dob": "2009-10-02",
          "height": 177
        },
        {
          "fname": "Octavius",
          "lname": "Moody",
          "dob": "2009-10-15",
          "height": 182
        },
        {
          "fname": "Aurora",
          "lname": "Jennings",
          "dob": "2009-03-15",
          "height": 186
        },
        {
          "fname": "Lucius",
          "lname": "Mitchell",
          "dob": "2008-05-01",
          "height": 173
        }
      ]
    }
  },
  mounted(){
    this.dtHandle = $(this.$el).DataTable({
      columns: this.columns
    });

    this.dtHandle.rows.add(this.rowData)

    this.dtHandle.draw()
  }
}
</script>
