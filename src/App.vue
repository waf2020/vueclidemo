<template>

  <div class="container">
    <div>
    <mt-header fixed title="小熊敬礼">
  <router-link to="/" slot="left">
    <mt-button icon="back">返回</mt-button>
  </router-link>
  <mt-button icon="more" slot="right"></mt-button>
</mt-header>
    </div>
      <div class="header_text">
        <span>商家登录</span>
        <span>注册</span>
      </div>
  <div class="mydiv">xixixi</div>
 
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style  scoped>
    * {
      margin: 0px;
      padding:0px;
    }
    .container {
      width: 100%;
    }
    .mint-header {
      background-color: #21418a;
      height: 45px;
      
    }
    .mint-header-title
    {
        font-size: 1.6rem;
    }
    .mydiv {
      font-size: 1.8rem;
    }
    
    
</style>>

</style>
