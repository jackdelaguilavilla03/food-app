<template>
  <div id="app">
    <div class="navbar-container">
      <div class="navbar-content">
        <router-link to="/">
          <box-icon name="home-alt-2" color="gray"></box-icon>
        </router-link>
        <router-link to="/shop">
          <box-icon name="basket" color="gray"></box-icon>
        </router-link>
        <router-link to="/bookmark">
          <box-icon name="bookmark" color="gray"></box-icon>
        </router-link>
        <router-link to="/profile">
          <box-icon name="user-circle" color="gray"></box-icon>
        </router-link>
      </div>
    </div>
    <router-view />
  </div>
</template>

<script>
// @ is an alias to /src
</script>
<style lang="less">
.navbar-container {
  position: fixed;
  bottom: 0;
  width: 100%;

  .navbar-content {
    padding: 20px;
    display: flex;
    justify-content: space-between;

    a {
      color: rgba(163, 163, 163);
      &.router-link-active {
        color: rgba(255, 131, 62);
      }
    }
  }
}

#app {
  font-family: "Open Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

* {
  padding: 0;
  margin: 0;
}
</style>
