<template>
    <header>
        <div class="jumbo">
            <section>
                <div class="title">
                    <h4>Certified fitness professional</h4>
                    <h1>teke control of your health</h1>
                    <div class="rule"></div>
                    <p>Curabitur non molla sit amet nisl tempus convallis quis ac lectus dolor sit amet</p>
                    <button>Visit my youtube channel</button>
                    <button>buy avada today</button>
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
            color: white;
            width: 80%;
            margin: 0 auto;
                .title {
                width: 50%;
            }
                h4{
                color: red;
            }
            .rule {
                width: 40px;
                border: 2px solid yellow;
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

            }
        }
        
    }
}

</style>