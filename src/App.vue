<template>
  <div class=" m-0 p-0 w-100">
    <div class="row m-0 p-0 w-100">
      <div class="col-xl-1" />
      <div class="col-xl-10">
        <div class="row m-0 p-0  ">
          <app-header />
        </div>
        <div class="row m-0 p-0">
          <router-view />
        </div>
        <div class="row m-0 p-0">
          <app-footer />
        </div>
      </div>
      <div class="col-xl-1" />
    </div>
  </div>
</template>
<script>
import Header from './components/Header'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    'app-header': Header,
    'app-footer': Footer
  },
  data () {
    return {
      
    }
  }
}
</script>
