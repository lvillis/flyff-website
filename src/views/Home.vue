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
                <div class="col-3 rates-col">
                    <a href="#/register"></a>
                    <i class="fas fa-user-plus"></i>
                    <h1>Register</h1>
                    <p>
                        Register your web account
                    </p>
                </div>
                <div class="col-3 rates-col">
                    <a href="#/download"></a>
                    <i class="fas fa-download"></i>
                    <h1>Download</h1>
                    <p>
                        For the latest redux client
                    </p>
                </div>
                <div class="col-3 rates-col">
                    <a href="#/discord"></a>
                    <i class="fas fa-comments"></i>
                    <h1>Community</h1>
                    <p>
                        Join the community discussions
                    </p>
                </div>
            </div>
        </div>


      <div class="container margin-top">
        <div class="row">
          <div class="col-12">

              <div class="row no-gutters align-items-center">
                  <div class="col-8">
                      <h1 class="mb-0">News & <span class="color-red">Events</span></h1>
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
p {
  color: #858585;
}

.margin-top {
    margin-top: 5rem;
}

.border-div {
  width: 15%;
  height: 1px;
  border-radius: 10px;
  background-color: rgba(30,37,52,.5); 
  margin-bottom: 2rem;
}

    .rates-col {
        margin: 2rem;
        padding: 2rem;
        text-align: center;
        border-radius: 5px;
        box-shadow: 0 0 10px 0 rgba(153, 170, 181, 0.2);
        position: relative;

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

</style>
