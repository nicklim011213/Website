<template>
  <div class="item">
    <div class="Project">
        <h3> A simple 3D Graphics Engine (With Camera Controls)</h3>
        <a href="https://github.com/nicklim011213/GraphicsEngine"> <img src="../assets/WIP.png"></a>
    </div>
    <div class="Project">
        <h3> A simple 3D Projection of a 2D Map using SFML</h3>
        <a href="https://github.com/nicklim011213/2DMapProjection"> <img src="../assets/LimGEDemo2.gif"></a>
    </div>
    <div class="Project">
        <h3> Learning how to build websites with Vue (This page!)</h3>
        <a href="https://github.com/nicklim011213/Website"> <img src="../assets/WIP.png"></a>
    </div>
    <div class="Project">
        <h3> Floorspaces an webapp for drawing and modeling floorplans</h3>
        <a href="https://github.com/Floorspaces/FloorSpaces-Public"> <img src="../assets/Floorspaces.gif"></a>
    </div>
  </div>
</template>

<style scoped>
.item {
  display: grid;
  position: relative;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr, 1fr;
  border: 0;
  height: 100%;
  width: 100%;
  background-color: #40405D;
  border-top: white;
  border-style: solid;
  gap: 15px;
}
li {
  outline: solid;
  margin: 1vh;
  padding: 0.5vh;
  border: 0;
  border-color: rgb(0, 0, 0);
  outline-color: rgb(0, 0, 0);
}
h3 {
  color: #ffffff;
  margin: 0;
  padding: 0;
  border: 0;
}
a {
  display: inline-block;
  text-decoration: none !important;
}
ul
{
  list-style-type: none;
  margin: 0;
  padding: 0;
  border: 0;
}
img
{
  display: block;
  margin: 0;
  border: 0;
  outline-width: 0;
  object-fit: contain;
  height: 400px;
}
</style>
