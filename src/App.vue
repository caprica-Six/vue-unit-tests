<template>
  <div id="app">
      <router-link to="/"><img alt="Vue logo" src="./assets/logo.png"></router-link>

      <Message msg="Awesome Vue"/>
      <SectionHeader />

      <main>
          <router-view />
      </main>
  </div>
</template>

<script>
    import SectionHeader from "@/components/SectionHeader"
    import Message from '@/components/Message'

export default {
  name: 'app',
  components: {
      SectionHeader,
      Message
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
