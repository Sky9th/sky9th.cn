<template>
  <div class="home">
    <!-- Floating Shards -->
    <img src="@/assets/images/skyadmin/logo.png" alt="Shard" class="shard">

    <!-- Welcome Section -->
    <div class="welcome d-flex justify-content-center flex-column">
      <div class="inner-wrapper mt-auto mb-auto">
        <h1>SkyAdmin</h1>
        <p class="welcome-title">基于TP6.0以及Vue2.0的后台管理系统</p>
        <div class="action-links">
          <!--<a class="btn btn-primary btn-pill align-self-center mr-2 disabled"><i class="fa fa-download mr-1"></i>
            Download Now</a>-->
          <a data-scroll-to="#introduction" id="scroll-to-content"
             class="btn btn-outline-light btn-pill align-self-center disabled">Learn More</a>
        </div>
        <div class="github">

          <div class="section-title col-lg-8 col-md-10 ml-auto mr-auto">
            <h3 class="mb-4"><a href="https://github.com/Sky9th/sky-admin-api">SkyAdminVue —— 前端</a></h3>
            <p class="intro">SkyAdmin是使用基于D2Admin开发的内容管理系统前端框架，使用vue-cli3构建，具备基本的RBAC管理功能，集成 element-UI, Fontawesome等多种常用库，助力敏捷开发</p>
            <p><img v-for="(item, index) in vueGithub" :alt="item.split(',')[0]" :src="item.split(',')[1]" :key="index"></p>
          </div>

          <div class="section-title col-lg-8 col-md-10 ml-auto mr-auto">
            <h3 class="mb-4"><a href="https://github.com/Sky9th/sky-admin-vue">SkyAdminApi —— 后端</a></h3>
            <p class="intro">SkyAdmin是使用基于ThinkPHP6.0开发的后端接口支撑框架，采用Mysql数据库，集成EasyWechatSDK，支持微信、小程序对接。完全RestFul接口，具备基本的接口加密技术，助力敏捷开发</p>
            <p><img v-for="(item, index) in apiGithub" :alt="item.split(',')[0]" :src="item.split(',')[1]" :key="index"></p>
          </div>

        </div>
      </div>
    </div>

    <!-- Page Content -->
    <div class="page-content">
      <!-- Content -->
      <div class="content clearfix">

        <div id="introduction" class="container mb-5">
          <div class="section-title col-lg-8 col-md-10 ml-auto mr-auto">
            <p class="lead">从事程序员也有一段时间了，SkyAdmin是入行以来下定决心对自己有一个交代而做的后台管理系统，同时也希望这个管理系统能够帮助日后在工作中可以为自己节省时间。秉承着开源互助的精神，该后台管理系统也是站在众多巨人的肩膀上才能开发出来，所以分享出来也希望能给予其他人帮助的同时，能依靠大家的力量去完善这个系统</p>
          </div>
        </div>

        <!-- Colors -->
        <div id="colors" class="container mb-5">

          <div class="section-title col-lg-8 col-md-10 ml-auto mr-auto">
            <h3 class="mb-4">相关项目</h3>
            <p>在此会展示基于SKyAdmin作为后台管理的其他相关项目</p>
          </div>

          <div class="example col-md-10 ml-auto mr-auto">
            <div class="row">
              <div class="color-wrapper col-lg-3 col-md-6 col-sm-6">
                <div class="color">
                  <div class="swatch" style="background: #0067f4"></div>
                  <span class="title">SkyChat</span>
                  <span class="hex-value">一个Unity3D引擎做的小游戏</span>
                </div>
              </div>

              <div class="color-wrapper col-lg-3 col-md-6 col-sm-6">
                <div class="color">
                  <div class="swatch" style="background: #5A6169"></div>
                  <span class="title">SkyMall</span>
                  <span class="hex-value">基本功能的B2C单用户商城</span>
                </div>
              </div>
            </div>
          </div>

        </div>
        <div class="tlinks">Collect from <a href="http://www.cssmoban.com/">网站建设</a></div>

        <!-- Typography -->
        <div id="typography" class="container mb-5">
          <div class="section-title col-lg-8 col-md-10 ml-auto mr-auto">
            <h3 class="mb-4">技术栈</h3>
            <p>本项目使用到的相关框架、语言、软件，排名不分先后</p>
          </div>

          <div class="example col-md-10 ml-auto mr-auto">
            <table class="table table-striped">
              <thead>
              <tr>
                <th>语言/框架</th>
                <th>版本</th>
                <th>相关链接</th>
              </tr>
              </thead>
              <tbody>
              <tr>
                <td>
                  <h3>ThinkPHP</h3>
                </td>
                <td>6.0</td>
                <td><a href="http://www.thinkphp.cn/">http://www.thinkphp.cn/</a></td>
              </tr>
              <tr>
                <td>
                  <h3>D2Admin</h3>
                </td>
                <td>1.8</td>
                <td><a href="https://d2-admin.netlify.com/#/login?redirect=%2Findex">https://d2-admin.netlify.com/#/login?redirect=%2Findex</a></td>
              </tr>
              <tr>
                <td>
                  <h3>Vue</h3>
                </td>
                <td>2.0</td>
                <td><a href="https://cn.vuejs.org/">https://cn.vuejs.org/</a></td>
              </tr>
              <tr>
                <td>
                  <h3>Mysql</h3>
                </td>
                <td>5.*</td>
                <td><a href="https://www.mysql.com/">https://www.mysql.com/</a></td>
              </tr>
              <tr>
                <td>
                  <h3>PHP</h3>
                </td>
                <td>7.1.*</td>
                <td><a href="https://www.php.net/">https://www.php.net/</a></td>
              </tr>
              <tr>
                <td>
                  <h3>HTML/CSS/Javascript</h3>
                </td>
                <td></td>
                <td></td>
              </tr>
              </tbody>
            </table>
          </div>
        </div>

      </div>

      <footer class="main-footer py-5">
        <p class="text-muted text-center small p-0 mb-4">&copy; Copyright 2020 — Sky9th & <a href="http://www.beianbeian.com/" target="_blank">粤ICP备15083833号</a></p>
      </footer>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
    name: 'home',
    components: {},
    data () {
        return {
            vueGithub: [
                'GitHub issues,https://img.shields.io/github/issues/Sky9th/sky-admin-vue',
                'GitHub forks,https://img.shields.io/github/forks/Sky9th/sky-admin-vue',
                'GitHub stars,https://img.shields.io/github/stars/Sky9th/sky-admin-vue',
                'GitHub license,https://img.shields.io/github/license/Sky9th/sky-admin-vue'
            ],
            apiGithub: [
                'GitHub issues,https://img.shields.io/github/issues/Sky9th/sky-admin-api',
                'GitHub forks,https://img.shields.io/github/forks/Sky9th/sky-admin-api',
                'GitHub stars,https://img.shields.io/github/stars/Sky9th/sky-admin-api',
                'GitHub license,https://img.shields.io/github/license/Sky9th/sky-admin-api'
            ]
        }
    }

}
</script>
