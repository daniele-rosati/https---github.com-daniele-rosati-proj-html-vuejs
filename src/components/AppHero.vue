<script>
export default {
    name: 'AppHero'
}
</script>


<template>
<div id="container-hero" >
    <div class="">
        <div class="row" style="margin: 0;">
            <div  class="col-9 right" style="padding-right: 0;">
                <div class="col-10 ">

                    <div class="title" style="font-size: 25px;">
                        EVERY MOMENT COUNTS
                    </div>
                    <hr class="under-title opacity-80">
                    <div class="par">
                        <p>Curabitur non mi et tupis pharetra vulputate. Cras consequat, risus nec commodo vehicula, nisi est laoreet leo. ac convallis nisi nibh id velit. Aliquam mattis metus  a nisi pretium</p>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt molestiae illo, quasi cupiditate dolorem consequatur alias molestias magnam, eos repudiandae itaque ducimus asperiores, repellat voluptates quae quod laudantium doloremque voluptatibus.</p>
                        <p>Curabitur non mi et tupis pharetra vulputate. Cras consequat, risus nec commodo vehicula, nisi est laoreet leo. ac convallis nisi nibh id velit.</p> 
                    </div>
                    <button class="btn btn-warning opacity-100 " style="color:#ffffff; border-radius: 0%; margin-top: 25px; " type="button">OUR MISSION</button>
                </div>
            </div>
            <div class=" col-3 " style=" padding: 0; ">
                <div class="col-2 " style="background-image: url(images/sfondo-numeri.jpg); width: 100%; height: 100%;  ">
                    <p>
                        <div class="font fs-1"><i class="fa-regular fa-heart"></i> 2032</div>
                        <div class="font">Volunteers worldwide</div>
                    </p>
                    <p>
                        <div class="font fs-1"> <i class="fa-solid fa-earth-americas"></i>132</div>
                        <div class="font">active projects</div>
                    </p>
                    <p>
                        <div class="font fs-1"> <i class="fa-solid fa-dollar-sign"></i> 3.8M </div>
                        <div class="font">Donated</div>
                    </p>
                </div>
            
                </div>
        </div>
    </div>
</div>


</template>

<style>

    #container-hero{
    display: flex;
    align-items: center;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    }

    .under-title{
        width: 150px;
        margin: 1rem 0;
        color: #ffc96b;
        border: solid 2px;
        
    }

    .par{
        padding-top: 20px;
    }

    .col-10{
        padding-bottom: 5%;
    }

    .col-2{
    height: 370px;
    text-align: center;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    padding-right: 0%;
    }

    .right{
        display: flex;
        justify-content: center;
        align-items: center;
        padding-top: 60px;
    }

    

    .font{
        color:#f9f9f9;

    }
</style>