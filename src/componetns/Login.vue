<template>
    <div class="loginform"  >
                    <h4 class="m-0">Login to account</h4>
                   
                    <input type="text" class="myinp" placeholder="Your username">
                    <p class="msg text-danger mt-1"></p>
                    <input type="password" class="myinp" placeholder="Your password">
                    <p class="msg text-danger mt-1"></p>
                    <input type="submit" class="mybtn loginbtn" value="Login">
                    <p class="msg text-danger mt-1 m-0 text-center"></p>
               </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
 .loginform {
          
          
               box-shadow: 0px 0px 10px rgba(0,0,0,0.75);
               border-radius: 3px;
               padding: 60px 40px;
               width: 400px;
               
          }
          h4{
              color:azure;
          }
          .myinp{
               border: 1px solid #e3e3e3;
               outline: none;
               padding: 8px 10px;
               font-size: 14px;
               width: 100%;
               display: block;
               margin-top: 15px;
          }
          .myinp:focus-visible{
               border: 1px solid black;
          }
          .mybtn{
               background-image: linear-gradient(to right, rgb(236, 72, 153), rgb(239, 68, 68), rgb(234, 179, 8));
               color: white;
               outline: none;
               border: none;
               width: 100%;
               padding: 8px 10px;
          }
          .mybtn:hover{
               box-shadow: 3px 3px 10px rgba(0,0,0,0.5);
          }

</style>