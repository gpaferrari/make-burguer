<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>


export default{
    nome: "Banner"

} 
        
    
</script>

<style scoped>
#main-banner{
    background-image: url('/img/burger.jpg');
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

#main-banner h1{
    color: aliceblue;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
}

@media only screen and (min-width: 350px){
    #main-banner{
        background-position: -300px -450px;
    }

}

@media only screen and (min-width: 600px){
    #main-banner{
        background-position: 0 -500px;
    }

}

@media only screen and (min-width: 900px){
    #main-banner{
        background-position: 0 -150px;
    }

}

@media only screen and (min-width: 1450px){
    #main-banner{
        background-position: 0px -400px;
    }

}
</style>
