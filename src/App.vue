<template>
  <div id="q-app">
    <router-view />
  </div>
</template>
<script lang="ts">
import 'animate.css';
import {Vue, Component} from 'vue-property-decorator';
import AOS from 'aos';

import 'aos/dist/aos.css'

@Component
export default class App extends Vue {
 created(){
  AOS.init();
}

}

</script>
