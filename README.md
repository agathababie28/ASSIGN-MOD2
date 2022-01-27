
<!DOCTYPE html>
<html lang="en">
<head>
<title>Language Preferences</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
}

/* Style the header */
.header {
  background-color: #f1f1f1;
  padding: 20px;
  text-align: center;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width:992px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>


<div class="row">
  <div class="column">
    <h2>ENGLISH</h2>
    <p>very fluent in speech and writing</p>
  </div>
  
  <div class="column">
    <h2>RUNYAKORE</h2>
    <p> Very fluent in speech than in writing.</p>
  </div>
  
  <div class="column">
    <h2>LUGANDA</h2>
    <p> fairy good in it</p>
  </div>
</div>

</body>
</html>
