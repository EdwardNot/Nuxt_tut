<template>
  <div>
      <h1>About TestApp</h1>
      <p>Thi is test app</p>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'About test app',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Some test of nuxt app'
        }
      ]
    }
  }
}
</script>

<style>

</style>
