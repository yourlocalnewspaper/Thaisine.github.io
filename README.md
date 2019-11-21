<!DOCTYPE html>
<html>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Arial, Helvetica, sans-serif;}

.navbar {
  width: 100%;
  background-color: #555;
  overflow: auto;
}

.navbar a {
  float: left;
  padding: 12px;
  color: white;
  text-decoration: none;
  font-size: 17px;
  width: 25%; /* Four links of equal widths */
  text-align: center;
}

.navbar a:hover {
  background-color: #000;
}

.navbar a.active {
  background-color: #4CAF50;
}

@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block;
    width: 100%;
    text-align: left;
  }
}

</style>
<body>

<h1 align="center">Thaisine</h1>
<h1 align="center">Home</h1>

<div class="navbar">
  <a class="active" href="file:///C:/Users/pchs/Documents/page1.htm">Home</a> 
  <a href="file:///C:/Users/pchs/Documents/page2.htm">Dishes</a> 
  <a href="file:///C:/Users/pchs/Documents/page3.htm">Drinks</a> 
  <a href="file:///C:/Users/pchs/Documents/page4.htm">Desserts</a>
</div>


<div>
    <p style="float: left;"><img src="thailand_cuisine1.jpg" width="600px" border="1px"></p>
    <p><font size="8">Thai cuisine usually focuses on lightly prepared dishes with strong aromatic components and spicy edge. It tries to bring important detail as well as using ingredients with medicinal benefits and good flavors. Instead of being simple, the cuisine tries to be complex with their combination of elements.
</font></p>
</div>


</body>
</html> 
