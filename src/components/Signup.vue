<template>
    <div id="signup" class="py-5">
        <div class="container my-5">
            <div class="row ">
                <div class="col-lg-8 pl-5">
                <h3 class="text-left">Earn extra money tutoring</h3>
                <p class="text-left">set your own Schedule, be your own boss.</p>
                </div>
                <div class="col-lg-4 text-center">
                     <button id="signupBtn" class="px-1 my-5">Sign Up To Tutor</button>
                <div />
            </div>
        </div>
    </div>
    </div>
</template>

<style scoped>
#signup{
   background:  #3e4095;;
}
#signup h3{
    font-family: Raleway;
    font-style: normal;
    font-weight: bold;
    font-size: 42px; 
    color: #FFFFFF;
}
#signup p{
    font-family: Raleway;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    color: #FFFFFF;

}
#signupBtn {
    color: #FD640F;
    font-family: Raleway;
    font-style: normal;
    font-weight: bold;
    font-size: 18px;
    width: 250px;
    height: 53px;
    border: none;
    border-radius: 5px;
    align-items: center;
}

@media screen and (max-width: 910px) {

    #signup h3{
        font-weight: bold;
        font-size: 36px;
    }
    #signup p{
        font-size: 24px;
    }
    
}
@media screen and (max-width: 600px){
    #signup h3{
        font-size: 24px;
    }
    #signup p{
        font-size: 14px;
    }
    #signupBtn{
      width: 250px;  
      font-size: 14px;
    }
    
}


</style>