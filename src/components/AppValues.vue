<script>
export default {
    name: 'AppValues'
}
</script>

<template>

    <div id="container-values" style="background-image: url(images/home-content-bg-2.jpg); background-size: cover; ">
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             
        <div id="container-col" class="container text-center">
            <div class="row">
            
                <div class="col align-self-center d-flex">
                <h2 class="font"> OUR VALUES </h2>
                <hr class="under-title opacity-80 text-center">
                <p class="font">Think Big. Act Bigger.</p>
                </div>
            </div>
            <div class="row">
            
                
                <div class="col ">
                    <i class="fa-solid fa-droplet fs-1" style="color: #ffc96b;"></i>
                    <div class="font" style="padding:15px;" > <strong>Clean Water </strong> </div>
                    <p class="font"> Nullam convalis, orci in coungue aliquet, diam mauris cursus urna , id maximum lectus magna maximus. </p>
                    <div> <button class="btn btn-warning opacity-80  " style="color:#ffffff; border-radius: 0%; margin-top: 25px; " type="button">OUR MISSION</button> </div>
                </div>
                <div class="col">
                    <i class="fa-solid fa-stethoscope fs-1" style="color: #ffc96b;"></i>
                    <div class="font" style="padding:15px;"> <strong> Vacciantions </strong> </div>
                    <p class="font"> Nullam convalis, orci in coungue aliquet, diam mauris cursus urna , id maximum lectus magna maximus. </p>
                    <div > <button class="btn btn-warning opacity-80 " style="color:#ffffff; border-radius: 0%; margin-top: 25px; " type="button">OUR MISSION</button> </div>
                </div>
                <div class="col">
                    <i class="fa-solid fa-graduation-cap fs-1" style="color: #ffc96b;"></i>
                    <div class="font" style="padding:15px;"> <strong> Education </strong> </div>
                    <p class="font"> Nullam convalis, orci in coungue aliquet, diam mauris cursus urna , id maximum lectus magna maximus. </p>
                    <div> <button class="btn btn-warning opacity-80 " style="color:#ffffff; border-radius: 0%; margin-top: 25px; " type="button">OUR MISSION</button> </div>
                </div>
                <div class="col">
                    <i class="fa-solid fa-wheat-awn fs-1" style="color: #ffc96b;"></i>
                    <div class="font" style="padding:15px;"> <strong> Farming </strong> </div>
                    <p class="font"> Nullam convalis, orci in coungue aliquet, diam mauris cursus urna , id maximum lectus magna maximus. </p>
                    <div> <button class="btn btn-warning opacity-80 " style="color:#ffffff; border-radius: 0%; margin-top: 25px; " type="button">OUR MISSION</button> </div>
                </div>
            </div>
            

        </div>
        
    </div>

</template>

<style>
    #container-values{
        width: 100%;
        height: 100% ;
    }
    
    #container-col{
        padding-top:10%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
    }

    .d-flex{
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .col{
        padding-top: 5%;
        padding-bottom: 5%;
    }

    /* .btn:hover .brn-warning{
        color: #262e44;
    }

    i:hover{
        color: white;
    } */

</style>