<template>
  <div id="app">


    <div id="nav">
      <div class="container login-container">
        <div class="row align-items-center">
          <div class="col-md-8">
            <router-link to="/" class="navlink">Home</router-link>
            <router-link to="/features" class="navlink">Features</router-link>
            <router-link to="/register" class="navlink">Register</router-link>
            <router-link to="/download" class="navlink">Download</router-link>
          </div>
          <div class="col-md-4 text-md-right">
            <span class="language">English <i class="fas fa-caret-down"></i></span>

            <button class="btn btn-primary" v-on:click="isActive = !isActive">Login</button>

            <transition name="bounce">
                <Login v-show="isActive"></Login>
            </transition>
           
          </div>
        </div>


      </div>
    </div>

     <router-view/>
      
   

    <div class="footer card-footer">
      <div class="container text-right">
        <p class="pt-2">
          Site by Vista Copyright @ 2020
        </p>
      </div>
    </div>
  </div>
</template>

<script>
  // @ is an alias to /src
  import Login from './components/login-sidebar.vue'

  export default {
    name: 'Home',
    components: {
      Login 
    },
      data() {
        return {
          isActive: false
      }
    },
      mounted() {
     var nav = document.querySelector('#nav');

      window.addEventListener('scroll', function(event) {
          event.preventDefault();

          if (window.scrollY <= 300) { 
              nav.style.backgroundColor = 'rgba(255, 255, 255, 0.4)'; 
              nav.style.padding = '20px';
          } else {
              nav.style.backgroundColor = 'rgba(255, 255, 255, 0.9)';
              nav.style.padding = '8px';
          }
      });
  }
  }
</script>

<style lang="scss" scoped>
  .bounce-enter-active {
    animation: bounce-in .5s;
  }
  .bounce-leave-active {
    animation: bounce-in .5s reverse;
  }
  @keyframes bounce-in {
    0% {
      transform: scale(0);
    }
    50% {
      transform: scale(1.1);
    }
    100% {
      transform: scale(1);
    }
  }

  .language {
    font-weight: 700;
    padding-right: 2rem;

    .fas {
      padding-left: 0.5rem;
    }
  }


  .login-container {
    #login {
      position: absolute;
      top: 80px;
      right: 0;

    }
  }

</style>