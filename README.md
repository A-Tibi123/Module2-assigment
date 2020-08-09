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
