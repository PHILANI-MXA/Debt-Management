<template>
    <div>
    <nav class="navbar navbar-expand">
      <div class="container-fluid">
        <a class="navbar-brand bg-white px-2 mx-3 "  to="/" href="#"><img src="https://i.postimg.cc/D0TpVDjq/favicon-32x32.png" alt="">LOAN EASE</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav m-auto">
            <li class="nav-item text-white">
             <router-link class="text-decoration-none text-black" to="/">Home</router-link>
            </li>
            
              <li class="nav-item">
              <router-link class="text-decoration-none text-black" to="/assessment">Assessment Page</router-link>
            </li>
            <li class="nav-item">
                <router-link class="text-decoration-none text-black" to="/contact">Contact Us</router-link>
               </li>
             <!-- <li class="nav-item">
                <router-link class="text-decoration-none text-black invisible" to="/loan">Personal/ Debt Consolidation Loan</router-link>
           </li>
            <li class="nav-item text-decoration-none">
               <router-link class="text-decoration-none text-black invisible" to="/about">About</router-link>
            </li>
            <li class="nav-item">
                <router-link class="text-decoration-none text-black invisible" to="/debt">Debt Management</router-link>
            </li>
           <li class="nav-item">
            <router-link class="text-decoration-none text-black invisible" to="/services">Services</router-link>
        </li>
              <li class="nav-item" >
              <router-link class="text-decoration-none text-black invisible" to="/admin">Admin</router-link>
            </li> -->
          </ul>
        </div>
      </div>
    </nav>
    </div>
    <router-view/>
    </template>
    
    <style scoped>
     @import url('https://fonts.googleapis.com/css?family=Raleway:400,700');
     @import url('https://fonts.googleapis.com/css2?family=STIX+Two+Math&display=swap');
    * {
        font-family: 'STIX Two Math', serif;
    }
    .nav-item{
    position: relative;
    padding: 20px;
    font-size: Medium;
    font-family: 'STIX Two Math', serif;

    }
    .navbar-brand{
      font-style: italic;

    }
    .btn{
      color: white;
      border-color: white;
    }
    nav {
    position:fixed;
    width: 100%;
    top: 0;
    background-color: #778899;
    z-index:50;

    }
    </style>