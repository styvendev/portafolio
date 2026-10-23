<script lang="ts" setup>
import IconMail from '~icons/lucide/mail'
import IconTrash from '~icons/lucide/trash'
</script>

<template>
  <section class="flex flex-col items-center colorGray p-8">
    <h2 class="text-3xl font-bold my-4">Contáctanos</h2>
    <form method="post" class="flex flex-col gap-4 w-full my-4 text-lg md:w-1/2">
      <label for="name" class="flex flex-col group">
        <span class="p-2 rounded-xl text-gray-500 group-focus-within:text-blue-400">Nombre</span>
        <input type="text" name="name" id="name" class="border-2 rounded-xl p-2 border-gray-200 bg-gray-50 outline-none focus:border-blue-400 focus:bg-blue-50"/>
      </label>
      <label for="lastname" class="flex flex-col group">
        <span class="p-2 rounded-xl text-gray-500 group-focus-within:text-blue-400">Apellido</span>
        <input type="text" name="lastname" id="lastname" class="border-2 rounded-xl p-2 border-gray-200 bg-gray-50 outline-none focus:border-blue-400 focus:bg-blue-50"/>
      </label>

      <label for="email" class="flex flex-col group">
        <span class="p-2 rounded-xl text-gray-500 group-focus-within:text-blue-400">Email</span>
        <input type="email" name="email" id="email" class="border-2 rounded-xl p-2 border-gray-200 bg-gray-50 outline-none focus:border-blue-400 focus:bg-blue-50"/>
      </label>
      <label for="phone" class="flex flex-col group">
        <span class="p-2 rounded-xl text-gray-500 group-focus-within:text-blue-400">Teléfono</span>
        <input type="tel" name="phone" id="phone" class="border-2 rounded-xl p-2 border-gray-200 bg-gray-50 outline-none focus:border-blue-400 focus:bg-blue-50"/>
      </label>
      <label for="message" class="flex flex-col group">
        <span class="p-2 rounded-xl text-gray-500 group-focus-within:text-blue-400">Mensaje</span>
        <textarea name="message" id="message" class="border-2 rounded-xl p-2 border-gray-200 bg-gray-50 outline-none focus:border-blue-400 focus:bg-blue-50"></textarea>
      </label>
      <div class="w-full md:flex md:flex-row gap-2">
        <button type="submit" class="flex flex-row w-full justify-center my-4 gap-2 font-bold border-none rounded-xl p-2 bg-blue-100 text-white hover:bg-blue-300 active:bg-blue-400">
          <span class="">Enviar</span>
          <IconMail class="m-1"/>
        </button>
        <button type="submit" class="flex flex-row w-full justify-center my-4 gap-2 font-bold border-none rounded-xl p-2 bg-red-100 text-white hover:bg-red-300 active:bg-red-400">
          <span class="">Vaciar</span>
          <IconTrash class="m-1"/>
        </button>
      </div>

    </form>
  </section>
</template>
