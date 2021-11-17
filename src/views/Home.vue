<template>
  <div class="home">
    <div class="img">
      <img src="@/assets/images2/国际航空服务与管理_02.jpg" alt="">
    </div>
    <div class="title_warp">
      <p>
        <router-link to="/" tag="span">当前位置：首页 ></router-link>
        <router-link to="/" tag="span" class="hang">招生要求</router-link>
      </p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  components: {
  }
}
</script>
<style lang="scss" scoped>
.home{
  width: 3.75rem;
  margin: 0 auto;
}
.img{
  width: 100%;
  height: 1.49rem;
  img{
    width: 100%;
    height:100%;
  }
}
.title_warp{width:100%;padding:0 .2rem;margin: .15rem 0;box-sizing:border-box;
p{width: 100%;text-align:left;
span {font-size: .14rem;font-weight: normal;font-stretch: normal;line-height: .07rem;letter-spacing: 0px;color: #888888;}
.hang {margin-left: 0.05rem;font-family: PingFang-SC-Medium;font-size: .14rem;font-weight: normal;letter-spacing: 0px;color: #b0b0b0;}
}
}
</style>