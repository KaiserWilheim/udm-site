<script setup>
</script>

<template>
    <header>
    </header>

    <main>
        <div class="ground">
            <div class="lobby">
                <div class="con">
                    <h1>UNIWERSYTET</h1><h1>DOMOWY</h1>
                    <h3>Home University</h3>
                </div>
                <div class="con">
                    <h2>
                        Site under construction...
                    </h2>
                </div>
            </div>
        </div>
    </main>
</template>

<style scoped>
    .ground {
        position: relative;
        display: grid;
        justify-content: center;
        align-content: center;
        height: 100vh;
    }

    .lobby {
        display: flex;
        padding: 20px;
        align-items: center;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    .con {
        padding: 20px 30px;
        position:relative;
    }

        .con:not(:last-child)::after {
            content: "";
            position: absolute;
            right: 0;
            top: 0;
            bottom: 0;
            width: 1px;
            background-color: black;
        }

    h1 {
        color: #500050;
        text-align: right;
        font-family: "Noto Serif";
    }

    h3 {
        color: #500050;
        text-align: right;
        font-family: "Times New Roman";
    }

    h2 {
        color: #000000;
        text-align: left;
        font-family: "Segoe UI";
    }
</style>
