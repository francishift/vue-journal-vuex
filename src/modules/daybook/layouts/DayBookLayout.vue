<template>
  <Navbar />
  <div class="mt-2">
    <div class="d-flex">
      <div class="col-4"><Entrylist /></div>
      <div class="col">
        <router-view />
      </div>
    </div>
  </div>
</template>

<script>
import { defineAsyncComponent } from 'vue'

export default {
  components: {
    Navbar: defineAsyncComponent(() => import("../components/Navbar.vue")),
    Entrylist: defineAsyncComponent(() => import("../components/Entrylist.vue")
    ),
  },
}
</script>
