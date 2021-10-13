<template>
  <header>
    <div id="nav m-2">
      <b-navbar toggleable="lg">
        <b-navbar-brand href="#" id="logo">LOGO</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse" id="toggler"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav  class="ml-auto">
            <b-navbar-nav id="navbarContainer">
              <b-nav-item href="#" class="navLinks"
                ><a href="">About Us </a></b-nav-item
              >
              <b-nav-item href="#" class="navLinks"
                ><a href="">Contact Us</a></b-nav-item
              >
              <b-nav-form>
                <button class="loginBtn text-light">Login</button>
              </b-nav-form>
            </b-navbar-nav>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
   
  <div class="container">
    <div class="row">
      
        <div class="col-lg-6">
           <!-- text to appear on screen bigger than large -->
          <div class="d-none d-lg-block">
            <div class="pt-5" id="writeup">
          <div>
            <p>The new way to get connected</p>
            <h1>
              Online,<br />
              in-person <br> everywhere.
            </h1>
            <div class="d-flex" id="getStartedBtnHolder">
              <button id="getStartedBtn" class="">Get Started</button>
              <a href="#" class="ml-5 mt-2" id="downloadLink"
                >Download mobile app</a
              >
            </div>
          </div>
          </div>
        </div>

         <!-- code for large and lower screens -->
          <div class="d-lg-none">
    
          <img src="../assets/images/banner.png" alt="" class="img-fluid" />
          </div>
    </div>

    <div class="col-lg-6">

       <!-- text to appear on screen bigger than large -->
         <div class="d-none d-lg-block mt-5 pt-5">
           <img src="../assets/images/banner.png" alt="" class="img-fluid" />
        </div>

        <!-- code for large and lower screens -->
        <div class="d-lg-none ">
            <div class="pt-5" id="writeup">
          <div>
            <p class="text-center">The new way to get connected</p>
            <h1 class="text-center">
              Online,<br />
              in-person <br> everywhere.
            </h1>

            <div class="text-center mt-3">
              <button id="getStartedBtn" class="text-center">Get Started</button>
            </div>
            
              
            
          </div>
          </div>
        </div>

    </div>
  </div>
  </div>

  </header>
</template>



<style>
* {
  margin: 0;
  padding: 0;
}
header {
  top: 0;
  background: #ffffff;
  /* border: 2px solid red; */
}
#nav {
  /* border: 2px solid grey; */
  padding-top: 20px;
  padding-bottom: 50px;
}

#logo {
  margin-left: 50px;
  font-family: Poppins;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 54px;
  color: #3e4095;
  text-decoration: none;
}
.navLinks {
  /* border: 2px solid green; */
  padding-right: 50px;
  color: #3e4095;
  font-weight: 100px;
}
.navLinks a {
  text-decoration: none;
  font-family: Poppins;
  font-style: normal;
  font-weight: normal;
  font-size: 22.5px;
  line-height: 34px;
}

#toggler {
  color: #3e4095;
}
#nav-collapse {
  color: #3e4095;
}

#navbarContainer {
  margin-right: 150px;
  padding-left: 50px;
}

.nav-links ul {
  padding-right: 50px;
}

.loginBtn {
  border: none;
  background: #3e4095;
  border-radius: 5px;
  width: 112px;
  height: 35px;
  color: #ffffff;
}
#writeup {
  /* width: 550px; */
  /* border: 2px solid yellow; */
  order: 1;
}

#writeup p {
  padding-top: 50px;
  font-family: Raleway;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  color: #263238;
}
#writeup h1 {
  font-family: Raleway;
  font-style: normal;
  font-weight: 800;
  font-size: 72px;
  line-height: 85px;
}
#getStartedBtn {
  position: static;
  width: 175px;
  height: 53px;
  border: none;
  background: #3e4095;
  border-radius: 5px;
  color: #ffffff;
  font-family: Raleway;
  font-style: normal;
}
#downloadLink {
  text-decoration: none;
  font-family: Raleway;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 28px;
  color: #263238;
}
#banner {
  height: 627.36px;
  /* border: 2px solid cyan; */
  order: 2;
}

#banner img {
  position: absolute;
  width: 500px;
}

.groupHolder {
  display: flex;
  /* border: 2px solid red; */
  justify-content: space-between;
}

@media screen and (max-width: 810px) {
  .groupHolder {
    display: block;
  }
  #writeup {
    order: 2;
  }
  #banner {
    order: 1;
    /* border: 2px solid black; */
    padding-left: 80px;
  }
  #writeup p {
    font-size: 24px;
    text-align: center;
  }
  #writeup h1 {
    font-style: normal;
    font-weight: 800;
    font-size: 64px;
    line-height: 75px;
    text-align: center;
  }
  #banner img {
    width: 400.16px;
    padding-top: 30px;
    /* padding-left: 300px; */
    /* border: 2px solid peru; */
  }
  #getStartedBtnHolder {
    /* border: 2px solid black; */
    /* justify-content: center; */
    padding-left: 200px;
    width: 500px;
  }
  #getStartedBtn {
    width: 125px;
    height: 53px;
    margin: 0;
  }
  #downloadLink {
    display: none;
  }
}
@media screen and (max-width: 710px) {
  #banner {
    order: 1;
    /* border: 2px solid black; */
    padding-left: 0px;
  }
  #banner img {
    width: 338px;
    height: 310.92px;
  }
  #writeup h1 {
    font-weight: 800;
    font-size: 42px;
    line-height: 49px;
    text-align: center;
  }
}
</style>