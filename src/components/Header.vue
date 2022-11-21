<template>
    <header>
        <nav>
            <h2><a href="#">VUE</a></h2>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
</template>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

header {
    margin: 0;
    background-color: #efefef;
    color: #000;
}

header nav {
    padding: 10px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

header nav h2 a {
    color: rgba(0, 150, 0, 1);
    text-decoration: none;
    font-weight: 600;
}

header nav ul {
    list-style: none;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
}

header nav ul li a {
    color: #000;
    margin-left: 1rem;
    text-decoration: none;
    justify-content: space-between;
    align-items: center;
}
</style>