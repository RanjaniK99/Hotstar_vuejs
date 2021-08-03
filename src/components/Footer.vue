<template>
      
      <div class="ft container-fluid">
    <p class="color">In case of any query, email us at<a  href="#" class=" text-decoration-none ">  subscribe@hotstar.com</a></p>
    <div class="fw-bold">
       <router-link to="About"  class=" text-decoration-none  subcolor">About</router-link>&nbsp;
      <router-link to="https://www.hotstar.com/in/terms-of-use"  class=" text-decoration-none  subcolor">Terms Of Use</router-link>&nbsp;
      <a href="https://www.hotstar.com/in/privacy-policy"  class=" text-decoration-none subcolor"> Privacy Policy</a>&nbsp;
      <a href="https://help.hotstar.com/support/home"  class=" text-decoration-none subcolor">FAQ</a>&nbsp;
      <a href="https://help.hotstar.com/support/tickets/new"  class=" text-decoration-none subcolor" >Feedback</a>&nbsp;
      <a href="https://jobs.lever.co/hotstar"  class=" text-decoration-none subcolor"></a></div>
      <div class="row">
     <p class="col-lg-6 color" >© 2021 STAR. All Rights Reserved. HBO, Home Box Office and all related channel and programming logos are service 
     marks of, and all related programming visuals and elements are the property of, Home Box Office, Inc. All rights 
      reserved.</p>
      <div class="col-lg-2 color">
      <h4 class="  fs-6 ">Connect with us </h4>
            <a href="https://www.facebook.com"> <img src="../assets/fb.jpeg" alt="" width="40" height="40" class="rounded ms-2"></a>
            <a href="#"><img src="../assets/twitter.jpeg" alt="" width="40" height="40" class="rounded ms-2"></a></div>
      <div class="col-lg-4 color">
            <h4 class="fs-6 ">Disney+Hotstar App</h4>
            <a href="#"> <img src="../assets/gpay.png" alt="" width="150" height="40" class="rounded"></a> &nbsp;
            <a href="#" > <img src="../assets/appstores.png" alt="" width="150" height="40" class="rounded"></a>
   </div>
   </div>
  
   </div>
    
</template>

<script>
    export default {
       name:'footer', 
    }
</script>

<style>
.ft {
  height: fit-content;
}
.color {
  color: white;
}
.subcolor {
  color: white;
}
.subcolor:hover {
  color: blue;
}
</style>