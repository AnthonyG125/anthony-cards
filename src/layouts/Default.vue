<template>
  <div class="main">
    <slot/>
  </div>
</template>



<style>
body, html {
  font-size: 15px;
  -webkit-font-smoothing: antialiased;
  background: #222;
  color: #fff;
  font-family: Nunito,Helvetica,Arial,sans-serif;
  padding: 0;
  margin: 0;
  width: 100%;
  height: 100%;
}
.main {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>
