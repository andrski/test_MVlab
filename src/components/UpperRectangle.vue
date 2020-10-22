<template>
    <div class="up_rect">
        <div class="left_text_wrap">
            <p class="left_text">Цех ковки тяжелых конструкций и древесины / Станок 1 </p>
        </div>
        <div class="up_rect_buttons">
            <button class="up_btn_hour">час</button>
            <button class="up_btn_workshift">смена</button>
            <button class="up_btn_day">день</button>
            <button class="up_btn_week">неделя</button>
            <button class="up_btn_month">месяц</button>
        </div>
        
        <button class="up_back_arrow">
            <img src="../assets/arrow_back_ios_24px.png" alt="back arrow" class="back_ar">
        </button>
        <button class="up_forward_arrow">
            <img src="../assets/arrow_forward_ios_24px.png" alt="forward arrow" class="forward_ar">
        </button>
        <div class="up_rect_icon">
            <img src="../assets/strange_icon.png" alt="strange icon" />
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .up_rect{
        position: relative;
        width: 1794px;
        height: 48px;
        background: #F9FAFC;
    }
    .left_text_wrap{
        position: absolute;
        left: 24px;
        top: 0px;
        width: 864px;
        height: 48px;
    }
    .left_text{
        color: #4A627A;
        width: 100%;
        margin-top: 12px;
    }
    .up_rect_buttons{
        position: absolute;
        left: 1088px;
        top: 12px;
    }
    .up_btn_hour, .up_btn_workshift, .up_btn_day, .up_btn_week, .up_btn_month{
        color: #7B879D;
        background: #EAEEF7;
        border-radius: 4px;
    }
    /* change buttons on events */
    .up_btn_day:hover, .up_btn_day:active{
        color: #FF7167;
    }
    .up_btn_hour:hover, .up_btn_hour:active{
            color: #FF7167;
        }
    .up_btn_workshift:hover, .up_btn_workshift:active{
        color: #FF7167;
    }
    .up_btn_week:hover, .up_btn_week:active{
        color: #FF7167;
    }
    .up_btn_month:hover, .up_btn_month:active{
        color: #FF7167;
    }
    /* back, forward, strange icon */
    .up_back_arrow{
        position: absolute;
        left: 1669.3px;
        top: 11.63px;
        width: 14,59px;
        height: 24,75px;
        border: #F9FAFC;
        background: #F9FAFC;
    }
    .up_back_arrow:active{
        background: #EAEEF7;
    }
    .up_forward_arrow{
        position: absolute;
        left: 1706.11px;
        top: 11.63px;
        width: 14,59px;
        height: 24,75px;
        border: #F9FAFC;
        background: #F9FAFC;
    }
    .up_forward_arrow:active{
        background: #EAEEF7;
    }
    .up_rect_icon{
        position: absolute;
        left: 1754.5px;
        top: 10.25px;
        width: 26.25px;
        height: 26.25px;
    }
</style>