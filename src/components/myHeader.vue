<template>
    <header>
        <div class="jumbo">
            <section>
                <div class="title">
                    <h4>Certified fitness professional</h4>
                    <h1>Take control of your health</h1>
                    <div class="rule"></div>
                    <p>Curabitur non molla sit amet nisl tempus convallis quis ac lectus dolor sit amet</p>
                    <button><i class="fab fa-youtube"></i> Visit my youtube channel</button>
                    <button class="avada">Buy avada today <i class="fas fa-arrow-right"></i></button>
                </div>
                <div class="container-play">
                    <div class="play"><i class="fas fa-play"></i></div>
                </div>
            </section>
            
        </div>
    </header>
</template>

<script>

export default {
  name: 'myHeader',
 
}
</script>

<style lang="scss">
header {
    .jumbo {
        background-image: url("../assets/img/slider82x-scaled.jpg");
        background-size: cover;
        background-repeat: no-repeat;
        height: 500px;
        display: flex;
        align-items: center;
        section {
            display: flex;
            align-items: center;
            color: white;
            width: 80%;
            margin: 0 auto;
            height: 100%;
            background: rgb(0,0,0);
            background: linear-gradient(90deg, rgba(0,0,0,1) 47%, rgba(0,0,0,0) 59%);
                .title {
                width: 50%;
                button {
                background-color: #3230a1; /* Green */
                border: 2px solid #3230a1;
                border-radius: 20px;
                color: white;
                padding: 10px 20px;
                text-align: center;
                text-decoration: none;
                display: inline-block;
                font-size: 12px;
                cursor: pointer;
                }
                button:hover {
                background: crimson;
                border:crimson 2px solid ;
                }
                .avada {
                background-color: transparent; /* Green */
                border: 2px solid white;
                border-radius: 20px;
                color: white;
                padding: 10px 20px;
                text-align: center;
                text-decoration: none;
                display: inline-block;
                font-size: 12px;
                cursor: pointer;
                margin-left: 10px;
                }
                .avada:hover {
                background: white;
                color: black;
                border: 2px solid white;
                }
            }
            h4 {
                color: rgb(231, 60, 117);
                margin-bottom: 20px;
            }
            .rule {
                width: 40px;
                border: 2px solid yellow;
                margin: 20px 0;
            }
            p {
                color: gray;
                margin-bottom: 20px;
            }
            .container-play {
                width: 50%;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .play {
                display: flex;
                align-items: center;
                justify-content: center;
                background: white;
                color: teal;
                width: 50px;
                height: 50px;
                border-radius: 100%;
                cursor: pointer;
            }
        }
        
    }
}

</style>