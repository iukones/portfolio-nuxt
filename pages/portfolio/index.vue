<template>
    <section class="ae-container-fluid ae-container-fluid--inner rk-portfolio">
    <div class="ae-masonry ae-masonry-md-2 ae-masonry-xl-4">
      <a class="rk-item ae-masonry__item">
        <img src="~/assets/img/project-1.jpg" alt="">
        <div class="item-meta">
          <h2>Essential Stationery</h2>
          <p>Branding</p>
        </div>
      </a>
      <a class="rk-item ae-masonry__item">
        <img src="~/assets/img/project-2.jpg" alt="">
        <div class="item-meta">
          <h2>Pickled Tousled</h2>
          <p>Art Direction</p>
        </div>
      </a>
      <a class="rk-item ae-masonry__item">
        <img src="~/assets/img/project-3.jpg" alt="">
        <div class="item-meta">
          <h2>Waistcoat vegan</h2>
          <p>Graphic Design</p>
        </div>
      </a>
      <a class="rk-item ae-masonry__item">
        <img src="~/assets/img/project-4.jpg" alt="">
        <div class="item-meta">
          <h2>Tumblr hammock</h2>
          <p>Packaging</p>
        </div>
      </a>
      <a class="rk-item ae-masonry__item">
        <img src="~/assets/img/project-5.jpg" alt="">
        <div class="item-meta">
          <h2>Biodiesel etsy</h2>
          <p>Branding</p>
        </div>
      </a>
      <a class="rk-item ae-masonry__item">
        <img src="~/assets/img/project-6.jpg" alt="">
        <div class="item-meta">
          <h2>Gentrify artisan</h2>
          <p>Graphic Design</p>
        </div>
      </a>
      <a class="rk-item ae-masonry__item">
        <img src="~/assets/img/project-7.jpg" alt="">
        <div class="item-meta">
          <h2>Plaid austin</h2>
          <p>Graphic Design</p>
        </div>
      </a>
      <a class="rk-item ae-masonry__item">
        <img src="~/assets/img/project-8.jpg" alt="">
        <div class="item-meta">
          <h2>Trust fund</h2>
          <p>Packaging</p>
        </div>
      </a>
    </div>
  </section>
</template>

<script>
export default {
    transition: 'fadeOpacity'
}
</script>

<style scoped>
.fadeOpacity-enter-active, .fadeOpacity-leave-active {
  transition: opacity .45s ease-out;
}

.fadeOpacity-enter, .fadeOpacity-leave-active {
  opacity: 0;
}

</style>
