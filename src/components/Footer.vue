<template>
    <footer>
        <div>
            <ul>
                <li><a href="#"><img src="../assets/facebook.png"></a></li>
                <li><a href="#"><img src="../assets/instagram.png"></a></li>
                <li><a href="#"><img src="../assets/gorjeo.png"></a></li>
            </ul>
        </div>
        <div>
            <p>Desarrollo Web I ©️ Todos los derechos reservados</p>
        </div>
    </footer>
</template>

<style>
    footer{
        padding: 10px;
        justify-content: center;
        color: #000;
        position: relative;
        bottom: 0;
        background-color: #efefef;
        width: 100%;
    }

    footer ul{
        width: 50%;
        list-style: none;
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        align-items: center;
        padding: auto;
        margin: auto;
    }

    footer p{
        text-align: center;
    }

    footer img{
        width: 32px;
        height: 32px;
    }
</style>