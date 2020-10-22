<template>
    <div class="left_rectangle">
            <div class="left_rect_wraper">
                <div class="online">
                        <button class="btn_online">
                            <p class="p_wrap">
                                <img src="../assets/Vect_online.svg" alt="screen" class="" />
                                <img src="../assets/Vect_vert.svg" alt="vert" class="" />
                                <img src="../assets/Vect_horiz.svg" alt="horiz" class="" />
                            </p>
                        <p class="p_text_online">Online</p> 
                        </button>
                </div>

                <div class="report">
                    <button class="btn_report">
                            
                                <img src="../assets/Vect_report.svg" alt="screen" class="rep" />
                                <img src="../assets/Vect_rep_line1.svg" alt="vert" class="rep_line1" />
                                <img src="../assets/Vect_rep_line2.svg" alt="horiz" class="rep_line2" />
                                <img src="../assets/Vect_rep_line3.svg" alt="horiz" class="rep_line3" />
                           
                            <p class="p_text_rep">Report</p> 
                        </button>
                </div>

                <div class="settings">
                    <button class="btn_settings">
                            
                         <img src="../assets/Vect_settings.svg" alt="settings" class="set_img" />
                                                           
                         <p class="p_text_set">Settings</p> 
                        </button>
                </div>
            </div>
        </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .left_rectangle{
        width: 120px;
        height: 902px;       
        background: #EDF2F8;
    }
    .online{
        position: absolute;
        top: 48px;
    }
    .report{
         position: absolute;
        top: 127px;
    }
    .settings{
        position: absolute;
        top: 206px;
    }
    
    .btn_online{
        width: 120px;
        height: 79px;
        background: #EAEEF7;
        border:  #EAEEF7;
    }
    .p_wrap{
        display: flex;
        flex-direction: column;
        position: absolute;
        top: 10px;
        left: 35px;
    }
    .p_text_online{
        position: absolute;
        top: 50px;
        left: 30px;
    }
    .btn_online{
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    /* report */
    .btn_report{
        width: 120px;
        height: 79px;
        background: #EAEEF7;
        border:  #EAEEF7;
    }
    .p_text_rep{
        position: absolute;
        left: 30px;
        top: 51px;
    }
    .rep{
        position: absolute;
        left: 40px;
        top: 14.37px
    }
    .rep_line1{
        position: absolute;
        left: 45px;
        top: 27.44px
    }
     .rep_line2{
        position: absolute;
        left: 45px;
        top: 33.38px
    }
     .rep_line3{
        position: absolute;
        left: 45px;
        top: 39.31px
    }
    /* setting */
.btn_settings{
        width: 120px;
        height: 79px;
        background: #EAEEF7;
        border:  #EAEEF7;
    }
    .set_img{
        position: absolute;
        left: 35px;
        top: 15px;
    }
    .p_text_set{
        position: absolute;
        left: 28px;
        top: 50px;
    }

    .btn_settings:active,  .btn_settings:hover{
        color: #FF7167;
    }
    
    .btn_online:active, .btn_online:hover{
        color: #FF7167;
    }
    .btn_report:active, .btn_report:hover{
        color: #FF7167;
    }

</style>