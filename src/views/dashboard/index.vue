<template>
  <div class="container">

  </div>
</template>
<script>
import { mapGetters } from 'vuex'
export default {
  name: 'Dashboard',
  methods: {
  },
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>
<style scoped>
.container {
  margin: 30px;
}
.template {
  background-color: #EBEEF5
}
.bg-purple {
  background: #d3dce6;
}
.bg-purple-light {
    background: #e5e9f2;
  }
.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
.text {
  font-size: 25px;
  line-height: 46px;
}
</style>
