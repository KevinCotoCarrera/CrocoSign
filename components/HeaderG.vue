<template>
  <div >
    
    <div class="w-full p-5 flex justify-around z-50">
      <span id="brand" class="text-2xl font-bold">Crocosign</span>
      <ul class="flex justify-end gap-4 text-gray-600 nav" style="line-height: 32px;">
          <li class="links hidden sm:inline"><a href="#team">Team</a></li>
          <li class="links hidden sm:inline"><a href="#about">Acerca de Nosotrosa</a></li>
          <li>
            <v-btn class="-mt-1 btn links"
            small
            elevation="2"
            outlined
            color="teal"
            >
              Contactanós
            </v-btn></li>
      </ul>
    </div>
    <div class="hero-section flex px-2 md:px-10 lg:px-20 xl:px-52 mt-20">
      <div class="flex flex-col gap-4">
      <h1 class="hero-text text-4xl font-bold">
        Creamos diseños que <span class="block"> resaltan tu marca,</span> <span class="block"> y te hacen inolvidable</span>
       </h1>
        <p class="text-gray-400">
          Somos un equipo de jovenes diseñadores con <span class="block"> grandes sueños</span>
        </p>
        <v-btn class="w-36"
        elevation="5"
        color="#7ae989"
      >
      Contratanós 
      </v-btn>
      </div>
      <img src="../static/img-header.jpg" class="hero-image w-64 hidden md:inline sm:w-80 lg:w-96 rounded-sm shadow-lg">
    </div>
   <div class="flex gap-5 px-10">
          
     </div>
  </div>
</template>
<script>

export default {
 
   
  }
  

</script>


<style scoped>
 #brand{
  background-image: linear-gradient(120deg, #d1ff67 0%, #7ae989 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>