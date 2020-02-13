<template>
  <div class="register">
    <div class="banner">
    </div>
    <div class="mainContent">
      <div class="container text-center">
        <h1>Register your account with <span class="color-red">Redux Flyff</span></h1>
        <p>
          Jump into Redux Flyff with an account! just fill out the form below<br> and you'll be on your way to playing.
        </p>
      </div>

      <div class="container mt-md-5">

        <div class="row justify-content-center">
          <div class="col-md-6 p-0">
            <div class="alert alert-primary text-center" role="alert">
              <i class="fas fa-exclamation-circle"></i><br>

              You are registering for a <b>website account</b>. Once you have created this account, you can then login here to create your <b>in-game accounts</b>. All of your in-game accounts are stored under 1 website account so please do not fill in random information.
            </div>
          </div>
        </div>

        <div class="row justify-content-center">
          <div class="col-md-6 form-container">
            <form>
                <div class="form-group row">
                  <label for="inputUser" class="col-sm-2 col-form-label">Username:</label>
                  <div class="col-sm-10">
                    <input type="text" class="form-control" id="inputUser" placeholder="Username">
                  </div>
                </div>
                <div class="form-group row">
                  <label for="inputEmail" class="col-sm-2 col-form-label">Email:</label>
                  <div class="col-sm-10">
                    <input type="email" class="form-control" id="inputEmail" placeholder="Email">
                  </div>
                </div>
                <div class="form-group row">
                  <label for="inputPassword" class="col-sm-2 col-form-label">Password:</label>
                  <div class="col-sm-10">
                    <input type="password" class="form-control" id="inputPassword" placeholder="Password">
                  </div>
                </div>
                <div class="form-group row align-items-center">
                <label for="inputPassword" class="col-sm-2 col-form-label">Confirm:</label>
                <div class="col-sm-10">
                  <input type="password" class="form-control" id="inputPassword" placeholder="Confirm Password">
                </div>
                </div>
              <div class="text-center">
                <button type="submit" class="btn btn-primary">Register Account</button>
              </div>
            </form>

          </div>
        </div>
      </div>

    </div>
  </div>
</template>
<style lang="scss" scoped>

  .alert {
    b {
    }
    .fas {
      font-size: 2rem;
      margin: 0 0 1rem 0;
      opacity: 0.8;
    }
  }


  .form-container {
    border: 1px solid rgba(0, 0, 0, 0.1);
    border-radius: 5px;
    padding: 2rem;

    .form-control {
      background-color: #f6f6f6;

      &:focus {
        border-color: rgb(217, 43, 46);
        box-shadow: 0 0 0 0.2rem rgba(217, 43, 46, .25);
      }
    }
  }

</style>