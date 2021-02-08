<template>
  <form @submit.prevent="SubmitClick">
    <input v-model="text" type="text" placeholder="Search for joke...">
    <input type="submit" value="Search Joke">
  </form>
</template>

<script>
export default {
  name: 'Search',
  data () {
    return {
      text: ''
    }
  },
  methods: {
    SubmitClick () {
      this.$emit('search-text', this.text)
      this.text = ''
    }
  }
}
</script>

<style>

</style>
