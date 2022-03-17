<template>
  <header :class="{ 'scrolled-nav':scrollPosition }">
      <nav>
          <div class="branding">
              <img src="@/assets/Logo.png" alt="" >
          </div>
          <ul v-show="!mobile" class="navigation">
              <li><router-link class="link" :to="{name: 'Home'}">Home</router-link></li>
              <li><router-link class="link" :to="{name: ''}">About</router-link></li>
              <li><router-link class="link" :to="{name: ''}">Portfolio</router-link></li>
              <li><router-link class="link" :to="{name: ''}">Contact</router-link></li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style>

</style>