<template>
<section class="container-fluid min-vh-100 py-5 my-5">
      <div class="container py-5 my-5">
        <div class="row justify-content-start text-black">
        </div>
        <div class="row justify-content-center">
          <div class="col-md-4">
            <h3>Free yourself from financial burden</h3>
            <div class="card">
                <img src="https://i.postimg.cc/MGTRSKnd/petr-sevcovic-e12w-QLAj-Qi0-unsplash.jpg" class="card-img-top" alt="Card image">
                <div class="card-body">
                  <h5 class="card-title">Our happy client</h5>
                  <p class="card-text">After years of financial struggle, Alex finally felt the weight lift from his shoulders as his debt was cleared. 
                    The overwhelming relief and newfound freedom brought tears to his eyes, 
                    marking the start of a fresh, unburdened chapter in his life. He could now breathe easy and dream big.</p>
                  <a href="#" class="btn btn-primary">see more</a>
                </div>
            </div>
          </div>
          <div class="col-md-6">
            <h2 class="form">Assessment Form</h2>
                    <form>
                        <div class="d-flex">
                            <div class="col-md-6">
                                <label for="firstName" class="form-label">First Name</label>
                                <input type="text" class="form-control" id="firstName" required>
                            </div>
                            <div class="col-md-6">
                                <label for="lastName" class="form-label">Last Name</label>
                                <input type="text" class="form-control" id="lastName" required>
                            </div>
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" required>
                        </div>
                        <div class="mb-3">
                            <label for="idNumber" class="form-label">ID Number</label>
                            <input type="text" class="form-control" id="idNumber" required>
                        </div>
                        <div class="mb-3">
                            <label for="phoneNumber" class="form-label">Phone Number</label>
                            <input type="tel" class="form-control" id="phoneNumber" required>
                        </div>
                        <div class="mb-3">
                            <label for="income" class="form-label">Gross income</label>
                            <input type="text" class="form-control" id="gincome" required>
                        </div>
                        <div class="mb-3">
                            <label for="employer" class="form-label">Employer</label>
                            <input type="text" class="form-control" id="employer" required>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </form>
          </div>
        </div>
    </div>
</section>


  </template>

  <style scoped>

  .container-fluid{
    background:linear-gradient(95deg,#cacae7,hsla(240, 0%, 47%, 0.773), hsla(240, 0%, 47%, 0.773), #cacae7);
  }

  .container{
    background-color: white;
  }

</style>

  