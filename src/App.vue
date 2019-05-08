<template>
<div id="app">
  <router-view/>
</div>
</template>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

h1 {
  font-size: 30px;
}

header {
  position: sticky;
  top: 0px;
  background-color: lightsteelblue;
  padding: 16px;
  margin: 12;
}

header nav ul {
  list-style-type: none;
}

header nav ul li {
  margin: 6px;
}

footer {
  position: fixed;
  bottom: 0%;
  background-color: lightsteelblue;
  padding: 8px;
  width: 100%;
}

section {
  display: flex;
  flex-direction: column;
  padding: 12px;
  margin: 12px;
}

section p,
details {
  margin: 6px;
  padding: 6px;
  line-height: 150%;
}
</style>

