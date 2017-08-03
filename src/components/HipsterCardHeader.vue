<template>
  <div class="header">
    <img :src="img" :alt="imgAlt">
  </div>
</template>

<script>
  export default {
    props: {
      img: String,
      imgAlt: String
    }
  }
</script>