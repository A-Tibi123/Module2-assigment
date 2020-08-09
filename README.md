<!DOCTYPE hTML>
<html>
<head>
<link rel="stylesheet" type="text/css href="/Module2/css.css">
<meta charset="utf-8">
<title>Module2-assigment</title>
<style>
  
*{
  box-sizing: border-box;
}
h1 { 
  color: black
  font-size: 23px;
  font-weight: bold;
  font-style: italic;
  text-align: center;
}

p{
  margin-right: auto;
  margin-left: auto;
  color: black;
}

#box{
 border: 1px solid black;
  background-color: blue;
  width: 333px;
  padding: 30px 60px 30px 60px;
  }
  #t1{
  color: black;
  background-color: brown;
  position: top right;
  }

#t2{
  color: purple;
  background-color:yellow ;
  position: top right;
  }
  
  #t3{
  color: white;
  background-color: red;
  position: top right;
  }
  
.row{
  width: 100%;
}

@media (min-width: 950px) and (max-width: 1199) {
  .col-lg-1, .col-lg-2, .col-lg-3 {
  float: left;
  border: 1px;
}
.col-lg-1 {
  width: 33.33%;
}
.col-lg-2 {
  width: 33.33%;
}
.col-lg-3 {
  width: 33.33%;
}
}

@media (min-width: 950px) and (max-width: 1199) {
  .col-md-1, .col-md-2, .col-md-3 {
  float: left;
  border: 1px;
}
.col-md-1 {
  width: 33.33%;
}
.col-md-2 {
  width: 33.33%;
}
.col-md-3 {
  width: 33.33%;
}
}

</style>
</head>
<body>
<h1>Pizza Menu</h1>
  
<div class="row">
  <div class="col-lg-3 col-md-4">
<div id="box">
  <div id=t1>
    <p>Capriciosa</p>
  </div>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
  </p>
</div>
<div class="row">
  <div class="col-lg-3 col-md-4">
<div id="box">
  <div id=t2>
    <p>Vegetarian</p>
  </div>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
  </p>
</div>
<div class="row">
  <div class="col-lg-3 col-md-4">
<div id="box">
  <div id=t3>
    <p>Fromage</p>
  </div>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
  </p>
</div>
</body>
</html>
