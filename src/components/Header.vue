<script setup>
</script>

<template>
    <div class="container-header" data-aos="fade-in">
        <a href="/" class="container-header-logo">Portfolio</a>
        <ul class="container-header-links">
            <li><a href="/" class="container-header-link">Projects</a></li>
            <li><a href="/" class="container-header-link">Contact</a></li>
            <li><a href="/" class="container-header-link">About</a></li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
.container-header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 20px;

    .container-header-logo {
        color: paleturquoise;
        font-size: 24px;
        font-weight: bold;
        font-family: 'Montserrat', sans-serif;
    }

    .container-header-links {
        display: flex;
        gap: 20px;

        .container-header-link {
            color: grey;
            font-size: 16px;
            font-weight: light;
            font-family: 'Montserrat', sans-serif;

            &:hover {
                color: white;
            }
        }
    }
}

@media (max-width: 768px) {

    .container-header {

        .container-header-links {
            display: none;
        }
    }
}
</style>