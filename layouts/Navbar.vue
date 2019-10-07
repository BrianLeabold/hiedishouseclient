<template>
  <nav>
    <ul class="main-menu bold">
      <li>
        <nuxt-link to="/">About</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/mission">Mission</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/updates">Updates</nuxt-link>
      </li>
    </ul>
  </nav>
</template>
<script>
export default {
  name: 'Navbar'
}
</script>
<style scoped>
nav {
  width: 100%;
  padding-top: 15px;
  height: 50px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: navy;
}
.main-menu {
  list-style: none;
  margin: auto;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}
li {
  margin: 0 10px;
  padding: 5px 10px;
  height: 50px;
  text-align: center;
  font-size: 1.2rem;
}
li a {
  text-decoration: none;
  height: 50px;
  padding: 5px;
  color: black;
  font-size: 1.2rem;
}
li a:hover {
  color: #35495e;
}
.nuxt-link-exact-active {
  background: gold;
}
</style>