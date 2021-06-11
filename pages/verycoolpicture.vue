<template>
  <div class="container">
    <div>
      <h1 class="title">
        Very Cool Picture
      </h1>
       <h4><a href="/">← Go back</a></h4>
       <img src="~/assets/img100.jpg">
    </div>
  </div>
</template>

<script>
import { } from '@nuxtjs/sanity'

export default { }
</script>

<style>
.container {
  margin: 2rem;
  min-height: 100vh;
  background-color: lightgreen;
}

.posts {
  margin: 2rem 0;
}
.summary { margin-top: 0.5rem; }
</style>
