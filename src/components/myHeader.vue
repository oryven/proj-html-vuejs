<template>
    <header>
        <div class="jumbo">
            <section>
                <h4>Certified fitness professional</h4>

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
        section {
            width: 80%;
            margin: 0 auto;
        }
        h4{
            
        };
    }
}




</style>