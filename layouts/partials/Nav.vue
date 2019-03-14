<template>
  <header>
    <nuxt-link to="/" class="logo">Nuxty</nuxt-link>
    <nav>
      <ul>
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/about">about</nuxt-link></li>
        <li><nuxt-link to="/services">services</nuxt-link></li>
        <li><nuxt-link to="/contact">contact</nuxt-link></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style>
  header {
    display: grid;
    background: rgb(0, 219, 146);
    grid-template-columns: repeat(2, auto);
  }

  .logo, li a {
    padding: 1em 1em;
    display: block;
    text-transform: uppercase;
    text-decoration: none;
    font-weight: bold;
    color: white;
    font-size: .9em;
  }

  nav {
    justify-self: right;
  }
  ul {
    list-style-type: none;
  }
  li {
    display: inline;
  }
  li a{
    padding: 1em 2em;
    display: inline-block;
    background: rgba(0, 0, 0, 0.1);
  }
</style>
