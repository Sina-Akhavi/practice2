<template>
  <ul>
    <li><a href="#" class="one">Home</a></li>
    <li><a href="#" class="one">Docs</a></li>
    <li class="logout"><a href="#" class="active">Logout</a></li>
    

  </ul>
</template>

<script></script>

<style>
body {
  margin: 0;
}

ul {
  background-color: black;
  overflow: hidden;
  margin: 0;
}

li {
  float: left;
  display: block;
  padding: 14px 16px;
}

a.one:hover {
  background-color: rgb(51, 53, 55);
}

a {
  padding: 14px 16px;
  color: white;
  text-decoration: none;
  text-align: center;

}

li.logout {
  float: right;
}


li.logout:hover {
  background-color: greenyellow;
}

a.active {
  background-color: green
}




</style>