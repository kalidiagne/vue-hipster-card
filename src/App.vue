<template>
  <div id="app">
    <h-card :border="true">
      <h-card-header img="http://via.placeholder.com/350x500">

      </h-card-header>
      <h-card-content title="titolo" description="Lorem ipsum dolor sit amet."> </h-card-content>
    </h-card>
  </div>
</template>

<script>
import hCard from './components/VueHipsterCard'
import hCardHeader from './components/HipsterCardHeader'
import hCardContent from './components/HipsterCardContent'
export default {
  name: 'app',
  components: {
    hCard,
    hCardHeader,
    hCardContent
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
