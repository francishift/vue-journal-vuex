<template>
  <div
    class="entry-container pointer p-2"
    @click="$router.push({ name: 'entry', params: { id: 10 } })"
  >
    <!-- Título -->
    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold">15</span>
      <span class="mx-1 fs-5">Julio</span>
      <span class="mx-2 fw-light">2021, jueves</span>
    </div>
    <div class="entry-description">
      Dolore reprehenderit ea aliquip ut deserunt. Nulla cillum in consequat
      anim officia est anim pariatur culpa tempor incididunt consequat. Velit
      pariatur cillum qui cupidatat eiusmod consequat labore commodo sunt qui
      eiusmod eu. Sint ex non id voluptate velit aute magna dolor aliquip
      consequat dolore. Sunt ad cupidatat voluptate ipsum reprehenderit culpa
      consequat non excepteur aliqua. Consectetur amet nostrud pariatur
      consectetur exercitation. Enim et mollit cillum est.
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss" scoped>
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;

  &:hover {
    background-color: lighten($color: grey, $amount: 45);
    transition: 0.2s all ease-in;
  }
  .entry-description {
    font-size: 13px;
  }
}
</style>
