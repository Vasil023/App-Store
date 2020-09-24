<template>
 <div class="wrapper">
  <div class="navbar">
    <div class="container">
    <div class="navbar-content">
      <div class="logo">
        VUE-CLI
        </div>
      <!-- /.logo -->
        <ul class="navbar-list">
          <li class="navbar-item">
            <router-link class="navbar-link" to="/">Home</router-link>
          </li>
           <li class="navbar-item">
            <router-link class="navbar-link" to="/example">Example</router-link>
          </li>
        </ul>
    </div>
    <!-- /.navbar-content -->
  </div>
<!-- /.container -->
  </div>
  <!-- /.navbar -->
   <router-view></router-view>
 </div>
 <!-- /.wrapper -->
</template>

<script>


export default {
  name: 'App',
  components: {
   
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
