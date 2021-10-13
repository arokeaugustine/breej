<template>
    <div class="container py-5 columnsContainer" >
  
    <!-- text to appear on screen bigger than large -->
         <div class="d-none d-lg-flex">

        <div class="columnz">
                <img src="../assets/images/Vector.png" alt="" class="cardImg" >
                <h2 class="text-left">Get a tutor</h2>
                <p class="text-left">The breej offers you a tutor in <br>
                seconds. Sign up, make a request <br>
                and get connected.</p>
            </div>

        <div class="columnz">
                <img src="../assets/images/Vector(1).png" alt="" class="cardImg">
                <h2 class="text-left">Shop online</h2>
                <p class="text-left">All your needs available in one app <br>
                order anything on our online store.</p>
            </div>
          <div class="columnz">
                <img src="../assets/images/Vector(2).png" alt="" class="cardImg">
                <h2 class="text-left">Sell Online</h2>
                <p class="text-left">User-friendly system with excellence <br>
                speed and reliability.</p>
            </div>

    </div> 

      <!-- code for large and lower screens -->
        <div class="d-lg-none text-center">
             <div class="columnz">
                <img src="../assets/images/Vector.png" alt="" class="cardImg" >
                <h2 class="">Get a tutor</h2>
                <p class="">The breej offers you a tutor in <br>
                seconds. Sign up, make a request <br>
                and get connected.</p>
            </div>

        <div class="columnz text-center">
                <img src="../assets/images/Vector(1).png" alt="" class="cardImg">
                <h2 class="">Shop online</h2>
                <p class="">All your needs available in one app <br>
                order anything on our online store.</p>
            </div>
          <div class="columnz text-center">
                <img src="../assets/images/Vector(2).png" alt="" class="cardImg">
                <h2 class="">Sell Online</h2>
                <p class="">User-friendly system with excellence <br>
                speed and reliability.</p>
            </div>
        </div>
    </div>
</template>

<style>
.columnsContainer{
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
}

.columnz{
    /* border: 2px solid rebeccapurple; */
    margin: 15px;
}
.cardImg{
    padding-top: 10px;
    margin-top: 20px;
} 
.columnz h2{
    font-family: Raleway;
    font-style: normal;
    font-weight: bold;
    font-size: 36px;
    line-height: 42px;

    color: #000000;
}
.columnz p{
    font-family: Raleway;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;

    color: rgba(0, 0, 0, 0.8);
}

@media screen and (max-width: 810px){
    #columns #column{
        flex-basis: 40%;
    }
}
</style>





     <!-- <div class="row">
            <div class="col-md-6 col-lg-4 cardi">
                <img src="../assets/images/Vector.png" alt="" class="mb-3 text-left cardImg" >
                <h2 class="text-left">Get a tutor</h2>
                <p class="text-left">The breej offers you a tutor in <br>
                seconds. Sign up, make a request <br>
                and get connected.</p>
            </div>
            <div class="col-md-6 col-lg-4 cardi">
                <img src="../assets/images/Vector(1).png" alt="" class="cardImg">
                <h2 class="text-left">Shop online</h2>
                <p class="text-left">All your needs available in one app <br>
                order anything on our online store.</p>
            </div>
            <div class="col-md-6 col-lg-4 cardi" id="lastColumn">
                <img src="../assets/images/Vector(2).png" alt="" class="cardImg">
                <h2 class="text-left">Sell Online</h2>
                <p class="text-left">User-friendly system with excellence <br>
                speed and reliability.</p>
            </div>
        </div>
     -->