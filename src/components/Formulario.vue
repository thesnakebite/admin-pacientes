<script setup>

</script>

<template>
    <div class="md:w-1/2">
        <h2 class="font-black text-3xl text-center">Seguimiento Pacientes</h2>

        <p class="text-lg mt-5 text-center mb-10">
            Añade Pacientes y
            <span class="text-indigo-600 font-bold">Adminístralos</span>
        </p>

        <form class="bg-white shadow-md rounded-lg py-10 px-5 mb-10">
            <div class="mb-5">
                <label for="mascota" 
                       class="block text-gray"
                >
                    Nombre mascota
                </label>
                <input class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                       id="mascota"
                       name=""
                       type="text"
                       placeholder="Nombre de la mascota" 
                />
            </div>
            <div class="mb-5">
                <label for="propietario" 
                       class="block text-gray"
                >
                    Nombre del propietario
                </label>
                <input class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                       id="propietario"
                       name=""
                       type="text"
                       placeholder="Nombre del propietario" 
                />
            </div>
            <div class="mb-5">
                <label for="email" 
                       class="block text-gray"
                >
                    E-mail
                </label>
                <input class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                       id="email"
                       name=""
                       type="email"
                       placeholder="E-mail del propietario" 
                />
            </div>
            <div class="mb-5">
                <label for="alta" 
                       class="block text-gray"
                >
                Alta
                </label>
                <input class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                       id="alta"
                       name=""
                       type="date" 
                />
            </div>
            <div class="mb-5">
                <label for="sintomas" 
                       class="block text-gray"
                >
                Alta
                </label>
                <textarea class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md h-40"
                          id="sintomas"
                          name=""
                />
            </div>

            <input type="submit" 
                   class="bg-indigo-600 w-full p-3 text-white uppercase font-bold hover:bg-indigo-700 cursor-pointer transition-colors" 
                   value="Registrar paciente" 
            />

        </form>
        
    </div>
</template>

<style scoped>

</style>
