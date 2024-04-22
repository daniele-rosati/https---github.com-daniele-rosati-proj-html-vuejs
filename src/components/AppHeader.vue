<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <header style="background-color: aqua; background-image: url(images/HelloIMG1669149393797.jpeg); " >
        <nav class="navbar ">
            <div class="container">
                <a class="navbar-brand" href="#">
                    <!-- <div> <img src=".\images\HelloIMG1669149323379.png" alt=""> </div> -->
                    <div class="font"> Logo non funziona oidocro'</div>
                </a>

                <div class="navbar-nav flex-row column-gap-5">
                    <div class="nav-item" >
                        <a class="nav-link font" style="color: #ffc96b">Home</a>
                    </div>
                    <div class="nav-item" >
                        <a class="nav-link font" > Mission </a>
                    </div>
                    <div class="nav-item" >
                        <a class="nav-link font">Causes</a>
                    </div>
                    <div class="nav-item" >
                        <a class="nav-link font">Journal</a>
                    </div>
                    <div class="nav-item" >
                        <a class="nav-link font" style="background-color: #ffc96b; padding: 10px;" >Donate</a>
                    </div>
                </div>        
            </div>
        </nav>

        <div class="container">
            <div class="container text-center container-header">

                    <div class="font" style="font-size: 60px;">MAKE A DIFFERENCE</div>
                    <p class="font">As long as poverty, injustice & inequality persist, none of us can truly rest</p>

                    <div class="container-btn ">
                        <button class="font" type="button" style="border-color: #ffffff; background: none; border-style:solid;"> OUR MISSION </button>
                        <button class="font" style="border-color: #ffc96b; background: none; border-style:solid;"> DONATE NOW </button>
                    
                    </div>
            </div>
        </div>
    </header>
</template>

<style>
header{

    

    .container{
        width: 100%;
        
    }

    .container-header{
        padding: 200px;
       
    }

    .container-btn{
        display: flex;
        justify-content: center;
        flex-direction: row;
        column-gap: 10px;
    }

    .font{
        color:#f9f9f9;
    }

    /* .navbar-nav{
        column-gap: 20px;
    } */
} 

</style>