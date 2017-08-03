<template>
  <div>
    <div class="hipster-card-box">
      <div class="hipster-card"
        :class="{ 'hipster-card-with-border': border }">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
  import hCardContent from './HipsterCardContent'
  export default {
    components: { hCardContent },
    data () {
      return {
        cardClasses: ''
      }
    },
    props: {
      border: {
        type: Boolean,
        default: false
      }
    },
    created () {
      console.log(this.$el)
    }
  }
</script>

<style src="./../../static/css/hipster_cards.css"></style>