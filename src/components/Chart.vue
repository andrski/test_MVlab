<template>
  <div >
    <highcharts class="chart" :options="chartOptions" ref="chart"></highcharts>
  </div>
</template>

<script>
export default {
   methods: {
    fetchData() {
      fetch('https://demo-live-data.highcharts.com/aapl-c.json')
      .then(response => {
        return response.json()
      })
      .then(data => {
        this.chartOptions.series[0].data = data;
      })
    },
  },

  beforeMount(){
    this.fetchData();
 },

  data() {
    return {
      chartOptions: {
        rangeSelector: {
            selected: 1
        },

        title: {
            text: 'test MVlab'
        },

        series: [{
            name: 'data from demo, your link failed',
            data: [],
            step: true,
            tooltip: {
                valueDecimals: 2
            }
        }]
      }
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .chart{
    position: absolute;
    left: 48px;
    top: 301px;

    width: 1680px;
    height: 216px;
  }
</style>
