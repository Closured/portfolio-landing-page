<script setup>
</script>

<template>
    <div class="container-projects" data-aos="fade-up">
        <h2 class="container-project-title">Projects</h2>
        <div class="container-project">
            <div class="container-p">
                <i class="fa-solid fa-code"></i>
                <h3>Project</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quas, veritatis animi velit nesciunt
                    incidunt...</p>
                <button>View</button>
            </div>
            <div class="container-p">
                <i class="fa-solid fa-code"></i>
                <h3>Project</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quas, veritatis animi velit nesciunt
                    incidunt...</p>
                <button>View</button>
            </div>
            <div class="container-p">
                <i class="fa-solid fa-code"></i>
                <h3>Project</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quas, veritatis animi velit nesciunt
                    incidunt...</p>
                <button>View</button>
            </div>
            <div class="container-p">
                <i class="fa-solid fa-code"></i>
                <h3>Project</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quas, veritatis animi velit nesciunt
                    incidunt...</p>
                <button>View</button>
            </div>
            <div class="container-p">
                <i class="fa-solid fa-code"></i>
                <h3>Project</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quas, veritatis animi velit nesciunt
                    incidunt...</p>
                <button>View</button>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container-projects {
    display: block;
    text-align: center;
    margin: 80px 20px;
    

    .container-project-title {
        color: white;
        font-family: 'Montserrat', sans-serif;
    }

    .container-project {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        gap: 20px;
        margin: 20px;

        .container-p {
            width: 200px;
            height: 300px;
            border: 1px solid paleturquoise;
            border-radius: 10px;
            padding: 20px;

            i {
                color: paleturquoise;
                font-size: 24px;
                margin-bottom: 20px;
            }

            h3 {
                color: white;
                font-family: 'Montserrat', sans-serif;
                margin-bottom: 20px;
            }

            p {
                color: grey;
                font-family: 'Montserrat', sans-serif;
                margin-bottom: 10px;
            }

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
    }
}
</style>