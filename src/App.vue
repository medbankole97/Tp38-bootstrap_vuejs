<template>
<div id="app">
 <NavbarComponent />
 <JumbotronComponent/>
 <CtaComponent/>
 <CardComponent />
 <FooterComponent />
</div>
  
</template>

<script>
import NavbarComponent from './components/NavbarComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';
import CtaComponent from './components/CtaComponent.vue';
import CardComponent from './components/CardComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
  name: 'App',
  components: {
   NavbarComponent,
   JumbotronComponent,
   CtaComponent,
   CardComponent,
   FooterComponent,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
