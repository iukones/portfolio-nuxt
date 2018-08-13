<template>
    <header class="ae-container-fluid ae-container-fluid--full rk-header ">
      <input type="checkbox" id="mobile-menu" class="rk-mobile-menu">
      <label for="mobile-menu">
        <svg role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="currentColor" d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z" class=""></path></svg>
      </label>
      <div class="ae-container-fluid rk-topbar">
        <h1 class="rk-logo">portfolio nuxt.js<sup>tm</sup></h1>
        <nav class="rk-navigation">
          <ul class="rk-menu">
            <nuxt-link tag="li" class="rk-menu__item" to="/"><a class="rk-menu__link">Inicio</a></nuxt-link>
            <li class="rk-menu__item"><a class="rk-menu__link">Páginas</a>
              <nav class="rk-menu__sub">
                <ul class="rk-container">
                  <nuxt-link tag="li" class="rk-menu__item" to="/portfolio"><a class="rk-menu__link">Portfolio</a></nuxt-link>
                  <nuxt-link tag="li" class="rk-menu__item" to="/about"><a class="rk-menu__link">About</a></nuxt-link>
                </ul>
              </nav>
            </li>
          </ul>
        </nav>
      </div>
    </header>
</template>

<script>
  export default {
    name: 'TheHeader'
  }
</script>

