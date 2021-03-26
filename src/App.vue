<template>
  <div id="app">
    <Index msg=''/>
    <Section/>
    <Team/>
    <PacketPremium/>
    <Footer/>
    <Style/>
    
  </div>
</template>

<script>
import Index from './components/Index.vue'
import Section from './components/Section.vue'
import Team from './components/Team.vue'
import PacketPremium from './components/PacketPremium.vue'
import Footer from './components/Footer.vue'
import Style from './components/Style.css'



export default {
  name: 'App',
  components: {
    Index,
    Section,
    Team,
    PacketPremium,
    Footer,
    Style
  }
}
</script>