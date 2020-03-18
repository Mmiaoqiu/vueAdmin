<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
import Cookies from 'js-cookie'

export default {
  name: 'App',
  mounted() {
    // Cookies.remove('Admin-Token')
    //
    // Cookies.set('Admin-Token', 'admin')
  }
}
</script>
