<template>
  <div class="top">
    <div class="top__bar container">
      <a href="mailto:info@kukalogistics.com" id="home" class="">
        <span class="top__bar-mail">info@kukalogistics.com</span></a
      >

      <a href="tel:+90(505)662 40 48" class="top__bar-tel"
        ><span> +90 (505) 662 40 48 </span></a
      >
    </div>
  </div>
  <nav class="nav">
    <div class="nav_container container">
      <div class="nav__item_logo">
        <a href="#!" class="nav__item_logo-logo"
          ><img src="@/assets/img/logo.svg" alt="" />
        </a>
        <h1 class="nav__item_logo-title">KUKA LOGISTICS</h1>
      </div>
      <div class="nav__item">
        <ul class="nav__item-title" :class="{ active: isActive == true }">
          <li>
            <a class="nav__item-icon" @click="isActive = false" href="#home">
              <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                <!--! Font Awesome Pro 6.4.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path 
                  d="M543.8 287.6c17 0 32-14 32-32.1c1-9-3-17-11-24L512 185V64c0-17.7-14.3-32-32-32H448c-17.7 0-32 14.3-32 32v36.7L309.5 7c-6-5-14-7-21-7s-15 1-22 8L10 231.5c-7 7-10 15-10 24c0 18 14 32.1 32 32.1h32v69.7c-.1 .9-.1 1.8-.1 2.8V472c0 22.1 17.9 40 40 40h16c1.2 0 2.4-.1 3.6-.2c1.5 .1 3 .2 4.5 .2H160h24c22.1 0 40-17.9 40-40V448 384c0-17.7 14.3-32 32-32h64c17.7 0 32 14.3 32 32v64 24c0 22.1 17.9 40 40 40h24 32.5c1.4 0 2.8 0 4.2-.1c1.1 .1 2.2 .1 3.3 .1h16c22.1 0 40-17.9 40-40V455.8c.3-2.6 .5-5.3 .5-8.1l-.7-160.2h32z"
                />
              </svg>
            </a>
          </li>
          <li class="nav__item-link"><a @click="isActive = false" href="#service">Услуги</a></li>
          <li class="nav__item-link"><a @click="isActive = false" href="#about">О нас</a></li>
          <li class="nav__item-link"><a @click="isActive = false" href="#why">Почему мы</a></li>
          <li class="nav__item-link"><a @click="isActive = false" href="#contact">Контакты</a></li>
        </ul>
        <button class="nav__menu" :class="{ active: isActive == true }" @click="isActive = !isActive">
          <span class="nav__menu_line"></span>
          <span class="nav__menu_line"></span>
          <span class="nav__menu_line"></span>
        </button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      isActive: false,
    };
  },
};
</script>

<style></style>
