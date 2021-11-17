<template>
  <div class="home">
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
.title_warp{width:100%;padding:0 .2rem;margin: .15rem 0;box-sizing:border-box;
p{width: 100%;text-align:left;
span {font-size: .14rem;font-weight: normal;font-stretch: normal;line-height: .07rem;letter-spacing: 0px;color: #888888;}
.hang {margin-left: 0.05rem;font-family: PingFang-SC-Medium;font-size: .14rem;font-weight: normal;letter-spacing: 0px;color: #b0b0b0;}
}
}
</style>