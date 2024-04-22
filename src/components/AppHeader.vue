<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <header>
        <nav class="navbar bg-body-tertiary">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img src=". fd\images\HelloIMG1669149314369.png" alt="Bootstrap" width="30" height="24">
    </a>

        <div class="navbar-nav flex-row column-gap-5">
            <div class="nav-item" >
                <a class="nav-link" style="color: #ffc96b">Home</a>
            </div>
            <div class="nav-item" >
                <a class="nav-link" > Mission </a>
            </div>
            <div class="nav-item" >
                <a class="nav-link">Causes</a>
            </div>
            <div class="nav-item" >
                <a class="nav-link">Journal</a>
            </div>
            <div class="nav-item" >
                <a class="nav-link " style="background-color: #ffc96b; padding: 10px;" >Donate</a>
            </div>

        </div>        


  </div>
</nav>
    </header>
</template>

<style>
header{
    .container{
        width: 100%;
        display: flex;
        justify-content: space-between;
    }

    /* .navbar-nav{
        column-gap: 20px;
    } */
} 

</style>