<template>
  <div >
    <Header class="header_main" ></Header>
    <LeftRect class="left_rect"></LeftRect>
        <div id="app" class="app">
          <UpperRectangle></UpperRectangle>
          <Checkboxes></Checkboxes>
          <InfoMain></InfoMain>
          <chart2></chart2>
          <chart></chart>
        </div>
    <Footer class="footer_main"></Footer>
  </div> 
</template>

<script>
import Chart from "./components/Chart";
import Chart2 from './components/Chart2';
import Header from './components/Header';
import Footer from './components/Footer';
import InfoMain from './components/InfoMain';
import LeftRect from './components/LeftRect';
import Checkboxes from './components/Checkboxes';
import UpperRectangle from './components/UpperRectangle';



export default {
  name: "app",
  components: {
    chart: Chart,
    chart2: Chart2,
    InfoMain,
    Header,
    Footer,
    LeftRect,
    Checkboxes,
    UpperRectangle,
  },
  methods: {
    handler() {
      var args = arguments;
      for (var arg of args) {
        if (arg instanceof Function) {
          arg();
        }
      }
    }
  }
};
</script>

<style>
    @font-face {
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
    src: local('Montserrat Regular'), local('Montserrat-Regular'),
         url('../public/style/fonts/montserrat-v15-latin-regular.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
         url('../public/style/fonts/montserrat-v15-latin-regular.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
  }
  /* montserrat-500 - latin */
  @font-face {
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 500;
    src: local('Montserrat Medium'), local('Montserrat-Medium'),
         url('../public/style/fonts/montserrat-v15-latin-500.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
         url('../public/style/fonts/montserrat-v15-latin-500.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
  }
  /* montserrat-600 - latin */
  @font-face {
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    src: local('Montserrat SemiBold'), local('Montserrat-SemiBold'),
         url('../public/style/fonts/montserrat-v15-latin-600.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
         url('../public/style/fonts/montserrat-v15-latin-600.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
  }
  html{
      box-sizing: border-box;
  }
  *, *::before, *::after{
      box-sizing: inherit;
  }
  body{
    max-width: 1920px;
    max-height: 950px;
    margin: 0px;
    background:  #E5E5E5; 
    font-family: 'Montserrat';
    font-style: normal;
    font-size: 16px;
    line-height: 1.2;
    font-weight: normal;
    /* max-width: 1920px; */
  }
</style>

<style scoped>
  .header_main{
    position: absolute;
    left:0px;
    top:0px;
  }
  .left_rect{
    position: absolute;
    left:0px;
    top: 48px;
  }
  #app{
    position: absolute;
    left: 120px;
    top: 48px;
    background: #E5E5E5;
  }
  .footer_main{
    position: absolute;
    left: 120px;
    top: 878px; /* position start from #app(first positionered el) */
  }
</style>
