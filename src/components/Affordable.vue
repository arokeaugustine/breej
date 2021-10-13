<template>
    <div class="p-5 my-5">
        <div class="row" id="parentdiv">
            <div class="col-lg-4 pt-5">
                 <!-- for larger screen sizes -->
                  <div class="d-none d-lg-block"> 
                    <img src="../assets/images/Vector(3).png" alt="" class="img-fluid py-3">
                    <h5 class="text-left">Easy to use</h5>
                    <p class="text-left">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                        Illo officiis vero delectus ipsam labore consequatur, 
                        eum dolores quae distinctio, aut nobis? Culpa.</p>
                  </div>     

                     <!-- for small screen -->
               <div class="d-lg-none text-center">
                   <img src="../assets/images/Vector(3).png" alt="" class="img-fluid py-3">
                    <h5 class="text-center">Easy to use</h5>
                    <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                        Illo officiis vero delectus ipsam labore consequatur, 
                        eum dolores quae distinctio, aut nobis? Culpa.</p>
               </div>   
                

            </div>
            <div class="col-lg-4 pt-5">
                <!-- for larger screen sizes -->
                <div class="d-none d-lg-block">
                     <img src="../assets/images/cash.png" alt="" class="img-fluid py-3">
                    <h5 class="text-left">Affordable</h5>
                    <p class="text-left">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                        Illo officiis vero delectus ipsam labore consequatur, 
                        eum dolores quae distinctio, aut nobis? Culpa.</p>
                </div>
                
                <!-- for small screen -->
               <div class="d-lg-none text-center">
                   <img src="../assets/images/cash.png" alt="" class="img-fluid py-3 text-center">
                    <h5 class="text-center">Affordable</h5>
                    <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                        Illo officiis vero delectus ipsam labore consequatur, 
                        eum dolores quae distinctio, aut nobis? Culpa.</p>
               </div>

            </div>
            <div class="col-lg-4 pt-5">
                <!-- for larger screen sizes -->
                <div class="d-none d-lg-block"> 
                <img src="../assets/images/Vector(3).png" alt="" class="img-fluid py-3">
                <h5 class="text-left">Fast and reliable</h5>
                <p class="text-left">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    Illo officiis vero delectus ipsam labore consequatur, 
                    eum dolores quae distinctio, aut nobis? Culpa.</p>
                </div>

                 <!-- for small screen -->
               <div class="d-lg-none text-center">
                <img src="../assets/images/Vector(3).png" alt="" class="img-fluid py-3">
                <h5 class="text-center">Fast and reliable</h5>
                <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    Illo officiis vero delectus ipsam labore consequatur, 
                    eum dolores quae distinctio, aut nobis? Culpa.</p>
               </div>

              
            </div>
        </div>
    
    </div>
</template>

<style scoped>
    h5{
        font-family: Raleway;
        font-style: normal;
        font-weight: 600;
        font-size: 36px;
        line-height: 42px;

        color: #000000;
    }
    p{
        font-family: Raleway;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 21px;

        color: #000000;
    }
    #parentdiv{
        padding-top: 40px;
        padding-bottom: 40px;
    }
</style>