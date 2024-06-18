<template>
  <div class="person">
    <h2>姓名: {{ name }}</h2>
    <h2>年龄: {{ age }}</h2>
  </div>
</template>

<script lang="ts">
export default {
  name: 'Person',
  setup () {
    

    return {}
  }
}
</script>
 
<style lang="scss" scoped>
.person {
  background-color: #ddd;
  width: 100px;
  height: 100px;
  border-radius: 50%
}
</style>