<template>
<div class="container-fluid">

 <div class="bound">
 <app-login></app-login>
 
 </div>
 </div>
</template>

<script>
import Login from './componetns/Login.vue';
export default{
  components :{
  'app-login':Login
  }
}
</script>

<style>
*{
  margin: 0px;
  padding: 0px;
}
.container-fluid{
  width: 100vw;
  height: 100vh;
  background-image: url(./assets/car-connectivity.jpg);
  background-size: cover;
  display: flex;
  justify-content: center;
  flex-direction: column;
}
.bound{
  display: flex;
  align-items: center;
  justify-content: center;
}



</style>
