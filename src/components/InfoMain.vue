<template>
  <div>
    <div class="info_main_big">
        <p class="info_oee">OEE</p>
        <p class="info_multyplication">AxPxQ</p>
        <p class="info_multy_proc">40%x60%x100%</p>
        <p class="info_target">Цель: 65%</p>
        <p class="info_base">Базовый:45%</p>
        <p class="info_proc_num">24%</p>
    </div>

    <div class="info_aviability">
        <p class="info_aviab">Availability</p>
        <p class="aviab_proc_numb">40%</p>
    </div>  

    <div class="info_perfomance">
        <p class="info_perfom">Performance</p>
        <p class="aviab_perfom_numb">60%</p>
    </div>  

    <div class="info_quality">
        <p class="info_qual">Quality</p>
        <p class="aviab_quality_numb">100%</p>
    </div>

    <div class="info_text_p">
        <p class="pi info_total_i">Общее время</p>
        <p class="pi info_total_text">99999999999999</p>

        <p class="pi info_downtime_i">Время простоя</p>
        <p class="pi info_downtime_text">99999999999999</p>

        <p class="pi info_danger_i">Время аварий</p>
        <p class="pi info_danger_text">99999999999999</p>

        <p class="pi info_outwork_i">Время в выключении</p>
        <p class="pi info_outwork_text">99999999999999</p>

        <p class="pi info_worktime_i">Время работы</p>
        <p class="pi info_worktime_text">99999999999999</p>
    </div>    
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  }
};
</script>

<style scoped>
    .info_main_big{
      position: absolute;
      left: 24px;
      top: 73px;

      width: 304px;
      height: 156px;
      background: #F8D7DA;
    }
    .info_aviability{
      position: absolute;
      left: 334px;
      top: 73px;

      width: 100px;
      height: 48px;
      background: #F8D7DA;
    }
    .info_perfomance{
      position: absolute;
      left: 334px;
      top: 127px;

      width: 100px;
      height: 48px;
      background: #FFF3CD;
    }
    .info_quality{
      position: absolute;
      left: 334px;
      top: 181px;

      width: 100px;
      height: 48px;
      background: #CCE5FF;
    }
    .info_text_p{
      position: absolute;
      left: 470px;
      top: 73px;

      width: 117px;
      height: 144px;
      
    }
    .pi{
      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 10px;
      line-height: 12px;
    }
    .info_total_i{
      position: absolute;
      top: 0px;
    }
    .info_total_text{
      position: absolute;
      top: 12px;
    }
    .info_downtime_i{
      position: absolute;
      top: 30px;
    }
    .info_downtime_text{
      position: absolute;
      top: 42px;
    }
    .info_danger_i{
      position: absolute;
      top: 60px;
    }
    .info_danger_text{
      position: absolute;
      top: 72px;
    }
    .info_outwork_i{
      position: absolute;
      top: 90px;
    }
    .info_outwork_text{
      position: absolute;
      top: 102px;
    }
    .info_worktime_i{
      position: absolute;
      top: 120px;
    }
    .info_worktime_text{
      position: absolute;
      top: 132px;
    }
/* info main big */
    .info_oee{
      position: absolute;
      left: 6px;
      top: 6px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 36px;
      line-height: 44px;
      letter-spacing: 0.05em;
      color: #721C24;
    }
    .info_multyplication{
      position: absolute;
      left: 8px;
      top: 44px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 10px;
      line-height: 12px;
      letter-spacing: 0.05em;
      color: #9098AF;
    }
    .info_multy_proc{
      position: absolute;
      left: 8px;
      top: 56px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 10px;
      line-height: 12px;
      color: #9098AF;
    }
    .info_target{
      position: absolute;
      right: 6px;
      top: 96px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 10px;
      line-height: 12px;
      text-align: right;
      color: #9098AF;
    }
    .info_base{
      position: absolute;
      right: 6px;
      top: 108px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 10px;
      line-height: 12px;
      text-align: right;
      color: #9098AF;
    }
    .info_proc_num{
      position: absolute;
      right: 12px;
      top: 120px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 36px;
      line-height: 44px;
      text-align: right;
      color: #721C24;
    }
/* aviability perfomanse quality */
    .info_aviab{
      position: absolute;
      left: 6px;
      top: 6px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 10px;
      line-height: 12px;
      color: #721C24;
    }
    .aviab_proc_numb{
      position: absolute;
      left: 6px;
      top: 20px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;
      color: #721C24;
    }
    .info_perfom{
      position: absolute;
      left: 6px;
      top: 6px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 10px;
      line-height: 12px;
      color: #856404;
    }
    .aviab_perfom_numb{
      position: absolute;
      left: 6px;
      top: 20px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;
      color: #856404;
    }
    .info_qual{
      position: absolute;
      left: 7px;
      top: 6px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 10px;
      line-height: 12px;
      color: #155724;
    }
    .aviab_quality_numb{
       position: absolute;
      left: 6px;
      top: 20px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;
      color:  #155724;
    }


</style>