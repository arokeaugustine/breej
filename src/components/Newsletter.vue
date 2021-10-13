<template>
    <div class="">
        <div class="container text-center">
            <div class="d-inline-flex text-center my-5">
                <p class=" lead pt-2 pr-2" id="newlettertext">Newsletter</p>
                <form action="" class="d-inline-flex">
                    <input type="text" placeholder="Your email" class="btn-text pt-1  mb-1">
                    <button type="submit"><i class="fa fa-paper-plane"></i></button>
                </form>
            </div>
        </div>
    </div>

</template>

<style scoped>
    .container{
        border-bottom: 3px solid #FE724C;;
    }
    #newlettertext{
        font-family: Raleway;
        font-style: normal;
        font-size: 18px;
        /* border: 2px solid rebeccapurple; */
        color: #0A142F;
        padding-top:100px ;
    }

    input{
        background: #3E4095;
        border-radius: 36px  0 0 36px;
        height: 50px;
        color: #fff;
        border: none;
    }
    input[type="text"]
    {
        width: 150px;
        padding-left: 10px;
    } 
 
    button{
        height: 50px;
        width: 50px;
        border-radius: 0  36px 36px 0 ;
        padding-left: -5px;
        border: none;

    }
    button i{
        color: #3E4095;
    }

    /* .btnImg{
    height: 63px;
        width: 80px;
        border-radius: 36px;
        margin-left: -35px;
    } */
</style>