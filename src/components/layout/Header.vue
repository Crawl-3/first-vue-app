<template>
  <header class="header">
    <nav class="navbar">
      <div class="routes">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </div>
    </nav>

    <div class="helpfull-links">
      <!-- <h5>Visit:</h5> -->
      <div class="links">
        <a href="https://github.com/WitecuseDev/" target="_blank" rel="noopener noreferrer"
          >Github</a
        >
        <!-- <a href="/">Discord</a> -->
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #1d1d1d;
  padding: 0 15px;
  border-bottom: 1px solid #333;
  // navbar
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 75px;
    .routes {
      display: flex;
      gap: 10px;
      a {
        font-weight: 600;
        color: #7e7e7e;
        border-radius: 4px;
        transition: all 200ms cubic-bezier(0.17, 0.67, 0.83, 0.67);
        padding: 12px 15px;
        &:hover {
          background: #333;
          color: #a5a5a5;
        }
        &.router-link-exact-active {
          background: #444;
          color: #42b983;
        }
      }
    }
  }
  // helpfull-links
  .helpfull-links {
    // display: flex;
    // align-items: center;
    // justify-content: space-between;
    // h5 {
    //   color: #7578da;
    //   font-weight: 800;
    //   margin-right: 10px;
    //   cursor: default;
    // }
    .links {
      display: flex;
      gap: 10px;
      a {
        color: #35b87d;
        background: #444;
        padding: 1px 4px;
        border-radius: 3px;
        font-weight: 500;
        transition: all 100ms;
        &:hover {
          color: #208d5c;
          background: #333;
          text-decoration: underline;
        }
      }
    }
  }
}
</style>
