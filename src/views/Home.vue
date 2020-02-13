<template>
  <div class="home">
    <div class="banner"></div>
    <div class="mainContent">
    <div class="container text-center">
      <h1>Welcome to <span class="color-red">Redux FlyFF</span></h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum dolores doloremque vel molestiae exercitationem sequi nesciunt quos deleniti, rem veritatis ipsa<br> a porro unde iure laboriosam quam dolore suscipit voluptate!
      </p>
    </div>
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-md-3 rates-col">
                    <a href="#/register"></a>
                    <i class="fas fa-user-plus"></i>
                    <h1>Register</h1>
                    <p>
                        Register your web account
                    </p>
                </div>
                <div class="col-md-3 rates-col">
                    <a href="#/download"></a>
                    <i class="fas fa-download"></i>
                    <h1>Download</h1>
                    <p>
                        For the latest redux client
                    </p>
                </div>
                <div class="col-md-3 rates-col">
                    <a href="https://discord.gg/9rQBMx2" target="_blank"></a>
                    <i class="fab fa-discord"></i>
                    <h1>Community</h1>
                    <p>
                        Join the community discussions
                    </p>
                </div>
            </div>
        </div>
      <div class="container mt-5">
        <div class="row">
          <div class="col-12">
              <div class="row no-gutters align-items-center">
                  <div class="col-8">
                      <h1 class="mb-0"><i class="fas fa-bullhorn pr-1"></i> News & <span class="color-red">Events</span></h1>
                      <p>Keep up with our latest patches and events</p>
                  </div>
                  <div class="col-4 text-right">
                      <i class="fas fa-arrow-circle-left"></i><i class="fas fa-arrow-circle-right"></i>
                  </div>
                  <div class="border-div"></div>
              </div>
          </div>
          <div class="col-md-4">
             <PatchNotes 
                patchTitle="Patch Note v2.3.1" 
                patchDesc="Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis iure explicabo quasi magnam architecto assumenda porro, nisi sit dolor animi labore minima ipsum? Reprehenderit perspiciatis voluptatum iusto debitis eos officia?" 
                patchDate="20-03-2020"
                patchFlagTitle="Hotfix"/>
          </div>
          <div class="col-md-4">
             <PatchNotes 
                patchTitle="Patch Note v2.3.1" 
                patchDesc="Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis iure explicabo quasi magnam architecto assumenda porro, nisi sit dolor animi labore minima ipsum? Reprehenderit perspiciatis voluptatum iusto debitis eos officia?" 
                patchDate="20-03-2020"
                patchFlagTitle="Hotfix"/>
          </div>
          <div class="col-md-4">
             <PatchNotes 
                patchTitle="Patch Note v2.3.1" 
                patchDesc="Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis iure explicabo quasi magnam architecto assumenda porro, nisi sit dolor animi labore minima ipsum? Reprehenderit perspiciatis voluptatum iusto debitis eos officia?" 
                patchDate="20-03-2020"
                patchFlagTitle="Hotfix"/>
          </div>
        </div>
      </div>

      <div class="rankings margin-top">
          <div class="container pt-md-3">
                <div class="row align-items-center justify-content-center">
                    <div class="col-xl-5 text-center siege-title">
                        <i class="fas fa-dragon"></i>
                        <h1 class="m-0">Guild <b class="color-red">Siege</b></h1>
                        <p>Are you ready to challenge the best?</p>
                    </div>
                    <div class="col-md-3 col-xl-2 offset-xl-1 text-center siege-date">
                        <div class="siege-content">
                            <i class="fas fa-shield-alt"></i>
                            <h1>Unranked</h1>
                            <p><b>MON</b> ( 9:00pm DST )</p>
                        </div>
                    </div>
                    <div class="col-md-3 col-xl-2 text-center siege-date">
                        <div class="siege-content">
                            <i class="fas fa-shield-alt"></i>
                            <h1>Unranked</h1>
                            <p><b>WED</b> ( 5:00pm DST )</p>
                        </div>
                    </div>
                    <div class="col-md-3 col-xl-2 text-center siege-date">
                        <div class="siege-content">
                            <i class="fas fa-shield-alt"></i>
                            <h1>Ranked</h1>
                            <p><b>SAT</b> ( 5:00pm DST )</p>
                        </div>
                    </div>
                </div>
              <div class="row justify-content-xl-end justify-content-center pt-md-4">
                  <div class="col-lg-4 siege-rank">
                      <div class="row testimage">
                          <div class="col-7">
                              <i class="fas fa-crown" style="color: #ffd700;"></i>
                              <h1 class="m-0">Vista</h1>
                                <p>MVP</p>
                                <p class="mb-0"><b>Kills:</b> 24<br>
                                <b>Points:</b> 132<br>
                                <b>Guild:</b> NunChukz
                                </p>
                          </div>
                          <div class="col-5">
                          </div>
                      </div> 
                  </div>
                  <div class="col-md-5 col-lg-3 siege-rank">
                      <div class="row align-items-center">
                          <div class="col-8">
                            <i class="fas fa-trophy" style="color: #ffd700;"></i>
                            <h1>Poggerz</h1>
                            <p>Winning Guild</p>
                            <p class="mb-0">
                            <b>Points:</b> 132<br>
                            <b>Leader:</b> Picklez<br>
                            </p>
                          </div>
                          <div class="col-4">
                              <img src="../assets/images/banner.png">
                          </div>
                      </div>
                  </div>
                  <div class="col-md-5 col-lg-3 siege-rank">
                      <div class="row align-items-center">
                          <div class="col-8">
                            <i class="fas fa-award" style="color: silver;"></i>
                            <h1>BobRoss</h1>
                            <p># 2</p>
                            <p class="mb-0">
                            <b>Points:</b> 109<br>
                            <b>Leader:</b> Squidward<br>
                            </p>
                          </div>
                          <div class="col-4">
                              <img src="../assets/images/banner.png">
                          </div>
                      </div>
                  </div>
              </div>
          </div>
           <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none">
           <polygon fill="white" points="0,100 100,0 100,100"/>
           </svg>
      </div>

      <div class="container margin-top pt-5">
          <h1 class="mb-1"><i class="fas fa-scroll"></i> Rules & <span class="color-red">Regulations</span></h1>
          <p>
              Please familiarize yourself with these rules
          </p>
          <div class="border-div"></div>

          <div class="row">
              <div class="col-md-6">
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. At optio in autem quasi officiis repellendus modi excepturi expedita, cumque dolorum, illo, ipsam ipsa. Nisi voluptas mollitia commodi ratione iste temporibus dolore ullam pariatur? Alias minus eum excepturi, aspernatur perferendis ullam expedita, reprehenderit ex odio eligendi molestiae voluptate? Reprehenderit, error. Tempore!
                </p>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. At optio in autem quasi officiis repellendus modi excepturi expedita, cumque dolorum, illo, ipsam ipsa. Nisi voluptas mollitia commodi ratione iste temporibus dolore ullam pariatur? Alias minus eum excepturi, aspernatur perferendis ullam expedita, reprehenderit ex odio eligendi molestiae voluptate? Reprehenderit, error. Tempore!
                </p>
              </div>
              <div class="col-md-6">
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. At optio in autem quasi officiis repellendus modi excepturi expedita, cumque dolorum, illo, ipsam ipsa. Nisi voluptas mollitia commodi ratione iste temporibus dolore ullam pariatur? Alias minus eum excepturi, aspernatur perferendis ullam expedita, reprehenderit ex odio eligendi molestiae voluptate? Reprehenderit, error. Tempore!
                </p>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. At optio in autem quasi officiis repellendus modi excepturi expedita, cumque dolorum, illo, ipsam ipsa. Nisi voluptas mollitia commodi ratione iste temporibus dolore ullam pariatur? Alias minus eum excepturi, aspernatur perferendis ullam expedita, reprehenderit ex odio eligendi molestiae voluptate? Reprehenderit, error. Tempore!
                </p>
              </div>
          </div>
          
      </div>

     


    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import PatchNotes from '@/components/patchnotes.vue'
import Login from '@/components/login-sidebar.vue'

export default {
  name: 'Home',
  components: {
    PatchNotes,
    Login
  }
}
</script>

<style lang="scss" scope>

svg {
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 250px;
  z-index: 3;
  /* set height to pixels if you want angle to change with screen width */
}
p {
  color: #858585;
}

.margin-top {
    margin-top: 5rem;
}

.rankings {
    background-color: rgba(0,0,0,.03);
    position: relative;
    padding: 3rem 0;

    border-top: 1px solid rgba(0, 0, 0, 0.15);

    .container {
        position: relative;
        z-index: 5;
    }

    &:after {
        position: absolute;
        content: " ";
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;

        background-image: url('../assets/images/upresia.jpg');
        background-size: cover;
        background-position: center;
        background-blend-mode: multiply;
        opacity: 0.165;

    }
    .siege-title {
        .fas {
            font-size: 4rem;
            margin-bottom: 1rem;
        }
        h1 {
            font-size: 40px;
        }
        p {
            font-size: 20px;
        }
    }

    .siege-date {
        background-color: white;
        border-radius: 8px;
        margin: 1rem;
        padding: 1rem;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.05), 0 6px 20px 0 rgba(0, 0, 0, 0.05);
        position: relative;


        b {
            color: rgb(217,43, 46);
        }

        p {
            font-weight: 600;
            font-size: 11px;
        }

        .fas {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
    }

    .siege-rank {
        background-color: white;
        border-radius: 8px;
        margin: 2rem 2rem;
        padding: 2rem;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.05), 0 6px 20px 0 rgba(0, 0, 0, 0.05);
    
        .fas {
            font-size: 1.5rem;
        }

        .testimage {
            background-image: url('../assets/images/billposter_background.jpg');
            background-size: cover;
            background-position: center left;
        }
    }
}

  /* Large desktop */
  @media (min-width: 1200px) {
      
  }

  /* Desktop */
  @media (min-width: 992px) and (max-width: 1199px) {
        .rankings {
                .siege-rank {
                        margin: 1rem 1rem;
                    }
            }
  }

  /* Portrait tablet to landscape and desktop */
  @media (min-width: 768px) and (max-width: 991px) {
      .rankings {
        .siege-rank {
                margin: 1rem 1rem;
            }
      }
  }

  /* Landscape phone to portrait tablet */
  @media (max-width: 767px) {
    .rankings {
        .siege-rank {
                margin: 1rem 1rem;
            }
      }  
  }


    .rates-col {
        margin: 2rem;
        padding: 2rem;
        text-align: center;
        border-radius: 5px;
        box-shadow: 0 0 10px 0 rgba(153, 170, 181, 0.2);

        &:hover {
            color: rgb(217,43, 46);;
            transition: 200ms ease-in-out;
        }

        a {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
        }

        .fas {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        .fab {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
    }

    .fa-arrow-circle-left {
        font-size: 2rem;
        &:hover {
            color: rgb(217,43, 46);
            transition: 200ms ease-in-out;
        }

    }
    .fa-arrow-circle-right {
        font-size: 2rem;
        margin-left: 0.5rem;
        &:hover {
            color: rgb(217,43, 46);
            transition: 200ms ease-in-out;
        }
    }

    /* Large desktop */
    @media (min-width: 1200px) {
        .container {
            max-width: 1350px;
        }
    }

    /* Desktop */
    @media (min-width: 992px) and (max-width: 1199px) {

        .rates-col {
            margin: 1rem;
        }
    }

    /* Portrait tablet to landscape and desktop */
    @media (min-width: 768px) and (max-width: 991px) {
        .rates-col {
            margin: 1rem;
        }
    }

    /* Landscape phone to portrait tablet */
    @media (max-width: 767px) {
        .rates-col {
            margin: 1rem;
        }
    }


</style>
