<script setup>
</script>

<template>
    <div class="container-hero">
        <h1 data-aos="fade-down">Portfolio</h1>
        <p data-aos="fade-down">Trying our <span>best</span> to product the <span>best</span> for you!</p>
    </div>
    <div class="container-tech" data-aos="fade-down">
        <h2 class="container-tech-h2" data-aos="flip-up">Tech Stack</h2>
        <div class="container-stack">
            <i class="fa-brands fa-html5" title="HTML"></i>
            <i class="fa-brands fa-css3-alt" title="CSS"></i>
            <i class="fa-brands fa-js" title="Javascript"></i>
            <i class="fa-brands fa-vuejs" title="Vue"></i>
            <i class="fa-brands fa-react" title="React"></i>
        </div>
    </div>
    <div class="container-buttons">
        <button data-aos="fade-right">View Projects</button>
        <button data-aos="fade-left">Contact Me</button>
    </div>
    <div class="container-scroller" data-aos="fade-up">
        <p>Scroll Down</p>
        <i class="fa-solid fa-chevron-down"></i>
    </div>
</template>

<style lang="scss" scoped>
.container-hero {
    display: block;
    text-align: center;
    margin-top: 80px;
    margin-left: 20px;
    margin-right: 20px;
    margin-bottom: 40px;

    h1 {
        color: paleturquoise;
        font-size: 50px;
        font-family: 'Playfair', serif;
    }

    p {
        color: white;
        font-size: 18px;
        font-family: 'Montserrat', sans-serif;

        span {
            color: paleturquoise;
        }
    }
}

.container-tech {
    display: block;
    text-align: center;

    .container-tech-h2 {
        color: paleturquoise;
        font-size: 30px;
        font-family: 'Playfair', serif;
    }

    .container-stack {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 10px;
        padding: 10px;

        i {
            color: grey;
            font-size: 30px;

            &:hover {
                color: white;
                cursor: pointer;
            }

        }
    }
}

.container-buttons {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;

    button {
        background-color: paleturquoise;
        color: rgb(15, 15, 25);
        border-radius: 4px;
        font-size: 16px;
        padding: 6px 12px;

        &:hover {
            background-color: rgb(120, 195, 195);
            cursor: pointer;
        }
    }
}

.container-scroller {
    display: block;
    text-align: center;
    margin: 80px 40px;

    p {
        color: white;
        font-size: 16px;
        font-family: 'Montserrat', sans-serif;
    }

    i {
        color: paleturquoise;
        animation: bounce 2s infinite;
    }

    @keyframes bounce {

        0% {
            transform: translateY(0);
        }

        50% {
            transform: translateY(10px);
        }
    }
}
</style>