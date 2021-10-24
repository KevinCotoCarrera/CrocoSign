<template>
     <div class=" mt-20 pb-10">
              <h2 class="text-3xl font-semibold text-center">
                Nuestros altamente calificados Diseñadores
              </h2>
                <div class="team flex flex-col md:flex-row">
                    <div class="mt-20 flex flex-col items-center">
                        <img src="../static/person1.jpg" class="w-72 h-72 rounded-md shadow-lg"/>
                        <h3 class="text-lg font-medium mt-3 text-left w-60">Marcus Stevenson</h3>
                        <span class="text-gray-600 font-light text-sm text-left w-60">Diseñador Web</span>
                        <p class="text-gray-600 text-sm w-60 h-20 mt-2">Especializado en la creación de interfaces web, más de 5 años de experiencia trabajando como Diseñador UX/UI</p>
                        <img src="../static/person2.jpg" class="w-72 h-72 mt-12 rounded-md shadow"/>
                        <h3 class="text-lg font-medium mt-3 text-left w-60">Sthepanie Larimova</h3>
                         <span class="text-gray-600 font-light text-sm text-left w-60">Diseñadora Gráfica</span>
                        <p class="text-gray-600 text-sm w-60 h-20 mt-1">Experiencia trabajando en la creación de flyers para eventos y poster con objetivo comercial, capaz de llevar una identidad visual de 0 a 100.</p>
                    </div>
                    <div class="mt-20 flex flex-col items-center ">
                        <img src="../static/person3.jpg" class="w-72 h-72 rounded-md shadow"/>
                        <h3 class="text-lg font-medium mt-3 text-left  w-60">Julia Roberts</h3>
                         <span class="text-gray-600 font-light text-sm text-left w-60">Diseñadora Mobile</span>
                        <p class="text-gray-600 text-sm w-60 h-20 mt-1">Con alto desempeñeno en Diseño Mobile, creando interfaces elegantes tanto para iOS como para Android</p>
                        <img src="../static/person4.jpg" class="w-72 h-72 mt-12 rounded-md shadow-lg"/>
                        <h3 class="text-lg font-medium mt-3 text-left  w-60">Jhonathan Michaels</h3>
                         <span class="text-gray-600 font-light text-sm text-left w-60">Diseñador Industrial</span>
                        <p class="text-gray-600 text-sm w-60 h-20 mt-1">Su campo de acción es crear los propotipos gráficos por los que se crean barras, sillas, iluminaria y toda clase de objetos de interiores.</p>
                    </div>
                   
                </div>
    </div>
</template>
<script>

export default {
    mounted(){
        this.animateTeam()
    },
    methods:{
        animateTeam(){
            this.$gsap.from('.team' ,{ scrollTrigger:{trigger:'.team' , toggleActions: 'restart none none none'} ,x: '-100px' , ease: 'bounce',})
        }
    }
}
</script>