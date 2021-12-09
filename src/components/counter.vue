<template>
  <div class="button-section">
    <button @click="count++">Counter</button>
    <p>{{ count }}</p>
  </div>
</template>
<script>
export default {
  data () {
    return {
      count: 0,
    };
  },
};
</script>
<style lang="scss" scoped>
.button-section {
  border: 1px solid #dae2e9;
  background-color: #f4f7fa;
  border-radius: 20px;
  width: 10%;
  text-align: center;
  margin: 0px auto;
  button {
    padding: 10px;
    background-color: #046eff;
    color: white;
    border: none;
    border-radius: 10px;
    margin: 15px;
  }
}
</style>
