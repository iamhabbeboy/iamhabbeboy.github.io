<script>
import NavBar from '@/components/NavBar'
import ContactMe from '@/components/ContactMe'

export default {
  name: 'App',
  components: {
    NavBar,
    ContactMe
  }
}
</script>
<template>
  <div id="app">
    <div id="nav" style="position:fixed;height: 100%;width: 100%;">
      <div class="row  main-column">
        <div class="col-md-2 last">
           <div class="first-column__effect"></div>
         <ContactMe />
        </div>
        <div class="col-md-10 first">
          <NavBar/>
          <router-view/>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
html,
body {
  height: 100%;
}
#container {
  height: 100%;
  width: 100%;
  margin: 0 auto;
}
.main-column {
  height: 100vh;
}
.first {
  height: 100vh;
  overflow: scroll;
}
.last {
 /* background-image: url('../public/code.jpeg'), linear-gradient(top, #dc3545, #dc3545);*/
  background: linear-gradient(rgba(#dc3545, 0.5),rgba( #dc3545, 0.9));
}

  .first-column__effect {
    width: 150px;
    height: 150px;
    background: #FFF;
    position: absolute;
    left: 150px;
    top: 250px;
    border-radius: 100%;
  }

@media (max-width:480px)  {
    .last {
      height: 80px !important;
    }

    .first-column__effect {
      display: none;
    }

    #nav {
      position: relative !important;
      height: 30px !important;
    }

    .first {
      height: auto !important;
    }

}

</style>
