<script>
export default {
  name: 'ContactMe'
}
</script>
<template>
    <div>
         <ul class="list-group list-custom">
            <li class="list-group-item">

            </li>
            <li class="list-group-item">
              <a href="https://twitter.com/abbey__solomon" target="_blank"><i class="fa fa-twitter"></i></a>
            </li>
            <li class="list-group-item">
              <a href="https://linkedin/in/azeez-abiodun/" target="_blank"><i class="fa fa-linkedin"></i>  </a>
            </li>
            <li class="list-group-item">
              <a href="https://github.com/iamhabbeboy" target="_blank"><i class="fa fa-github"></i>  </a>
            </li>
          </ul>
    </div>
</template>
<style scoped lang="scss">
.list-custom {
    margin-top: 100px;
    .list-group-item {
        background: transparent;
        border: 0px solid transparent;
        padding-top: 30px;
        padding-bottom: 30px;
        text-align: center;
        display: block;
        a {
            color: #FFF;
            font-size: 2rem;
            display: block;
        }
    }
}

@media (max-width:480px)  {
    .list-custom {
      margin: 0px;
      flex-direction: row !important;
          .list-group-item {
                display: inline-block !important;
                padding: 15px;
                a {
                    display: inline-block;
                }
            }
        li {
            display: inline-block !important;
        }
    }
    .last {
        height: 20px !important;
    }
}

</style>
