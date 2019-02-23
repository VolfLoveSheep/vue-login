<template>
  <div>
    <h1>登录</h1>
    <el-form   label-width="80px">
      <el-form-item label="用户名">
        <el-input v-model="usrname"></el-input>
      </el-form-item>
    <el-form-item label="密码">
        <el-input v-model="password"></el-input>
      </el-form-item>
    
      <el-form-item>
        <el-button type="primary" @click="onSubmit">登录</el-button>
       
      </el-form-item>
    </el-form>
  </div>
</template>
<script>
export default {
    data(){
        return {
            usrname:'',
            password:''
        }
    },
    methods:{
      onSubmit(){
        console.log('123');
        
      }
    }
}
</script>
<style lang="less" scoped>

</style>


