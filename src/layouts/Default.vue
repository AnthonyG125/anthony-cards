<template>
  <div class="layout">
    <slot/>
  </div>
</template>



<style>
body {
  font-size: 15px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background: #222;
  color: #fff;
  font-family: Nunito,Helvetica,Arial,sans-serif;
  padding: 0;
  margin: 0;
  width: 100%;
  height: 100%;
}

.layout {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

</style>
