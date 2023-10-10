<template>
  <div>
    abc
  </div>
</template>

<script>
export default {
  name: 'sample',
  layout: 'ore',
  data(){
    return {
      header: {
        title: 'ページタイトル'
      }
    }
  },
  mounted() {
    this.updateHeader()
  },
  methods: {
    updateHeader() {
      this.$nuxt.$emit('updateHeader', this.header.title)
    }
  }
}
</script>
