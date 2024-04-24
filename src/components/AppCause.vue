<script>
export default {
    name: 'AppCause'
}
</script>

<template>

<div id="container-causes" class="container">

    <div class="container"> 
        <div class="container text-center">
            <div class="row align-items-start">
                
                <div class="col col align-self-center d-flex">
                <h2> RECENT CAUSES </h2>
                <hr class="under-title opacity-100 text-center">
                <div> We run projects in over 30 countries in 5 contintents </div>
                </div>
                
            </div>
        </div>
        

    </div>

    <div class="container text-center">
        <div class="row">
            <div class="col-3">
            <img src="C:\Users\Daniele\proj-html-vuejs\images\avada-charity-fair-trade-featured-600x450.jpg" alt="trade">
            </div>
            <div class="col-3">
            <img src="C:\Users\Daniele\proj-html-vuejs\images\avada-charity-shelter-featured-600x450.jpg" alt=" shelter">
            </div>
            <div class="col-3">
            <img src="C:\Users\Daniele\proj-html-vuejs\images\avada-charity-farming-featured-600x450.jpg" alt="">
            </div>
            <div class="col-3">
            <img src="C:\Users\Daniele\proj-html-vuejs\images\avada-charity-vaccines-featured-600x450.jpg" alt="">
            </div>
        </div>
    
    </div>

    

</div>

<div class="container-red font" >
    <h4>VIEW ALL OUR CAUSES</h4>
</div>

</template>

<style>

    #container-causes{
        padding-bottom: 5%;
        padding-top: 5%;
    }

    .container-red{
    display: flex;
    justify-content: center;
    background-color: #ed6967;
    padding-top: 30px;
    padding-bottom: 30px;

    }
    

    img{
        width: 100%;
    }

</style>