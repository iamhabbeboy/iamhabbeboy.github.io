<script>
export default {
  name: 'portfolio',
  mounted () {
    var selectedClass = ''
    $('.fil-cat').click(function () {
      selectedClass = $(this).attr('data-rel')
      $('#portfolio').fadeTo(100, 0.1)
      $('#portfolio div')
        .not('.' + selectedClass)
        .fadeOut()
        .removeClass('scale-anm')
      setTimeout(function () {
        $('.' + selectedClass)
          .fadeIn()
          .addClass('scale-anm')
        $('#portfolio').fadeTo(300, 1)
      }, 300)
    })
  }
}
</script>
<template>
  <div class="row">
    <div class="custom-jumbotron col-md-9">
      <h1>My Recent Job Done</h1>
      <p>Check out my recent projects</p>

      <div class="clearfix"></div>
      <div class="toolbar mb2 mt2">
        <button class="btn fil-cat" href data-rel="all">All</button>
        <button class="btn fil-cat" data-rel="web">Wordpress</button>
        <button class="btn fil-cat" data-rel="flyers">Web App</button>
        <!-- <button class="btn fil-cat" data-rel="bcards">Mobile App</button> -->
      </div>

      <div style="clear:both;"></div>
      <div id="portfolio">
        <div class="tile scale-anm web all">
          <a href="https://abbisfarmltd.com" target="_blank" title="Abbisfarmltd">
          <img
            src="../../public/portfolio/abbisfarmltd.png"
            alt
          >
        </a>
        </div>
        <div class="tile scale-anm web all">
          <a href="https://amazingfoods.org.uk" target="_blank" title="Amazingfoods">
          <img
            src="../../public/portfolio/amazingfoods.png"
            alt
          >
        </a>
        </div>
        <div class="tile scale-anm web all">
          <a href="#" target="_blank" title="platformtimes">
          <img
            src="../../public/portfolio/platformtimes.jpg"
            alt
          >
        </a>
        </div>
        <div class="tile scale-anm bcards all">
          <a href="http://veritasmeds.com.ng" target="_blank" title="Veritasmeds">
          <img
            src="../../public/portfolio/veritasmeds.png"
            alt
          >
        </a>
        </div>

        <div class="tile scale-anm flyers all">
          <a href="https://hotels.ng" target="_blank" title="Hotels.ng">
          <img
            src="../../public/portfolio/hotelsng.png"
            alt
          >
        </a>
        </div>
        <div class="tile scale-anm flyers all">
          <a href="http://frontendug.github.io" target="_blank" title="FrontendUG">
          <img
            src="../../public/portfolio/frontendug.png"
            alt
          >
        </a>
        </div>
        <div class="tile scale-anm flyers all">
          <a href="https://payroll.abbisfarmltd.com" title="Abbisfarmltd payroll system">
          <img
            src="../../public/portfolio/payroll.png"
            alt
          >
        </a>
        </div>
        <div class="tile scale-anm flyers all">
          <a href="https://timbu.com" target="_blank" title="Timbu ">
          <img
            src="../../public/portfolio/timbu.png"
            alt
          >
        </a>
        </div>

        <div class="tile scale-anm web all">
          <a href="http://fowoso.com" target="_blank" title="Fowoso">
          <img
            src="../../public/portfolio/fowoso.png"
            alt
          >
        </a>
        </div>

          <div class="tile scale-anm flyers all">
          <a href="http://115garage.com" target="_blank" title="115garage">
            <img
              src="../../public/portfolio/115garage.png"
              alt
            >
        </a>
        </div>

        <div class="tile scale-anm web all">
          <a href="http://115garage.com" target="_blank" title="115garage notification system">
          <img
            src="../../public/portfolio/115garage.png"
            alt
          >
          </a>
        </div>
      </div>

      <div style="clear:both;"></div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.toolbar {
  margin-top: 50px;
}

button.btn:first-child {
  border-left: 1px solid #555 !important;
}
.btn {
  border-radius: 0px !important;
  border-left: 0px !important;
  padding-left: 50px !important;
  padding-right: 50px !important;
}
.custom-jumbotron {
  margin-top: 50px !important;
  padding: 30px;
}

#portfolio {
  margin: 1rem 0;
  -webkit-column-count: 3;
  -moz-column-count: 3;
  column-count: 3;
  -webkit-column-gap: 1rem;
  -moz-column-gap: 1rem;
  column-gap: 1rem;
  -webkit-column-width: 33.33333333333333%;
  -moz-column-width: 33.33333333333333%;
  column-width: 33.33333333333333%;
}
.tile {
  -webkit-transform: scale(0);
  transform: scale(0);
  -webkit-transition: all 350ms ease;
  transition: all 350ms ease;
}

.scale-anm {
  transform: scale(1);
}

button {
  padding: 10px;
  text-decoration: none;
  font-family: lato;
  text-transform: uppercase;
  font-size: 12px;
  color: #333;
  display: block;
  float: left;
}

button:hover {
  cursor: pointer;
  background: #333;
  color: #eee;
}

.tile img {
  max-width: 100%;
  width: 100%;
  height: auto;
  margin-bottom: 1rem;
}

.btn {
  font-family: Lato;
  font-size: 1rem;
  font-weight: normal;
  text-decoration: none;
  cursor: pointer;
  display: inline-block;
  line-height: normal;
  padding: 0.5rem 1rem;
  margin: 0;
  height: auto;
  border: 1px solid;
  vertical-align: middle;
  -webkit-appearance: none;
  color: #555;
  background-color: rgba(0, 0, 0, 0);
}

.btn:hover {
  text-decoration: none;
}

.btn:focus {
  outline: none;
  border-color: var(--darken-2);
  box-shadow: 0 0 0 3px var(--darken-3);
}

::-moz-focus-inner {
  border: 0;
  padding: 0;
}
</style>
