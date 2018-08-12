<template>
    <footer class="ae-container-fluid rk-footer ">
      <div class="ae-grid ae-grid--collapse">
        <div class="ae-grid__item item-lg-4 au-xs-ta-center au-lg-ta-left">
          <ul class="rk-menu rk-footer-menu">
            <nuxt-link tag="li" class="rk-menu__item" to="/"><a class="rk-menu__link">Inicio</a></nuxt-link>
            <nuxt-link tag="li" class="rk-menu__item" to="/portfolio"><a class="rk-menu__link">Portfolio</a></nuxt-link>
            <nuxt-link tag="li" class="rk-menu__item" to="/about"><a class="rk-menu__link">About</a></nuxt-link>
          </ul>
          <p class="rk-footer__text rk-footer__copy "> <span class="ae-u-bold">© </span><span class="ae-u-bolder">TEST PORTFOLIO CON NUXT.JS</span> All Right Reserved.</p>
        </div>
        <div class="ae-grid__item item-lg-4 au-xs-ta-center"><a href="https://twitter.com/iukones" class="rk-social-btn ">
            <svg class="svg-icon" viewBox="0 0 20 20"><path fill="none" d="M18.258,3.266c-0.693,0.405-1.46,0.698-2.277,0.857c-0.653-0.686-1.586-1.115-2.618-1.115c-1.98,0-3.586,1.581-3.586,3.53c0,0.276,0.031,0.545,0.092,0.805C6.888,7.195,4.245,5.79,2.476,3.654C2.167,4.176,1.99,4.781,1.99,5.429c0,1.224,0.633,2.305,1.596,2.938C2.999,8.349,2.445,8.19,1.961,7.925C1.96,7.94,1.96,7.954,1.96,7.97c0,1.71,1.237,3.138,2.877,3.462c-0.301,0.08-0.617,0.123-0.945,0.123c-0.23,0-0.456-0.021-0.674-0.062c0.456,1.402,1.781,2.422,3.35,2.451c-1.228,0.947-2.773,1.512-4.454,1.512c-0.291,0-0.575-0.016-0.855-0.049c1.588,1,3.473,1.586,5.498,1.586c6.598,0,10.205-5.379,10.205-10.045c0-0.153-0.003-0.305-0.01-0.456c0.7-0.499,1.308-1.12,1.789-1.827c-0.644,0.28-1.334,0.469-2.06,0.555C17.422,4.782,17.99,4.091,18.258,3.266"></path>				</svg></a>
        </div>
        <div class="ae-grid__item item-lg-4 au-xs-ta-center au-lg-ta-right">
          <p class="rk-footer__text rk-footer__contact "> <span class="ae-u-bold">Email: </span><span class="ae-u-bolder"> <a href="mailto:iukones1@gmail.com" class="rk-dark-color ">iukones1@gmail.com </a></span></p>
          <p class="rk-footer__text rk-footer__by">development by <a href="https://www.iukones.com" class="ae-u-bolder">@iukones.</a></p>
        </div>
      </div>
    </footer>
</template>

<script>
  export default {
    name: 'TheFooter'
  }
</script>

