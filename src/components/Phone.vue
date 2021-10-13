<template>
    <div id="Phonecontainer">
        <div class="mx-5">
            <div class="row">
                <div  class="col-lg-4" >
                <img src="../assets/images/phone.png" alt="" id="phone" class="img-fluid">
                 </div>
                <div class="col-lg-8 py-5" >
                      <!-- code for large and lower screens -->
                     <div class="d-lg-none text-center" id="smallScreentext">
                          <h3>
                            Buy anything online in minutes
                        </h3>
                        <p class="lead" id="phoneParagraph">Download the breej app now</p>
                        <div>
                        <button ><img src="../assets/images/Icon Google play.png" alt=""> </button>
                         <button class="mt-2"><img src="../assets/images/appstore.jpg" alt="" id="Secondbtn"></button>
                        </div>
                     </div>

                     <!-- text to appear on screen bigger than large -->
                    <div class="d-none d-lg-block">
                        <h3 class="">
                            Buy anything online in minutes
                        </h3>
                        <p class="lead" id="phoneParagraph">Download the breej app now</p>
                        <div>
                        <button ><img src="../assets/images/Icon Google play.png" alt=""> </button>  <button ><img src="../assets/images/appstore.jpg" alt="" id="Secondbtn"></button>
                        </div>
                    </div>
                   
                </div>
               
            </div>
       
    </div>
     </div>
</template>

<style scoped >
#Phonecontainer{
    background: rgba(254, 114, 76, 0.4);
}
#phone{
    margin-top: -150px;
}
#Phonecontainer h3{
    font-family: Raleway;
    font-style: normal;
    font-weight: 800;
    font-size: 40px;
    line-height: 56px;

    color: #263238;
}
#phoneParagraph{

    font-family: Raleway;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    /* line-height: 33px; */
    color: #263238;
    /* border: 2px solid red; */


}
button{
    border-radius: 15px;
    background: rgba(254, 114, 76, 0.4);
}
button img{
    border-radius: 15px;
    width: 200px;
    height: 60px;
    background: rgba(254, 114, 76, 0.4);
}
@media screen and (max-width: 910px) {

    #Phonecontainer h3{
        font-weight: bold;
        font-size: 36px;
        padding-top: 15px;

    }
    #phoneParagraph{
        font-size: 24px;
    }

     #smallScreentext h3{
         border: 2px solid green;
         padding-top: 0;
         margin-top: -20px;
     }

}
@media screen and (max-width: 600px){
   #Phonecontainer h3{
        font-size: 24px;
    }
   #phoneParagraph{
        font-size: 18px;
    }
    #signupBtn{
      width: 250px;  
      font-size: 14px;
    }
    
}

</style>