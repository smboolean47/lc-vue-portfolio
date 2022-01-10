<template>
  <section class="about" id="chi-siamo">
      <div class="container">
          <div class="row align-items-center">
              <div class="col-5">
                  <img class="about__image" src="../../assets/images/avatar.png" alt="Samuele">
              </div>
              <div class="col-7">
                  <h3>Ciao, mi chiamo Samuele Madrigali 😊</h3>
                  <p>Sono un:</p>
                  <ul>
                      <li>Full Stack Developer 💻</li>
                      <li>Coding Coach 👨🏼‍🏫</li>
                      <li>Pescatore amatoriale 🐟</li>
                   </ul>
                   <p>
                       Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit quibusdam pariatur, odit magni omnis natus adipisci rem exercitationem iste! Neque minima architecto dolore necessitatibus reiciendis totam, natus aut autem voluptatibus!
                   </p>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style lang="scss" scoped>
.about {

    &__image {
        border-radius: 50%;
        max-width: 100%;
    }
}

</style>