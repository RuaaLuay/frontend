<template>
  <div>
    <div id="preloader">
      <div class="loader"></div>
    </div>
    <!-- preloader area end -->
    <!-- login area start -->
    <div class="login-area" style="padding-top: 20px">
      <div class="container" style="margin-bottom: 0px">
        <div class="login-box ptb--100">
          <form>
            <div class="login-form-head" style="text-align: center !important">
              <h4 class="sign" style="
                letter-spacing: 0;
                text-transform: uppercase;
                font-weight: 600;
                margin-bottom: 7px;
              ">
                Sign up
              </h4>
              <p class="hello">Hello there, Sign up and Join with Us</p>
            </div>
            <div class="login-form-body">
              <div class="form-gp">
                <!-- <label for="exampleInputName1">Full Name</label> -->
                <label class="fromto">Your Name:</label> <br>
                <input class="form-control" type="text" id="exampleInputName1" placeholder="Full Name" />
                <!-- <i class="ti-user"></i> -->
              </div>
              <div class="form-gp">
                <!-- <label for="exampleInputEmail1">Email address</label> -->
                <label class="fromto">Your Email:</label> <br>
                <input class="form-control" type="email" id="exampleInputEmail1" placeholder="Email address" />
                <!-- <i class="ti-email"></i> -->
              </div>
              <div class="form-gp">
                <!-- <label for="exampleInputPassword1">Password</label> -->
                <label class="fromto">Creat Password:</label> <br>
                <input class="form-control" type="password" id="exampleInputPassword1" placeholder="Password" />
                <!-- <i class="ti-lock"></i> -->
              </div>
              <div class="form-gp">
                <!-- <label for="exampleInputPassword2">Confirm Password</label> -->
                <label class="fromto">Confirm Your Password:</label> <br>
                <input class="form-control" type="password" id="exampleInputPassword2" placeholder="Confirm Password" />
                <!-- <i class="ti-lock"></i> -->
              </div>
              <div class="submit-btn-area">
                <button id="form_submit" type="submit">
                  Submit <i class="arrow-right"></i>
                </button>
                <div class="login-other row mt-4">
                  <div class="col-6 facebook">
                    <a class="fb-login" href="#">Sign up with
                      <span style="
                        font-weight: bold;
                        font-size: 15px;
                        text-transform: lowercase;
                      ">
                        f</span></a>
                  </div>
                  <div class="col-6 google">
                    <a class="google-login" href="#">Sign up with
                      <span style="font-weight: bold; font-size: 15px">
                        G</span></a>
                  </div>
                </div>
              </div>
              <div class="form-footer text-center mt-5">
                <p class="text-muted">
                  Don't have an account?
                  <router-link to="/Login"><a>Sign in</a> </router-link>
                </p>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "registerScreen",
};
</script>
<style>
.form-gp input::placeholder {
  font-weight: bold;
  opacity: 0.5;
  color: rgb(89, 88, 88);
}

.arrow-right {
  border: solid black;
  border-width: 0 3px 3px 0;
  display: inline-block;
  padding: 3px;
  transform: rotate(-45deg);
  -webkit-transform: rotate(-45deg);
}

.f2 a {
  color: #fff;
  font-family: 'Poppins', sans-serif;
  text-decoration: none;
}
</style>
