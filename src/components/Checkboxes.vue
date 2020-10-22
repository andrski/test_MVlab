<template>
    <div class="checkboxes">
        <div class="checkb_wraper">
        <label class="label_checkb"><span>A</span>
            <input class="inp_checkb" type="checkbox" name="a" value=""> 
             </label>
        <label class="label_checkb"><span>P</span>
            <input class="inp_checkb" type="checkbox" name="p" value=""> 
             </label>
        <label class="label_checkb"><span>Q</span>
            <input class="inp_checkb" type="checkbox" name="q" value=""> 
            </label>
        <label class="label_checkb"><span>OEE</span>
            <input class="inp_checkb" type="checkbox" name="oee" value=""> 
            </label>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .checkboxes{
        position: absolute;
        left: 813px;
        top: 277px;

        display: flex;
        flex-direction: row;
        justify-content: space-between;
        width: 175px;
        height: 24px;
    }
   
    .inp_checkb{
        width: 10px;
        height: 10px;
        background:#C4C4C4;
        margin-bottom: 4px;
        border-radius: 50%;
        vertical-align: middle;
       
        -webkit-appearance: none;
        outline: none;
        cursor: pointer;
    }
    .label_checkb{
        margin-right: 12px;
    }
</style>
