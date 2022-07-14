<template>

  <div class="container">
    <app-header></app-header>
    <hr>
    <app-main></app-main>
    <hr>
    <app-footer></app-footer>
  </div>
  
</template>

<script>

import HeaderPage from "./Header";
import FooterPage from "./Footer";
import MainerPage from "./Mainer";

export default {

  components: {
    'app-header': HeaderPage,
    'app-footer': FooterPage,
    'app-main': MainerPage,
  }



}
</script>


