<template>
<!-- 默认布局 -->
  <section class="default-container">
    <article class="top-template">
      <ul>
        <li>
          <i class="icon el-icon-house"></i>
          <nuxt-link to="/home">首页</nuxt-link>
        </li>
        <li>
          <i class="icon el-icon-shopping-bag-1"></i>
          <nuxt-link to="/mall">商城</nuxt-link>
        </li>
        <li>
          <i class="icon el-icon-coordinate"></i>
          <nuxt-link to="/personal">个性化推荐</nuxt-link>
        </li>
      </ul>
    </article>
    <article class="content-file">
      <nuxt />
    </article>
  </section>
</template>
<style lang="stylus" scoped>
.default-container
  ul
    list-style none
    li
      float right 
  a
    text-decoration none
    color #959595
  .top-template
    display flex
    flex-direction column
    justify-content flex-end
    border-bottom solid 1px #cdcdcd
    li
      border-right 1px solid #cdcdcd
      padding-right 5px
      margin-right 5px
      .icon
        color #D97F97
</style>
