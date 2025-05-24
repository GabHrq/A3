<template>
    <div class="navbar">
        <div class="navbar-container">
            <div class="left"><span>Flappy Graphic</span></div>
            <div class="right">
                <button id="navbutton">GitHub</button>
            </div>
        </div>
    </div>
</template>

<style>
    .navbar {
        display: flex;
        width: 100%;

        justify-content: center;
    }

    .navbar-container {
        display: flex;
        width: 100%;
        max-width: 60rem;
        flex-direction: row;
        justify-content: space-between;

        align-items: center;
        margin: 0 1rem;
    }

    #navbutton {
        padding: 0.4rem 0.8rem;
        background-color: rgb(82, 138, 119);
        border-radius: 8px;
    }
</style>