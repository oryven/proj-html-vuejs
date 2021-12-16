<template>
  <footer>
    <section class="container-footer">
        <div class="social">
            <img src="../assets/img/logo.png" alt="">
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aperiam reprehenderit dignissimos cupiditate sunt fuga, obcaecati a ratione sed voluptas quia corrupti? Saepe fugit</p>
            <span><i class="fab fa-facebook-f"></i></span>
            <span><i class="fab fa-twitter"></i></span>
            <span><i class="fab fa-youtube"></i></span>
            <span><i class="fab fa-instagram"></i></span>
            <span><i class="fab fa-linkedin-in"></i></span>
        </div>
        <div class="menu-footer">
            <h4>RECENT POST</h4>
            <ul>
                <li v-for="link, i in linksFooter" :key="i"><i class="fas fa-chevron-right"></i><a href="">{{link.text}}</a></li>
            </ul>
        </div>
        <div class="contacts">
            <h4>CONTACT INFORMATIONS</h4>
            <div class="address">4746 tipple road Michigan 48449</div>
            <div>Mobile: 800.000.000</div>
            <div>Email: prova@gmail.com</div>
        </div>
    </section>
    <div class="copiright">
        <div><i class="far fa-copyright"></i> Copyright 2012-2020 | Avada theme by 
        <span>ThemeFusione</span> | All rights reserved | Power by <span>WordPress</span>
        </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'myFooter',
  props: {
    linksFooter: Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
footer {
    background: black;
    color: white;
    .container-footer {
        display: flex;
        height: 300px;
        width: 80%;
        margin: 0 auto;
        text-align: center;
        padding: 50px 0 0 0;
    }
    .social, .menu-footer, .contacts {
        width: calc(100% / 3);
        a {
            text-decoration: none;
            color: white;
            margin-left: 5px;
        }
        p {
            margin: 20px 0;
        }
        .address {
            color: grey;
            margin: 20px;
        }
    }
    .social i {
        color:crimson;
        margin: 20px 5px 0 5px;
    }
    ul li {
            display: inline-block;
            list-style: none;
            margin: 10px 10px;
        }
    .copiright {
        color: grey;
        height: 100px;
        display: flex;
        justify-content: center;
        align-items: center;
        border-top: 1px solid darkgrey;
        font-size: 14px;
        span {
            color: white;
        }
    }    
}

</style>
