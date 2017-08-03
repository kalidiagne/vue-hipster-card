<template>
  <div class="content">
    <h6 v-if="category" class="category"> {{ category }} </h6>
    <h4 v-if="title" class="title"> {{ title }} </h4>
    <p v-if="description" class="description"> {{ description }} </p>
  </div>
</template>

<script>
  export default {
    props: {
      title: String,
      description: String,
      category: [String, Number]
    }
  }
</script>