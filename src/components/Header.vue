<template>

    <header>
        <img :src="caminhodaFoto" alt="">
        <div class="links">
            <h2>QUEM SOMOS</h2>
            <h2><a href="">CONTATO</a></h2>   
        </div>
        <div>
            <button class="bg-red-500">RIFA SOLIDÁRIA</button>
        </div> 
        <div>
            <img :src="caminhodosEmojis" alt="Redes Sociais">
        </div>
    </header>

    
</template>

<script>
export default{
    data(){
        return{
            caminhodaFoto: '/logo.png',
            caminhodosEmojis: '/emojis.png'
        }
    }
}

</script>
<style>
    .links{
        color: inherit;
        text-decoration: none;
        
    }
    header{ 
        padding: 2px;
        display: flex;
        justify-content:center;
        align-items: center;
        flex-direction: ;
    }

</style>