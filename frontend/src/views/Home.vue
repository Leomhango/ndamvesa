<template>
  <div class="home">
    <p class="text-3xl">{{string}}</p>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  data() {
    return {
      string: 'Hello, world'
    }
  }
}
</script>
