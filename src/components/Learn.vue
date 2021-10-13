<template>
    <div id="learnContainer">
        <div class="container">
            <h3 class="text-center">Ready to learn smartly?</h3>
            <p class="lead text-center">
                Download The Breej App Now
            </p>
            <!-- btn for screen greater than large -->
            <div class="text-center d-none d-lg-block">
                <button class="text-center mx-2"><img src="../assets/images/Icon Google play.png" alt=""> </button> <button><img src="../assets/images/appstore.jpg" alt=""></button>
           </div>
           <!-- btn for screen for large and smaller sizes -->
            <div class="text-center d-lg-none ">
                <button class="text-center"><img src="../assets/images/Icon Google play.png" alt=""> </button> 
                <button class="mt-2"><img src="../assets/images/appstore.jpg" alt=""></button>
           </div>
            <p class="text-center py-3" id="lastP">Or <a href="#">Sign up,</a> to start tutoring.</p>
        </div>
    </div>
</template>

<style scoped>
#learnContainer{
    background: #3E4095;
    padding: 30px;
}
h3{
    font-family: Raleway;
    font-style: normal;
    font-weight: 800;
    font-size: 48px;
    line-height: 56px;

    color: #FFFFFF;
}
p{

    font-family: Raleway;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    color: #FFFFFF;
}


button{
    border-radius: 15px;
    border: none;
}
button img{
    border-radius: 10px;
    width: 200px;
    height: 60px;
    border: none;
}
#lastP{
    font-size: 18px;
}
#lastP a{
    color: #FFFFFF;
}
@media screen and (max-width: 910px) {

    h3{
        font-weight: bold;
        font-size: 36px;
        padding-top: 15px;

    }
    p{
        font-size: 24px;
    }

}
@media screen and (max-width: 600px){
    h3{
        font-size: 24px;
    }
   p{
        font-size: 18px;
    }
    
}
</style>