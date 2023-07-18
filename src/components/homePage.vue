<template>
  <div>
<!--      <dropdown split-button type="primary">-->
<!--          Default-->
<!--          <template #dropdown>-->
<!--              <el-dropdown-menu>-->
<!--                  <el-dropdown-item>Taobao</el-dropdown-item>-->
<!--                  <el-dropdown-item>Tmall</el-dropdown-item>-->
<!--                  <el-dropdown-item>Jd</el-dropdown-item>-->
<!--              </el-dropdown-menu>-->
<!--          </template>-->
<!--      </dropdown>-->
      <div><el-input v-model="inputA" placeholder="Please input"/></div>

<!--      <div><el-button type="primary">Extract</el-button></div>-->
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'
const inputA = ref('')
</script>

<style scoped>

</style>