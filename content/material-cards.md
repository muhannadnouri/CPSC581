+++
title = "Material Portfolio"
slug = "material"
thumbnail = "images/tn.png"
description = "material"
+++

## [Source Code](https://codepen.io/gabrielglauber/pen/Xdrvxm)

<style>
body {
  color: #404040;
  line-height: 22px;
  letter-spacing: .4px;
}

.card-container {
  width: 100px;
}

.card {
  display: inline-block;
  box-shadow: 0 1px 2px 0 rgba(0,0,0,.15);
  margin: 20px;
  position: relative;
  margin-bottom: 50px;
  transition: all .2s ease-in-out;
  width: 300px;
  flex-shrink: 3;
}

.card:hover {
  /*box-shadow: 0 5px 22px 0 rgba(0,0,0,.25);*/
  box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
  margin-bottom: 54px;
}

.image {
  height: 200px;
  opacity: .7;
  overflow: hidden;
  transition: all .2s ease-in-out;
}

.image:hover,
.card:hover .image {
  height: 200px;
  opacity: 1;
}

.text {
  background: #FFF;
  padding: 20px;
  min-height: 200px;
}

.text p {
  margin-bottom: 0px;
}

.container {
  position: relative;
  width: 100%;
  max-width: 960px;
  margin: 0 auto;
  padding: 0 20px;
  box-sizing: border-box; }
.column,
.columns {
  width: 100%;
  float: left;
  box-sizing: border-box; }

/* For devices larger than 400px */
@media (min-width: 400px) {
  .container {
    width: 85%;
    padding: 0; }
}

/* For devices larger than 550px */
@media (min-width: 550px) {
  .container {
    width: 80%; }
  .column,
  .columns {
    margin-left: 4%; }
  .column:first-child,
  .columns:first-child {
    margin-left: 0; }

  .one.column,
  .one.columns                    { width: 4.66666666667%; }
  .two.columns                    { width: 13.3333333333%; }
  .three.columns                  { width: 22%;            }
  .four.columns                   { width: 30.6666666667%; }
  .five.columns                   { width: 39.3333333333%; }
  .six.columns                    { width: 48%;            }
  .seven.columns                  { width: 56.6666666667%; }
  .eight.columns                  { width: 65.3333333333%; }
  .nine.columns                   { width: 74.0%;          }
  .ten.columns                    { width: 82.6666666667%; }
  .eleven.columns                 { width: 91.3333333333%; }
  .twelve.columns                 { width: 100%; margin-left: 0; }

  .one-third.column               { width: 30.6666666667%; }
  .two-thirds.column              { width: 65.3333333333%; }

  .one-half.column                { width: 48%; }

  /* Offsets */
  .offset-by-one.column,
  .offset-by-one.columns          { margin-left: 8.66666666667%; }
  .offset-by-two.column,
  .offset-by-two.columns          { margin-left: 17.3333333333%; }
  .offset-by-three.column,
  .offset-by-three.columns        { margin-left: 26%;            }
  .offset-by-four.column,
  .offset-by-four.columns         { margin-left: 34.6666666667%; }
  .offset-by-five.column,
  .offset-by-five.columns         { margin-left: 43.3333333333%; }
  .offset-by-six.column,
  .offset-by-six.columns          { margin-left: 52%;            }
  .offset-by-seven.column,
  .offset-by-seven.columns        { margin-left: 60.6666666667%; }
  .offset-by-eight.column,
  .offset-by-eight.columns        { margin-left: 69.3333333333%; }
  .offset-by-nine.column,
  .offset-by-nine.columns         { margin-left: 78.0%;          }
  .offset-by-ten.column,
  .offset-by-ten.columns          { margin-left: 86.6666666667%; }
  .offset-by-eleven.column,
  .offset-by-eleven.columns       { margin-left: 95.3333333333%; }

  .offset-by-one-third.column,
  .offset-by-one-third.columns    { margin-left: 34.6666666667%; }
  .offset-by-two-thirds.column,
  .offset-by-two-thirds.columns   { margin-left: 69.3333333333%; }

  .offset-by-one-half.column,
  .offset-by-one-half.columns     { margin-left: 52%; }

}
</style>

<html lang="en">

<head>
  <title>Pure CSS Material Design cards</title>
</head>

<body>

  <div class="container">
    <div class="row">
      <div class="col-md-6 col-sm-8 col-xs-12 col-md-offset-3 col-sm-offset-2">
        <div class="card">
          <div class="image">
            <img src="http://assets.materialup.com/uploads/fc97b003-ba72-4c6e-9dd3-19bf5002c244/preview.jpg" width="100%">
          </div>
          <div class="text">
            <h3>Project 1</h3>
            <p>Description</p>
          </div>
        </div>
                      <div class="card">
          <div class="image">
            <img src="http://assets.materialup.com/uploads/fc97b003-ba72-4c6e-9dd3-19bf5002c244/preview.jpg" width="100%">
          </div>
          <div class="text">
            <h3>Project 2</h3>
            <p>Description</p>
          </div>
        </div>
                <div class="card">
          <div class="image">
            <img src="http://assets.materialup.com/uploads/fc97b003-ba72-4c6e-9dd3-19bf5002c244/preview.jpg" width="100%">
          </div>
          <div class="text">
            <h3>Project 3</h3>
            <p>Description</p>
          </div>
        </div>
                        <div class="card">
          <div class="image">
            <img src="http://assets.materialup.com/uploads/fc97b003-ba72-4c6e-9dd3-19bf5002c244/preview.jpg" width="100%">
          </div>
          <div class="text">
            <h3>Project 4</h3>
            <p>Description</p>
          </div>
        </div>
      </div>
      </div>
      </div>
    </div>
  </div>
</body>
</html>