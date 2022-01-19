<template>
<div class="header">
    <div class="text-circle">
  <h1>air bean</h1>
  <h3>drone-delivered coffee</h3>
  </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.header {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: #38846d;
}

.text-circle {
    text-align: center;
    border: 1px solid white;
    padding: 60px;
    border-radius: 60rem;
    background-color: #4c907b;
}

h1, h3 {
    text-transform: uppercase;
    color: white;
    margin: 0;
}

h1 {
    font-size: 3rem;
    font-weight: lighter;
    font-family: 'Rufina', serif;
}

h3 {
    font-size: .8rem;
    letter-spacing: 5px;
    font-family: 'Nanum Gothic', sans-serif;
    font-weight: lighter;
}
</style>