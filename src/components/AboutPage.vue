<template>
  <div class="about">
    <div class="container">
      <div class="text">
        <h2>Our coffee</h2>
        <p>
          <strong
            >Pumpkin spice mug, barista cup, sit macchiato, kopi-luwak, doppio,
            grounds dripper, crema, strong whipped, variety extra iced id lungo
            half and half mazagran. Pumpkin spice.</strong
          >
        </p>
        <p>
          Que dark fair trade, spoon decaffeinated, barista wings whipped, as
          rich aftertaste, con panna milk black, arabica white rich beans single
          shot extra affogato. So affogato macchiato sit extraction instant
          grinder seasonal organic, turkish Lorem ipsum dolor sit amet,
          consectetur adipisicing elit. Dolor, et. Obcaecati at ut, totam quo
          earum nemo enim voluptatibus provident inventore modi. Est eius vitae
          veritatis neque ea exercitationem sapiente perspiciatis inventore,
          illum eveniet! Magni consequuntur aspernatur repudiandae id fuga!
        </p>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio
          exercitationem ipsum esse dolorum! Explicabo mollitia ea dolores quasi
          natus, beatae eaque voluptatibus praesentium commodi eum reprehenderit
          aut perspiciatis distinctio. Ipsa, sequi odio? Asperiores quae
          voluptatem recusandae modi! Repellendus, natus quos quas debitis
          doloremque tenetur blanditiis? Debitis natus dolorum nam in quod ab
          voluptatibus quam nesciunt sint non laborum sequi, nihil fuga veniam
          nulla ipsa omnis officia. Sunt, minus esse. Beatae nobis aspernatur
          impedit consequuntur voluptas? Esse maiores vero nulla repellat?
        </p>
      </div>
        <div class="creator-profile">
            <img src="https://cdn4.iconfinder.com/data/icons/movie-characters/50/fsociety-mask-512.png" alt="profile picture">
            <h3>Oscar Jansson</h3>
            <p>Owner & Founder</p>
        </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Mochiy+Pop+P+One&family=Nanum+Gothic&family=Poppins&family=Raleway&family=Rufina&display=swap');

.about {
  height: 100vh;
  background-color: #38846d;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: column;
}

.container {
  width: 60%;
  background-color: #f3e4e1;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

h2 {
  font-size: 2rem;
}

.text p {
  margin-top: 30px;
  
}

.text {
  margin-top: 50px;
  width: 70%;
  font-family: 'Rufina', serif;
}

.creator-profile {
    margin-top: 50px;
    text-align: center;
    margin-bottom: 10px;
}

.creator-profile img {
    width: 50px;
    height: 50px;
}

.creator-profile h3 {
    font-size: 2rem;
}
</style>