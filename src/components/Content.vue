<template>
  <div>
    <h1>권하연</h1>
    <input type="text" v-model="introduce">
    <p>{{ message }}</p>
    <p>{{ introduce }}</p>
  </div>
</template>

<script>
export default {
    name: 'Content',
    data: function () {
        return {
            message: '안녕하세요. 권하연입니다.',
            introduce: '',
        }
    }
}
</script>

<style>

</style>
