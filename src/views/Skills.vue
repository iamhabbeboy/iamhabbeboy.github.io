<template>
  <div class="row">
    <div class="custom-jumbotron col-md-9">
      <h1> Skills</h1>
      <p> Below are my professional skills.</p>
      <div class="skill__section">
        <h4>Backend </h4>
        <hr>
        <div class="row">
          <div class="col-md-2 text-center">
            <img src="../../public/skills/php.png" class="image-custom">
            <b>PHP</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/laravel.png" class="image-custom">
            <b>Laravel</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/lumen.png" class="image-custom">
            <b>Lumen</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/python.jpeg" class="image-custom">
            <b>Python</b>
          </div>
        </div>
      </div>
      <div class="skill__section">
        <h4>Frontend </h4>
        <hr>
        <div class="row">
          <div class="col-md-2 text-center">
            <img src="../../public/skills/html5.png" class="image-custom">
            <b>HTML5</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/sass.png" class="image-custom">
            <b>CSS+SASS</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/js.png" class="image-custom">
            <b>JavaScript</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/angular.png" class="image-custom">
            <b>AngularJS</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/vuejs.png" class="image-custom">
            <b>VueJS</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/react.png" class="image-custom">
            <b>ReactJS</b>
          </div>
        </div>
      </div>
      <div class="skill__section">
      	<h4>Database </h4>
        <hr>
        <div class="row">
          <div class="col-md-2 text-center">
            <img src="../../public/skills/mysql.png" class="image-custom">
            <b>MySQL</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/sqlite.jpeg" class="image-custom">
            <b>SQLite</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/redis.png" class="image-custom">
            <b>Redis</b>
          </div>
        </div>
      </div>
      <div class="skill__section">
        <h4>Mobile </h4>
        <hr>
        <div class="row">
          <div class="col-md-2 text-center">
            <img src="../../public/skills/react-native.png" class="image-custom">
            <b>React Native</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/ionic.png" class="image-custom">
            <b>Ionic cordova</b>
          </div>
        </div>
      </div>
      <div class="skill__section">
        <h4>Others </h4>
        <hr>
        <div class="row">
          <div class="col-md-2 text-center">
            <img src="../../public/skills/docker.png" class="image-custom">
            <b>Docker</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/git.png" class="image-custom">
            <b>Git</b>
          </div>
          <div class="col-md-2 text-center">
            <img src="../../public/skills/phpunit.png" class="image-custom">
            <b>Unit testing</b>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.custom-jumbotron {
  margin-top: 50px !important;
  padding: 30px;

}

.image-custom {
  width: 100%;
  max-width: 50px;
  display: block;
  margin: auto;
}

b {
  font-family: 'Raleway', sans-serif;
  text-transform: uppercase;
  font-size: 11px;
  /*-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;*/
}

.skill__section {
  margin-top: 40px;
}

</style>
