<template>
  <div>
    <h2>Welocme</h2>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'Welcome to test app',
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
