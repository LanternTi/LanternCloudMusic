<script setup>
import Header from './components/Header.vue';
import MySide from './components/MySide.vue';

</script>

<template>
  <div class="common-layout">
    <el-container>
      <el-header>
        <Header></Header>
      </el-header>
      <el-container>
        <el-aside width="20%">
          <MySide></MySide>
        </el-aside>
        <el-container>
          <el-main></el-main>
          <el-footer></el-footer>
        </el-container>
      </el-container>
    </el-container>
  </div>
</template>

<style>
#app {
  margin: 0 auto;
  width: 75%;
  border-radius: 5px;
  border: 1px solid rgb(151, 151, 151);
  min-width: 810px;
}

.el-header {
  background-color: rgb(47, 210, 239);
  border-radius: 5px 5px 0px 0px;
}
</style>