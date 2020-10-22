<template>
    <header class="header">
       <div class="wraper">

                 <div class="logo">
                    <a href="/" class="header_logo_link">
                        <img src="../assets/logo_MVLAB.svg" alt="some" class="logo_img">
                    </a> 
                </div>

            <nav class="nav">
                <ul class="header_list">
                    <li class="header_item">
                        <a href="/" class="header_link">Home</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">OEE</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">VIBRO</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">PROFILER</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">REPAIRS</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">RECORDER</a>
                    </li>
                </ul>
            </nav>

        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style  scoped>
   .header{
        background: #3F51B5;
        left: 0;
        top: 0;
        width: 1920px;
        height: 48px;
  }
  .wraper{
      display: flex;
  }
  .logo{
      background: whitesmoke;
      margin-top: 6px;
      margin-left: 12px;
      width: 95px;
  }
 
   .header_list{
      display:flex;
      flex-wrap: nowrap;
      align-items: flex-start;
      justify-content: space-between;
      width: 574px;
   }
   
  .nav{
      position: absolute;
      margin-top: 14px;
      margin-left: 156px;
  }
  .header_link{
      color: #B0BEC5;
      font-family: Montserrat;
      font-style: normal;
      font-weight: 500;
      font-size: 16px;
      line-height: 20px;
  }
  .header_link:hover, .header_link:focus, .header_link:active{
    color: #FFFFFF;
}
</style>