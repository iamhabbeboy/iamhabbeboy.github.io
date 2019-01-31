<template>
  <div class="about">
    <div class="row">
<div class="custom-jumbotron col-md-9">
    <h1> Contact </h1>
    <p> Incase you want me on your next project, please do get in touch.</p>

    <form action="https://formspree.io/abiodun.solomon.a@gmail.com" method="POST" >
      <div class="form-group">
        <input type="text" class="form-control" placeholder="Full Name" name="name" autocomplete="off" spellcheck="false" required="">
        </div>
        <div class="form-group">
        <input type="text" class="form-control" placeholder="Email Address" name="email" autocomplete="off" spellcheck="false" required="">
        </div>
         <div class="form-group">
        <textarea class="form-control" placeholder="Tell me something" name="message" required="" autocomplete="off" spellcheck="false"></textarea>
        </div>
         <button class="btn btn-danger btn-lg btn-custom" type="submit">Get In Touch</button>
      </form>

</div>
</div>
  </div>
</template>

<style scoped>
.form-control {
  border-radius: 30px;
  padding: 20px !important;
  font-family: 'Raleway', sans-serif;
}

 .custom-jumbotron {
    margin-top: 50px !important;
    padding: 30px;
 }

</style>
