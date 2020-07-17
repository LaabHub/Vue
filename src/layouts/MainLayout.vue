<template>
    <div>
  <div class="app-main-layout">
    <Navbar/>
    <Sidebar/>

    <main class="app-content">
      <div class="app-page">
          <router-view />
      </div>
    </main>
</div>
</div>
</template>

<script>
import Navbar from '@/components/Navbar'
import Sidebar from '@/components/Sidebar'

export default {
    name: 'main-layout',
    components: {
        Navbar,Sidebar 
    }
}
</script>