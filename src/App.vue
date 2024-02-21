<template>
  <a-card class="card" :bordered="false">
    <template #title>
      升级包内容&nbsp;&nbsp;&nbsp;&nbsp;
      <a-radio-group name="radioGroup">
        <a-radio value="1">占位1</a-radio>
        <a-radio value="2">占位2</a-radio>
      </a-radio-group>
      <a-divider type="vertical" />
      升级步骤
      <a-input/>
    </template>
    <a-checkbox>
      全选
    </a-checkbox>
  </a-card>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
