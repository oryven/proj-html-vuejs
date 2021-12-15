<template>
  <section class="mailing">
    <div class="container-mail">
      <h4>Join your mailing list today</h4>
      <h2>Insider offers &amp; flash sales in your <br> inbox every week</h2>
      <div class="rule"></div>
      <div class="subscrive">
        <form class="input-mail">
          <label for="email">Insert yor email ...*</label>
          <!-- <input type="email" id="email" name="email" placeholder="Insert yor email ...*" required> -->
        </form>
        <span><button>Subscrive</button></span>
      </div>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim reprehenderit nostrum <br> voluptate eaque a doloremque, iure laudantium</p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'mailingList'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.mailing {
  margin-top: 100px;
  background-image: url("../assets/img/banner1-2x.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  height: 500px;
  .container-mail {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 80%;
    height: 100%;
    background: rgb(6, 6, 7);
    background: linear-gradient(90deg, rgba(6,6,7,1) 47%, rgba(0,0,0,0) 59%);
    margin: 0 auto;
    color: white;
    .subscrive {
      margin: 20px 0 ;
      display: flex;
    }
    .rule {
      width: 40px;
      border: 2px solid yellow;
    }
    .input-mail{
      height: 30px;
      border-radius: 20px;
      background: white;
      color:grey;
      width: 30%;
      padding: 5px;
    }
    input {
      width: 100%;
      outline: none;
    }
  }
}

</style>
