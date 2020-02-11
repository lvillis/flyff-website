<template>
  <div class="home">
    <div class="banner"></div>

    <div class="mainContent">
      <div class="container">
        <div class="row">
          <div class="col-md-7 order-2 order-md-1">
             <PatchNotes 
                patchTitle="Patch Note v2.3.1" 
                patchDesc="Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis iure explicabo quasi magnam architecto assumenda porro, nisi sit dolor animi labore minima ipsum? Reprehenderit perspiciatis voluptatum iusto debitis eos officia?" 
                patchDate="20-03-2020"/>

              <PatchNotes 
                patchTitle="Patch Note v2.2.1" 
                patchDesc="Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis iure explicabo quasi magnam architecto assumenda porro, nisi sit dolor animi labore minima ipsum? Reprehenderit perspiciatis voluptatum iusto debitis eos officia?" 
                patchDate="05-03-2020"/>  

              <PatchNotes 
                patchTitle="Patch Note v2.1.1" 
                patchDesc="Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis iure explicabo quasi magnam architecto assumenda porro, nisi sit dolor animi labore minima ipsum? Reprehenderit perspiciatis voluptatum iusto debitis eos officia?" 
                patchDate="23-02-2020"/>   
          </div>

          <div class="col-md-5 order-1 order-md-2 mb-5 mb-md-0">
            <Login></Login>
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
