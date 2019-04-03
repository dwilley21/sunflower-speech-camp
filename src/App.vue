<template>
  <v-app>
     <v-toolbar>
        <v-toolbar-title>Sunflower Speech Camp</v-toolbar-title>
          <v-spacer></v-spacer>
             <v-toolbar-items class="hidden-sm-and-down">
                <v-btn flat>Home</v-btn>
                <v-btn flat>Camps</v-btn>
                <v-btn flat>Events</v-btn>
                <v-btn flat>Staff</v-btn>
                <v-btn flat>Register</v-btn>
              </v-toolbar-items>
            </v-toolbar>
    <v-content>
      <Home/>
      <Camps/>
      <Events/>
      <Staff/>
      <Register/>
    </v-content>
  </v-app>
</template>
<script>

import Home from './components/Home'
import Camps from './components/Camps'
import Events from './components/Events'
import Staff from './components/Staff'
import Register from './components/Register'
export default {
  name: 'App',
  components: {
    Home, 
    Camps,
    Events,
    Staff,
    Register
  },
  data () {
    return {
      //
    }
  }
}
</script>
<style lang="less">
 @primary-color: #8B4513;
 @secondary-color:#FFFF33;
</style>

