<template>
  <!-- <div :class="myClass"> -->
  <div v-bind="$attrs">
    This is the Erik Component
  </div>
  <div>
    Second Root node
  </div>

</template>

<script>


export default {
  name: 'App',
  inheritAttrs: true,
  components: {
  },
  computed: {
      myClass(){
        return this.$attrs.class
      }
  },
  mounted(){
    console.log(this.$attrs)
  }
}
</script>