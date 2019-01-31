<script>
export default {
  name: 'Jumbotron'
}
</script>
<template>
<div class="row">
<div class="custom-jumbotron col-md-9">
    <h1> Hi, I'm Abiodun Solomon</h1>
    <p> A Software Developer from Nigeria, Who is passionate about technologies.</p>
    <p>Organizer of <a href="http://frontendug.github.io" target="_blank" class="text__link">Frontend User Group</a> and Co-organizer of Python Nigeria Community (Abeokuta).</p>
    <router-link to="contact" class="btn btn-danger btn-lg btn-custom"  >Hire Me </router-link>
    &nbsp; <a href="https://drive.google.com/file/d/1LhymPGgu7vJpRwJhCC4UVrgkWqBZgBrQ/view?usp=sharing" target="_blank" class="custom-jumbotron__link" >Checkout my resume</a>
</div>
</div>
</template>
<style lang="scss">
    .image-circle {
        width: 100px;
        max-width: 100%;
        height: 100px;
        border-radius: 100%;
    }
    .custom-jumbotron {
        margin-top: 100px !important;
        padding: 30px;
    }
    .btn-custom {
        margin-top: 15px;
        border-radius: 25px !important;
        padding-left: 50px;
        padding-right: 50px;
    }
    h1 {
        font-family: 'Raleway', sans-serif;
    }
    p:first-child {
        padding: 20px 0px 20px;
    }

    .text__link {
        color: rgba(220, 53, 69, 0.5);
        &:hover {
            color: #555;
        }
    }

    .custom-jumbotron__link {
        color: #666;
        position:relative;
        top: 9px;
        transition: .5s all;
        --webkit-transition: .5s all;
        &:hover {
            color: #000;
        }
    }
</style>
