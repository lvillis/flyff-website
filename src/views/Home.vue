<template>
  <div class="home">
    <div class="banner"></div>

    <div class="mainContent">

<div class="container text-center">
  <div class="top-line"></div>
  <h1>Welcome to <span class="color-red">Redux FlyFF</span></h1>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum dolores doloremque vel molestiae exercitationem sequi nesciunt quos deleniti, rem veritatis ipsa<br> a porro unde iure laboriosam quam dolore suscipit voluptate!
  </p>
</div>


      <div class="container">
        <div class="row">
          <div class="col-12">
            <h1 class="mb-0">News & <span class="color-red">Events</span></h1>
            <p>Keep up with our latest patches and events</p>
            <div class="border-div"></div>
          </div>
          <div class="col-md-4">
             <PatchNotes 
                patchTitle="Patch Note v2.3.1" 
                patchDesc="Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis iure explicabo quasi magnam architecto assumenda porro, nisi sit dolor animi labore minima ipsum? Reprehenderit perspiciatis voluptatum iusto debitis eos officia?" 
                patchDate="20-03-2020"/>
          </div>
          <div class="col-md-4">
             <PatchNotes 
                patchTitle="Patch Note v2.3.1" 
                patchDesc="Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis iure explicabo quasi magnam architecto assumenda porro, nisi sit dolor animi labore minima ipsum? Reprehenderit perspiciatis voluptatum iusto debitis eos officia?" 
                patchDate="20-03-2020"/>
          </div>
          <div class="col-md-4">
             <PatchNotes 
                patchTitle="Patch Note v2.3.1" 
                patchDesc="Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis iure explicabo quasi magnam architecto assumenda porro, nisi sit dolor animi labore minima ipsum? Reprehenderit perspiciatis voluptatum iusto debitis eos officia?" 
                patchDate="20-03-2020"/>
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

<style scope>
p {
  color: #858585;
}

.border-div {
  width: 15%;
  height: 1px;
  border-radius: 10px;
  background-color: rgba(30,37,52,.5); 
  margin-bottom: 2rem;
}
</style>
