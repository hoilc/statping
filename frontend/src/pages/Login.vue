<template>
    <div class="container col-md-7 col-sm-12 mt-md-5">
        <div class="col-10 offset-1 col-md-8 offset-md-2 mt-md-2">
            <div class="col-12 col-md-8 offset-md-2 mb-4">
                <img alt="Statping Login" class="col-12 mt-5 mt-md-0" style="max-width:650px" src="banner.png">
            </div>
            <FormLogin/>
        </div>
    </div>
</template>

<script>
  const FormLogin = () => import('@/forms/Login')

  export default {
  name: 'Login',
  components: {
      FormLogin
  },
  data () {
    return {

    }
  },
    mounted() {

    },
    methods: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
