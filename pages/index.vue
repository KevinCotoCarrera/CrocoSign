<template>
  <div id="app" class="text-gray-700">
    <HeaderG/>
    <FeaturesG/>
    <TeamG/>
    <FormG/>
  </div>
</template>
<script>
export default {
   mounted() {
    this.animateOnScroll()
},

   methods: {
     animateOnScroll(){
     const timeline = this.$gsap.timeline({default: {duration : 1.2}})
     timeline
        .from('#brand', {y: '70px' , ease: 'bounce'})
        .from('.links',{ opacity : 0 , ease: 'bounce'})
        .from('.hero-section', {y: '70px' , ease: 'bounce',delay: 0.1})
        .from('.hero-image', {x: '70px' , ease: 'ease', delay: 0.3,})
     
        }}}
  
      

   

</script>
<style scoped>

  

</style>