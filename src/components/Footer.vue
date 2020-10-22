<template>
    <footer class="footer">
        <div class="left_arrow">
            <img src="../assets/keyboard_arrow_down_24px.png" alt="left arrow" class="img_left_ar">
        </div>
        <div class="down_rectangle">
            <p class="down_rect_info">Все устройства в сети</p>
        </div>
        <div class="right_arrow">
            <img src="../assets/keyboard_arrow_down_24px.png" alt="" class="img_right_ar">
        </div>
    </footer>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .footer{    
        display: flex;
    }
    .img_right_ar .img_left_ar{
        height: 7.41;
        width: 12;
    }
    .left_arrow{
        position: absolute;
        left: 18px;
        /* top: 8px; */
    }
    .right_arrow{
        position: absolute;
        left: 1770px;
        /* top: 8px; */
    }

    .down_rectangle{
        width: 1800px;
        height: 24px;     
        background: #D4EDDA;
        text-align: center;
    }
    
</style>