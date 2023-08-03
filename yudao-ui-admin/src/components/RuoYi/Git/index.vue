<template>
  <div>
    <svg-icon icon-class="github" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'XingHeGit',
  data() {
    return {
      url: 'https://github.com/xingheDYL/ruoyi-vue-pro'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
