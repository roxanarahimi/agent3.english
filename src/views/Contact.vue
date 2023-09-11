<template>
<div>
    <div class="basic-2">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="text-container">
                      <h4 class="text-center">Contact Us</h4>
                      <p class="p-large" style="	text-align: justify;">Address: 2nd floor, no 5, Farshadi st, Corner of Khandan ally, Shian, Tehran, Iran </p>

                      <p class="p-large  pt-2" >Email:
                      <span id="email" @click="copyMail()"> webagent.ir@gmail.com</span>
                      <span id="email-coppy-alert">email was copied!</span>
                      </p>
                      
                      <p class="p-large  pt-1" >Phone:
                      <span id="tel" @click="copyTel()">09032313681</span>
                      <span id="tel-coppy-alert">phone was copied!</span>
                      </p>
                    
                      
                      <div class="social-links mt-3">
                      
                      <a style="color: #ff5574" href="tel:09032313681" ><i class="bi bi-telephone-fill"></i></a>
                      <a target="_blank" style="color: #0077b5" href="https://linkedin.com/in/roxanarahimi"><i class="bi bi-linkedin"></i></a>
                      <a target="_blank" style="color: #25D366" href="https://api.whatsapp.com/send?phone=989032313681"><i class="bi bi-whatsapp"></i></a>
                      <a target="_blank" style="color: #229ED9" href="https://t.me/webagent_ir"><i class="bi bi-telegram"></i></a>
                      <a target="_blank" style="color: #bc2a8d" href="https://www.instagram.com/webagent.ir"><i class="bi bi-instagram"></i></a>
                      
                      </div>
                    </div>
                </div>
            </div>
        </div> 
    </div>
  </div>
  
  
</template>

<script>
export default {

methods:{
copyMail(){
//  /* Get the text field */
//   var copyText = document.getElementById("myInput");

//   /* Select the text field */
//   copyText.select();
//   copyText.setSelectionRange(0, 99999); /* For mobile devices */

//    /* Copy the text inside the text field */
//   navigator.clipboard.writeText(copyText.value);

//   /* Alert the copied text */
//   alert("Copied the text: " + copyText.value);

navigator.clipboard.writeText('webagent.ir@gmail.com');
  // alert("ایمیل کپی شد");
  setTimeout(()=>{
    document.getElementById('email-coppy-alert').style.opacity = '1';
  },300);
  
  setTimeout(()=>{
    document.getElementById('email-coppy-alert').style.opacity = '0';
  },2500);
},
copyTel(){

navigator.clipboard.writeText('09032313681');
  setTimeout(()=>{
    document.getElementById('tel-coppy-alert').style.opacity = '1';
  },300);
  
  setTimeout(()=>{
    document.getElementById('tel-coppy-alert').style.opacity = '0';
  },2500);
}
}

};
</script>

<style>

#email-coppy-alert{
opacity: 0;
transition: 0.2s ease;
font-size: 13px;
background: rgb(53, 53, 53) ;
color: whitesmoke;
position: relative;
top:20px;
right: -200px;
border-radius: 3px;
padding: 3px 10px;
}
#tel-coppy-alert{
opacity: 0;
transition: 0.2s ease;
font-size: 13px;
background: rgb(53, 53, 53) ;
color: whitesmoke;
position: relative;
top:20px;
right: -100px;
border-radius: 3px;
padding: 3px 10px;
}
@media (max-width: 432px) {
#email-coppy-alert{
position: absolute;
top: 350px;
right: 90px;
display: inline-block;

}
#tel-coppy-alert{
position: absolute;
top: 400px;
right: 90px;
display: inline-block;

} 
}


.social-links{

direction: ltr;
/* text-align: left !important; */
margin-top: 10px;

}
.social-links a{ 
font-size: 20px;
margin-right: 4px;
margin-left: 4px;
background: whitesmoke;
border-radius: 50%;
display: inline-block;
width: 30px !important;
height: 30px !important;
text-align: center;
padding-top: 4px;
cursor: pointer;
}
#email, #tel{
cursor: pointer;
}
</style>