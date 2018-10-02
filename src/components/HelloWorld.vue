<template>
  <div class="hello">
    <h3>hey hi</h3>
      <p>I am a rendered prop in a Vue component that has been tested with</p>
          <ul>
            <li
                v-for="link in links"
                :key="link.id">
                <a :href="link.url" target="blank">{{ link.name }}</a>
            </li>
        </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
    data() {
      return {
          links: [
              {
                  id: 1,
                  name: "vue cli service",
                  url: "https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-unit-jest"},
              {
                  id: 2,
                  name: "jest",
                  url: "https://jestjs.io/docs/en/testing-frameworks#vuejs"
              }
          ]
      }
    }
}
</script>

<style scoped>

</style>
