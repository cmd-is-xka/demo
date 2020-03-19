<template>
  <div>
    <el-container>
      <el-main>
        <span class="welcome">Welcome</span>
        <br />
        <span class="info">我见过春日夏风秋叶冬雪，也踏遍南水北山东麓西岭，可这四季春秋，苍山泱水都不及你冲我展眉一笑。</span>
      </el-main>
    </el-container>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
.el-main {
  background-color: rgb(254, 240, 240);
  width: 1366px;
  height: 768px;
  text-align: center;
  background-image: url('../assets/picture.png');
}

.welcome {
  display: block;
  color: red;
  font-size: 150px;
}

.info {
  display: block;
  margin-top: 300px;
  color: #F56C6C;
  font-size: 66px;
}
</style>
