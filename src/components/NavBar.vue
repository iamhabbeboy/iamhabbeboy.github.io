<template>
  <div>
      <nav class="navbar navbar-expand-lg navbar-light container">
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <router-link class="nav-link" to="/">Home
                <span class="sr-only">(current)</span>
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/portfolio">Portfolio</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/blog">Skills</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/contact">Contact</router-link>
            </li>

          </ul>
        </div>
      </nav>
    </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.nav-link {
  padding: 10px 20px !important;
}

.navbar-light .navbar-nav .active>.nav-link, .navbar-light .navbar-nav .nav-link.active, .navbar-light .navbar-nav .nav-link.show, .navbar-light .navbar-nav .show>.nav-link {
  color: #dc3545;
}
</style>
