<template>
  <footer class="footer bg-primary-color">
      <div class="container">
          <div class="row">
              <div class="col-4">
                  <h3>Social</h3>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero suscipit repellat, quas maiores, voluptate officiis molestias labore repellendus eos optio dolores doloremque nisi deleniti, asperiores error consequatur. Quia, temporibus nobis.</p>
              </div>
            <div class="col-4">
                <h3>Certificazioni</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero suscipit repellat, quas maiores, voluptate officiis molestias labore repellendus eos optio dolores doloremque nisi deleniti, asperiores error consequatur. Quia, temporibus nobis.</p>
            </div>
            <div class="col-4">
                <h3>Skills</h3>
                <div id="carouselExampleControls" class="carousel slide text-center" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="../../assets/images/vue.png" class="footer__logo" alt="Vue Logo">
                        </div>
                        <div class="carousel-item">
                            <img src="../../assets/images/laravel.png" class="footer__logo" alt="Laravel Logo">
                        </div>
                            <div class="carousel-item">
                            <img src="../../assets/images/php.png" class="footer__logo" alt="Php Logo">
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>
          </div>
      </div>
  </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
.footer {
    padding: 50px 0;
    // .footer__logo
    &__logo {
        max-height: 100px;
        max-width: 100%;
    }
}
</style>