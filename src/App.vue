<template>
  <app-header></app-header>
  <router-view></router-view>
  <app-footer></app-footer>
</template>

<script>
import appHeader from './views/app-header.vue'
import appFooter from './views/app-footer.vue'
export default {
  name: 'app',
  data() {
    return {
    }
  },
  components:{
    appHeader,
    appFooter
  }
}
</script>