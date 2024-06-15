<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Psuedo Class Selectors</title>
<style>

header li {
  list-style: none;
}  
a:link, a:visited {
  text-decoration: none;
  background-color: green;
  border: 1px solid blue;
  color: black;
  display: block;
  width: 200px;
  text-align: center;
  margin-bottom: 1px;
}

a:hover, a:active {
  background-color: red;
  color: purple;
}

</style>
</head>
<body>
<h1>Psuedo Class Selector</h1>

<header>
  <ul>
    <li><a href="/">Home</a></li>
    <li><a href="http://goo.gl/V0Wl6s"
    target="_blank">AngularJS Courses</a></li>
    <li><a href="http://www.facebook.com/CourseraWebDev" target="_blank">Facebook Fan page</a></li>
  </ul>
</header>

<section>
  <div>DIV 1</div>
  <div>DIV 2</div>
  <div>DIV 3</div>
  <div>DIV 4</div>
  <div>DIV 5</div>
  <div>DIV 6</div>
  <div>DIV 7</div>
  <div>DIV 8</div>
  <div>DIV 9</div>
  <div>DIV 10</div>
</section>

</body>
</html>
    
