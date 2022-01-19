<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/about">Our Coffee</router-link>
    <router-link to="/menu">Menu</router-link>
    <router-link to="/status">Order Status</router-link>
    <router-link to="/profile">Profile</router-link>
    <button class="login">Login</button>
  </div>
  <router-view/>
</template>

<script>

export default {
  components: {
    
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Mochiy+Pop+P+One&family=Nanum+Gothic&family=Poppins&family=Raleway&family=Rufina&display=swap');

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#nav {
  font-size: 1.2rem;
  background-color: #333;
  overflow: hidden;
  font-family: 'Nanum Gothic', sans-serif;
  font-weight: lighter;
  width: 100%;
  position: absolute;
}

#nav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 25px;
  text-decoration: none;
  font-size: 17px;
}

#nav a:hover {
  background-color: #4c907b;
}

#nav a:active {
  background-color: #4c907b;
  color: white;
}

button.login {
  float: right;
  padding: 6px 16px;
  border: 1px solid white;
  border-radius: 5px;
  outline: none;
  background: transparent;
  color: white;
  cursor: pointer;
  font-size: 1.2rem;
  margin: 6px 16px 0 0;
}

button.login:hover, button.login:active, button.login:focus {
  background-color: #4c907b;
}
</style>
