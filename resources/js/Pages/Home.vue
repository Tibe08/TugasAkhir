<template>
  <div class="q-pa-md" >
    <q-layout style="height: 400px" class=" shadow-2 rounded-borders">
      <q-header reveal elevated>
        <q-toolbar class="bg-yellow" style="height: 35px bg-white q-ma-md rounded-borders"  type="search">
                <q-input >
            <template v-slot:append>
            <q-icon name="search" />
            </template>
      </q-input>
      
          <q-toolbar-title >Freelance</q-toolbar-title>

        </q-toolbar>
      </q-header>

      <q-page-container>
        <q-page class="">
          Find & Hire Freelance
        <q-img src="img/pekerjaan_freelance.png" />
    
        </q-page>
      </q-page-container>
    </q-layout>
  </div>

</template>

<!-- <script>
import layoutVue "../Pages/Layout/layout.vue"
</script> -->