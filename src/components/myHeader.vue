<template>
    <header>
        <div class="jumbo">
            <section>
                <h4>Certified fitness professional</h4>
                <h1>teke control of your health</h1>
                <p>Curabitur non molla sit amet nisl tempus convallis quis ac lectus dolor sit amet</p>
                <button>Visit my youtube channel</button>
                <button>buy avada today</button>
            </section>
            <div>
                
            </div>
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
            color: white;
            width: 80%;
            margin: 0 auto;
        }
        h4{
            color: red;
        };
    }
}




</style>