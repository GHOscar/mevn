<template>
  <div class="container">
      <div class="menu">
        <h2>Menu</h2>
          <div class="menu-items">
            <div class="item"><button class="menu-btn">+</button>Brewed Coffee</div>
            <div class="item"><button class="menu-btn">+</button>Cappuccino</div>
            <div class="item"><button class="menu-btn">+</button>Mochiatto</div>
            <div class="item"><button class="menu-btn">+</button>Matcha Coffee</div>
            <div class="item"><button class="menu-btn">+</button>Brewed Coffee</div>
            <div class="item"><button class="menu-btn">+</button>Brewed Coffee</div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Mochiy+Pop+P+One&family=Nanum+Gothic&family=Poppins&family=Raleway&family=Rufina&display=swap');

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #38846d;
  height: 100vh;
}

.menu {
  font-family: 'Rufina', serif;
  margin-top: 5rem;
  height: 100%;
  width: 60%;
  background-color: #f3e4e1;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.menu h2 {
  font-size: 2rem;
  font-weight: lighter;
}

.menu-items {
  display: flex;
  flex-direction: column;
  font-size: 1.5rem;
  margin-top: 20px;
}

.item {
  display: flex;
  width: 400px;
  align-items: flex-end;
}

.item::after {
  border-bottom: 1px dotted black;
  content: '';
  flex: 1;
}

@media screen and (max-width: 900px) {
  .item {
    width: 100%;
  }
}

.menu-items button.menu-btn {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  font-size: 1.5rem;
  outline: none;
  border: none;
  margin: 10px;
  background-color: black;
  color: white;
  cursor: pointer;
  margin-right: 15px;
}

.menu-items button.menu-btn:hover {
  background-color: #38846d;
}
</style>