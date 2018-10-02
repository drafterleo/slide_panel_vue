<template>
  <div id="app">
    <Push>
      <a href="#">
        <i class="fa fa-fw fa-star-o"></i>
        <span>Favourites</span>
      </a>
      <a href="#">
        <i class="fa fa-fw fa-bell-o"></i>
        <span>Alerts</span>
      </a>
      <a href="#">
        <i class="fa fa-fw fa-envelope-o"></i>
        <span>Messages</span>
      </a>
      <a href="#">
        <i class="fa fa-fw fa-comment-o"></i>
        <span>Comments</span>
      </a>
      <a href="#">
        <i class="fa fa-fw fa-bar-chart-o"></i>
        <span>Analytics</span>
      </a>
      <a href="#">
        <i class="fa fa-fw fa-newspaper-o"></i>
        <span>Reading</span>
      </a>
    </Push>
  </div>
</template>

<script>
  import { Push } from 'vue-burger-menu'

  export default {
    name: 'app',
    components: {
      Push
    },
    data () {
      return {
        showLeftPanel: true,
      }
    }
  }
</script>

<style>

</style>
