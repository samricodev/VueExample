<template>
    <div class="container">
        <h2>TITULO</h2>
        <div class="card">
        <h2>SubTitulo</h2>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Impedit ab voluptatem cupiditate velit deleniti rem nam at. Officia eligendi ducimus commodi culpa magnam labore? Sint optio fugit velit aliquam sequi?</p>
    </div>
    <div class="card">
        <h2>SubTitulo</h2>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Impedit ab voluptatem cupiditate velit deleniti rem nam at. Officia eligendi ducimus commodi culpa magnam labore? Sint optio fugit velit aliquam sequi?</p>
    </div>
    <div class="card">
        <h2>SubTitulo</h2>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Impedit ab voluptatem cupiditate velit deleniti rem nam at. Officia eligendi ducimus commodi culpa magnam labore? Sint optio fugit velit aliquam sequi?</p>
    </div>
    <div class="card">
        <h2>SubTitulo</h2>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Impedit ab voluptatem cupiditate velit deleniti rem nam at. Officia eligendi ducimus commodi culpa magnam labore? Sint optio fugit velit aliquam sequi?</p>
    </div>
    </div>
</template>

<style>
    body{
        background-color: transparent;
        color: #fff;
    }

    .container{
        display: grid;
        grid-template-columns: auto;
        color: rgba(255,255,255,0.5);
        margin-top: 20px;
        margin-left: 10%;
        margin-right: 10%;
        margin-bottom: 20px;
        width: 80%;
    }

    .container h2{
        color: #fff;
        text-align: center;
    }

    .card{
        padding: 10px;
        margin: 10px 0px 20px 0px;
        border: rgba(0,0,0, 1);
        border-radius: 20px;
        box-shadow: 1px 1px 1px 1px rgba(255,255,255,1);
    }

    .card h2{
        text-align: left;
        color: rgba(0, 150,0, 1);
    }
</style>