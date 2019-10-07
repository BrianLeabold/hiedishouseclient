<template>
  <footer
    class="full-width center flex text-center justify-around align-middle text-lg text-blue-900"
  >
    <a
      title="Email to brian.leabold@gmail.com"
      href="mailto://brian.leabold@gmail.com"
    >Designed and built by Brian Leabold</a>
  </footer>
</template>
<script>
export default {
  name: 'Footer'
}
</script>
<style scoped>
footer {
  margin-bottom: 15px;
}
footer a:hover {
  color: goldenrod;
  font-weight: 600;
}
</style>