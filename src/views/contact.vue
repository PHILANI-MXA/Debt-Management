<template>

    <section class="container-fluid min-vh-100 py-5">    
    <div  class="col-md-3">
    </div>
    <div class="container vh-100 contact py-5 my-5 col-md-6">
      <h1 class="text-start fw-bold">Get in touch</h1>
      <div class="conbox">
        <form action="https://formspree.io/f/xpznrrpd">
          <div class="mt-3">
            <label for="Name">Name </label><input type="text" class="form-control" id="name" placeholder="Enter Your Name" name="name">
          </div> 
          <div class="mt-3">
            <label for="Surname">Surname </label><input type="text" class="form-control" id="text" placeholder="Enter Your Surname" name="surname">
          </div> 
          <div class="mt-3">
            <label for="contact">Contact </label><input type="tel" class="form-control" id="number" placeholder="Enter Your Phone Number" name="number">
          </div> 
          <div class="mt-3">
            <label for="Email">Email </label><input type="email" class="form-control" id="email" placeholder="Enter Your Email Address" name="email">
          </div> 
           <div class="form-check mt-3">
            <label class="form-check-label">
              <input class="form-check-input" type="checkbox" name="remember"> Remember me
            </label>
          </div>
          
      <!--     Textarea -->
          
           <div class=" mt-3">
            <label for="comment">Leave a message</label>
            <textarea class="form-control"  id="comment" name="text"></textarea>
          </div>
          <button type="button" class="btn btn-primary btn-lg mt-3" id="button">
            Submit
          </button>
        </form>         
      </div>  
    </div>
    <div  class="col-md-3">

    </div>
</section>
  </template>

  <style scoped>

  .container-fluid{
    background:white;
    
  }

  .contact{
    background-image: url(https://i.postimg.cc/Kjynz9jZ/julian-hochgesang-Dkn8-z-PIbwo-unsplash.jpg);
  }

  .conbox{
    background-color:black;
    color:white;
    font-size:22px;
    padding-top:10px;
    padding-bottom:20px;
    width:400px;
    margin-top:40px;
    height:460px;
    margin: auto;
    background-color: black;
    opacity:50%
  }
  #button{
    width:200px;
    height:50px;
    background-color: #91aa9d;
  }

  </style>
