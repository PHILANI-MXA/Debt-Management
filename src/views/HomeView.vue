<template>
<div class="container-fluid py-5 my-5 min-vh-100">
<div class="container py-5 my-5 min-vh-100">
  <h2 class="text-strong fw-bold ">Loan IZ</h2>
  <div class="row align-items-start">
    <div class="col-md-7">
      <div class="card align-items-start py-3 my-4">
        <div class="card-body h-30">
          <h5 class="card-title">Debt Management</h5>
          <h6 class="card-subtitle mb-2 text-muted">We offer debt management services</h6>
          <p class="card-text">Debt management refers to strategies and services designed to help individuals and organizations handle and repay
            their debts in an efficient and manageable manner.
            The primary goal of debt management is to reduce the financial burden of debt, improve credit scores, and prevent default or bankruptcy.
          </p>
        </div>
      </div>
    </div>
    <div class="col-md-7 text-primary">
      <div class="card align-items-start py-3 my-4" >
        <div class="card-body h-60" style="d-flex;">
          <h5 class="card-title">Personal Loan </h5>
          <h6 class="card-subtitle mb-2 text-muted">We offer Loan Consolidation services</h6>
          <p class="card-text">Personal loan consolidation is the process of combining multiple personal loans
            or other forms of debt into a single loan with one monthly payment.
            This can simplify your financial life, potentially lower your interest rates, and reduce your monthly payments.
          </p>
        </div>
      </div>
    </div>
    <div class="col-md-7 text-primary bg-transparent py-3 my-4">
      <div class="card align-items-start py-5" >
        <div class="card-body h-60" style="d-flex;">
          <h5 class="card-title">Debt Consolidation Loan</h5>
          <h6 class="card-subtitle mb-2 text-muted">We offer Loan Consolidation services</h6>
          <p class="card-text">Debt consolidation is a financial strategy that combines multiple debts into a single loan, 
            often with a lower interest rate and a more manageable monthly payment.
          </p>
        </div>
      </div>
    </div>
    <div class="row">
      <button type="button" class="btn btn-primary btn-lg mt-3" id="button">
        <router-link class="text-decoration-none text-black" to="/contact">check if you qualify?</router-link>
        
      </button>
    </div>
  </div>
  <div class="row align-items-center">
    <div class="col">
      
    </div>
    <div class="col">
      
    </div>
    <div class="col">
      
    </div>
  </div>
  <div class="row align-items-end">
    <div class="col">
      
    </div>
    <div class="col">
      
    </div>
    <div class="col">
      
    </div>
  </div>
  <section class="container py-5 my-5 min-vh-100 border border-dark overflow-hidden" style="background-color: #FFFFFF">
    <section class=" min-vh-100 " style="background-color: #FFFFFF">
      <div class="container border bordr-dark min-vh-100 py-5 my-5">
        <div class="row justify-content-start text-black">
        </div>
        <div class="row justify-content-center">
          <div class="col-md-4">
            <div class="card">
                <img src="https://i.postimg.cc/MGTRSKnd/petr-sevcovic-e12w-QLAj-Qi0-unsplash.jpg" class="card-img-top" alt="Card image">
                <div class="card-body">
                  <p>Our happy client</p>
                  <button>Read more</button>

                </div>
            </div>
          </div>
          <div class="col-md-6 min-vh-100 border border-black">
            <h2 class="bg-white strong py-5 my-5">ABOUT US</h2>
            <p>Welcome to LoanEase – your reliable source for personal loan solutions designed to meet your unique financial needs.</p>
            <h5>WHO WE ARE</h5>
            <p>At LoanEase, we are dedicated to helping individuals achieve their financial goals through flexible and accessible personal loan options.
               We also specialize in providing tailored financial solutions to help you manage your debt and achieve your financial goals. Our team of experienced financial 
              experts is committed to providing you with the best loan products and services to support your personal and financial aspirations. </P>
            <h5 class="strong">OUR MISSION</h5>
            <p>Our mission is to empower you with the financial resources you need to seize opportunities, overcome challenges, and make your dreams a reality. 
              We strive to offer straightforward and transparent personal loan solutions that simplify the borrowing process and provide peace of mind. </P>
          </div>
        </div>
    </div>
    <div class="container min-vh-100 py-5 my-5">
      <div>
        <!-- <h3>Our Services</h3> -->
      </div>
      <div class="row justify-content-start text-black">
      </div>
      <div class="row justify-content-center">
        
        <div class="col-md-6 min-vh-100 border border-black">
          <h2 class="bg-white strong py-5 my-5">OUR SERVICES</h2>
          <p>Welcome to LoanEase – your reliable source for personal loan solutions designed to meet your unique financial needs.</p>
          <h5>WHO WE ARE</h5>
          <p>At LoanEase, we are dedicated to helping individuals achieve their financial goals through flexible and accessible personal loan options.
             We also specialize in providing tailored financial solutions to help you manage your debt and achieve your financial goals. Our team of experienced financial 
            experts is committed to providing you with the best loan products and services to support your personal and financial aspirations. </P>
          <h5 class="strong">OUR MISSION</h5>
          <p>Our mission is to empower you with the financial resources you need to seize opportunities, overcome challenges, and make your dreams a reality. 
            We strive to offer straightforward and transparent personal loan solutions that simplify the borrowing process and provide peace of mind. </P>
        </div>
      </div>
  </div>
</section>

  </section>
</div>
</div>

</template>

<style scoped>
/* import perfect font*/

. {
  background-color: #778899;
}

  .container-fluid{
    background-color:white;
    background-image: url(https://i.postimg.cc/65JH20g4/krakenimages-376-KN-ISpl-E-unsplash.jpg);
    background-repeat: no-repeat;
    background-attachment: scroll, center;
    -webkit-background-size: cover, center;
    -moz-background-size: cover;
    background-size: cover;
    -o-background-size: cover;
    background-attachment: fixed;
    overflow:scroll;
    min-height: 100%;
  }

  .card{
    min-height: 200px;
    /*background-color: transparent;1*/
    color: black;
  }

  #button{
    width:200px;
    height:80px;
    background-color: #91aa9d;
  }

</style>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
