<template>
    <div class="m-5">
        <!-- first row containing image and writeup that changes on small screen sizes -->
        <div class="row">
            <div class="col-lg-6">
                <img src="../assets/images/desktop.jpg" alt="" class="img-fluid">
            </div>
            <div class="col-lg-6 pl-5 " id="imageOneWriteUp">
                <!-- code for resolutions greater than large -->
               <div class="d-none d-lg-block">
                    <h3 class="pt-3" >Approach tutorials <br> Differently</h3>
                <p class="lead" id="leadText">Save More time for your studies</p>
                <p class="text-left" id="mainPara">Lorem ipsum dolor sit, amet consectetur adipisicing elit. <br>
                     iure laborum commodi numquam porro hic. <br> Lorem 
                     ipsum dolor sit amet consectetur adipisicing elit. 
                     Quos, provident?</p>
                 <a href="">Learn more</a>
               </div>
                <!-- code for large and lower screens -->
                <div id="secondWriteup" class="d-lg-none">
                    <p class="lead">Request a tutor any course.</p>
                    <h3>Need a help with your studies?</h3>
                    <p id="secondPara">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                         Eaque asperiores suscipit possimus repudiandae soluta modi cum enim.</p>
                         <button id="getStartedBtn" class="">learn more</button>
                </div>
                

            </div>
        </div>

        <!-- second display of picture and writeup -->
         <div class="row my-5 pt-5">
            <div class="col-lg-6 pl-5 " id="imageOneWriteUp">
                <!-- code for resolutions greater than large -->
               <div class="d-none d-lg-block">
                <h3 class="pt-3 text-right" >Sell your items</h3>
                <p class="lead text-right" id="leadText">Recieve Payment instantly</p>
                <p class="text-right" id="mainPara">Lorem ipsum dolor sit, amet consectetur adipisicing elit. <br>
                     iure laborum commodi numquam porro hic. <br> Lorem 
                     ipsum dolor sit amet consectetur adipisicing elit. 
                     Quos, provident?</p>
                 <div class="text-right"><a href="" class="text-right">Learn more</a></div>
               </div>
                <!-- code for large and lower screens -->
                <div  class="d-lg-none">
                   <img src="../assets/images/room.jpg" alt="" class="img-fluid">
                </div>
                

            </div>     
           <div class="col-lg-6 pl-5 " id="imageOneWriteUp">
               
                 <!-- code for resolutions greater than large -->
               <div class="d-none d-lg-block">
                  <img src="../assets/images/room.jpg" alt="" class="img-fluid">
               </div>
                <!-- code for large and lower screens -->
                <div id="secondWriteup" class="d-lg-none">
                    <p class="lead pt-5">Reach the larger market.</p>
                    <h3>Need a help with your studies?</h3>
                    <p id="secondPara">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                         Eaque asperiores suscipit possimus repudiandae soluta modi cum enim.</p>
                         <button id="getStartedBtn" class="">learn more</button>
                </div>
                

            </div>     
 
        </div>

        <!-- third image section -->
        <div class="row pt-5">
            <div class="col-lg-6">
                <img src="../assets/images/laptop.jpg" alt="" class="img-fluid">
            </div>
            <div class="col-lg-6 pt-5 pl-5" id="thirdsection">
                <!-- text to appear on screen bigger than large -->
                <div class="d-none d-lg-block">
                     <h3 class="">Experienced in teaching?</h3>
                    <p class="lead" id="leadtext">Become a tutor</p>
                    <h6 id="otherwriteup">Lorem ipsum, dolor sit amet <br>
                    consectetur adipisicing elit. <br>
                    Sit itaque quas illum <br>
                    molestiae praesentium ipsam iusto.</h6>
                   <div><a href="" class="text-right">Learn more</a></div>
                </div>
              <!-- code for large and lower screens -->
                <div class="d-lg-none" id="breej-text">
                    <p class="lead text-left">Become a breej</p>
                    <h3 class="text-left">Earn while studying.</h3>
                    <p id="secondPara" class="text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                         Eaque asperiores suscipit possimus repudiandae soluta modi cum enim.</p>
                         <button id="getStartedBtn" class="">learn more</button>
                </div>
               
            </div>
            
        </div>

        <!-- last section of picture, uses the same style as the second section -->

          <div class="row my-5 pt-5" id="lastImageContainer">
            <div class="col-lg-6 pl-5 " id="imageOneWriteUp">
                <!-- code for resolutions greater than large -->
               <div class="d-none d-lg-block">
                <h3 class="pt-3 text-right Bold" >Buy your provisions</h3>
                <p class="lead text-right" id="leadText">Save more time for your studies.</p>
                <p class="text-right" id="mainPara">Lorem ipsum dolor sit, amet consectetur adipisicing elit. <br>
                     iure laborum commodi numquam porro hic. <br> Lorem 
                     ipsum dolor sit amet consectetur adipisicing elit. 
                     Quos, provident?</p>
                 <div class="text-right"><a href="" class="text-right">Learn more</a></div>
               </div>
                <!-- code for large and lower screens -->
                <div  class="d-lg-none">
                   <img src="../assets/images/provision.jpg" alt="" class="img-fluid">
                </div>
                

            </div>     
           <div class="col-lg-6 pl-5 " id="imageOneWriteUp">
               
                 <!-- code for resolutions greater than large -->
               <div class="d-none d-lg-block">
                  <img src="../assets/images/provision.jpg" alt="" class="img-fluid">
               </div>
                <!-- code for large and lower screens -->
                <div id="secondWriteup" class="d-lg-none mb-5">
                    <p class="lead pt-5">Order goods online and have them delivered.</p>
                    <h3>Too busy to reach the market place?</h3>
                    <p id="secondPara">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                         Eaque asperiores suscipit possimus repudiandae soluta modi cum enim.</p>
                         <button id="getStartedBtn" class="">learn more</button>
                </div>
                

            </div>     
 
        </div>
    </div>
</template>

<style scoped>
    #imageOneWriteUp h3{
        font-family: Raleway;
        font-style: normal;
        font-weight: bold;
        font-size: 35px;
        line-height: 41px;

        color: #263238;

        opacity: 0.8
    }
    #leadText{
        color: #263238;
        opacity: 0.7;
        /* border: 2px solid red; */
        font-style: normal;
        font-weight: 500;
        font-size: 28px;
    }
    #mainPara{        
        font-family: Poppins;
        font-style: normal;
        font-weight: 300;
        font-size: 22.5px;
        line-height: 34px;
        color: #263238;
    }
    #imageOneWriteUp a{
        font-family: Futura Bk BT;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 22px;
        text-decoration: none;
    }
    /* style for second writeup to appear on ipad and smaller screen sizes */
    #secondWriteup p{
        font-family: Raleway;
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 21px;
        text-align: left;
    }
    #secondWriteup h3{
        font-family: Raleway;
        font-style: normal;
        font-weight: bold;
        font-size: 24px;
        line-height: 28px;

        color: #3E4095;
    }
    #secondPara{
        font-family: Raleway;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        }

/* css for the third section */
        #thirdsection h3{
            font-family: Raleway;
            font-style: normal;
            font-weight: normal;
            font-size: 35px;
            color: #000000;
        }
        #leadtext{

            font-family: Poppins;
            font-style: normal;
            font-size: 28px;
            color: #263238;
        }
        #otherwriteup{
            font-family: Poppins;
            font-style: normal;
            font-weight: normal;
            font-size: 18px;
        }
        #thirdsection a{
            font-family: Futura Bk BT;
            font-style: normal;
            font-weight: normal;
            font-size: 18px;
            line-height: 22px;
            text-decoration: none;

        }

        /* breej text */
        #breej-text p{
            font-family: Raleway;
            font-style: normal;
            font-size: 18px;
            line-height: 21px;
        }
        #breej-text h3{
            font-family: Raleway;
            font-style: normal;
            font-weight: bold;
            font-size: 24px;
            line-height: 28px;
            color: #3E4095;
        }
        #lastImageContainer{
            padding-bottom: 250px;
        }
</style>