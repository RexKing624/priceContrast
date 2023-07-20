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
      <div><el-input v-model="input" placeholder="Please input"/></div>
      <el-text class="mx-1" type="danger">Price {{text}}</el-text>
      <div><el-button type="primary" @click="useBut()">Extract</el-button></div>

  </div>
</template>

<script lang="ts" setup>

// import testHtml from "./testHtml/testPage.html";
import { ref } from 'vue'
const input = ref('')
const text = ref('no')
function useBut(){

    // console.log('123123')
    console.log(this.input)
    this.text = this.input
    window.location.href =this.input
    console.log(testHtml)
    // location.replace =this.input

}
function reverseMessage() {

}

</script>

<style scoped>

</style>