 <template>
  <div>
  <div class="mx-auto text-center mt-5 pt-5">
   <h1>404</h1>
   <h6> This page dose not exist</h6>
   <div class="navbar d-flex justify-content-center py-2">
      <router-link class="btn btn-solid-sm m-1" to="/">Home</router-link>
   <a class="btn btn-solid-sm m-1" @click="$router.go(-1)">Back</a>
   </div>

  </div>
  
  </div>
 </template>
 
 <script>
 export default {
 

 
 }
 </script>
 
 <style scoped>
 h1{
 font-size: 100px;
 line-height: 100px;
 text-align: center !important;
 color: #ff5574;
 }
 h6{
  color: #ffc107;
 }
.navbar{
background: transparent;
}
 </style>