<script setup>
const currentYear = new Date().getFullYear();
</script>

<template>
    <div class="container-footer" data-aos="fade-in">
        <div class="container-footer-copyright">
            <p>&copy;{{ currentYear }}. Portfolio</p>
        </div>
        <div class="container-footer-logo">
            <h2>Portfolio</h2>
        </div>
        <div class="container-footer-links">
            <ul>
                <li><a href="/" class="link">Projects</a></li>
                <li><a href="/" class="link">Contact</a></li>
                <li><a href="/" class="link">About</a></li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container-footer {
    background-color: paleturquoise;
    display: flex;
    justify-content: space-around;
    text-align: center;
    align-items: center;
    padding: 20px;

    .container-footer-copyright {
        display: flex;

        p {
            color: rgb(15, 15, 25);
            font-size: 16px;
            font-family: 'Montserrat', sans-serif;
        }
    }

    .container-footer-logo {
        display: flex;

        h2 {
            color: rgb(15, 15, 25);
            font-family: 'Playfair', serif;
        }
    }

    .container-footer-links {
        display: flex;

        ul {
            display: block;
            text-align: center;

            .link {
                color: rgb(15, 15, 25);
                font-size: 14px;
                font-family: 'Montserrat', sans-serif;

                &:hover {
                    text-decoration: underline;
                }
            }
        }
    }
}

@media (max-width: 768px) {

    .container-footer {
        display: block;
        text-align: center;

        .container-footer-copyright {
            justify-content: center;
            padding: 10px;
        }

        .container-footer-logo {
            justify-content: center;
        }

        .container-footer-links {
            justify-content: center;
            padding: 10px;

            ul {
                display: flex;
                gap: 20px;
            }
        }
    }
}
</style>