<template>
  <section class="services">
    <div class="container-services">
      <div class="team">
        <i class="far fa-clock logo"></i>
        <h3>Team traing</h3>
        <h4>Find a partner</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Velit error, ex reiciendis minus, maxime facere nesciunt voluptatibus earum praesentium aut pariatur! Quisquam modi quidem amet dicta libero porro odio ratione.</p>
        <a href="*">Find a partner <i class="fas fa-chevron-right"></i></a>
      </div>
      <div class="crossfit">
        <i class="fas fa-dumbbell logo"></i>
        <h3>crossfit workout</h3>
        <h4>Push yor limits</h4>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque vitae aut autem ab sapiente aspernatur temporibus aliquam odio, facere ex dicta, repudiandae non ipsum beatae provident repellat accusamus sint similique.</p>
        <a href="*">Learn about crossfit <i class="fas fa-chevron-right"></i></a>
      </div>
      <div class="weight">
        <i class="fas fa-fire-alt logo"></i>
        <h3>weight loss plann</h3>
        <h4>Shed those phounds</h4>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quam consectetur non sequi alias est debitis cumque expedita aliquid voluptas eveniet quibusdam molestias quae, natus officia in similique reprehenderit? Assumenda, quia!</p>
        <a href="*">LSchedule a workout <i class="fas fa-chevron-right"></i></a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'services',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.services {
  background: black;
  height: 400px;
  
  color: white;
  .container-services {
    display: flex;
    width: 80%;
    margin: 0 auto;
  }
  .team, .crossfit, .weight {
    width: calc(100% / 3 - 20px);
    min-height: 300px;
    margin: 50px 10px;
    border: 2px solid rgba(18, 18, 170, 0.918);
    border-radius: 5px;
    text-align: center;
    padding: 40px
  }
  .logo {
      font-size: 40px;
    }
}

</style>
