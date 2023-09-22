<script setup>

</script>


<template>
    <div class="md: w-1/2">
        <h2 class="font-black text-3xl text-center">Seguimiento de Pacientes </h2>

        <p class="text-lg mt-5 text-center mb-10">
          Añade Pacientes y 
          <span class="text-indigo-600 font-bold">Administralos</span>

        </p>

        <form class="bg-white shadow-md rounded-lg py-10 px-5 mb-10">

            <div class="mb-5">
                <label 
                class="block text-gray-700 uppercase font-bold"
                for="mascota">

                 Nombre Mascota
                </label>

                <input id="mascota"
                type="text"
                placeholder="Nombre de la mascota"
                class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                
                
                />

            </div>

            <div class="mb-5">
                <label 
                class="block text-gray-700 uppercase font-bold"
                for="propietario">

                 Nombre del propietario
                </label>

                <input id="propietario"
                type="text"
                placeholder="Nombre de la propietario"
                class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                
                
                />

            </div>

            <div class="mb-5">
                <label 
                class="block text-gray-700 uppercase font-bold"
                for="email">

                 Email
                </label>

                <input id="email"
                type="email"
                placeholder="Nombre de la email"
                class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                
                
                />

            </div>

            <div class="mb-5">
                <label 
                class="block text-gray-700 uppercase font-bold"
                for="alta">

                 Alta
                </label>

                <input id="alta"
                type="date"
                placeholder="Nombre de la alta"
                class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                
                
                />

            </div>


            <div class="mb-5">
                <label 
                class="block text-gray-700 uppercase font-bold"
                for="sintomas">

                 Sintomas
                </label>

                <textarea 
                id="sintomas"
                placeholder="Describe los sintomas"
                class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                
                
                />

            </div>

                        

        </form>



    </div>
</template>


