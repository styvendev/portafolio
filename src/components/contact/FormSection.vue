<template>
  <section class="flex flex-col items-center">
    <form method="post" class="flex flex-col w-1/2">
      <label for="name">Nombre</label>
      <input type="text" name="name" id="name" />
      <label for="lastname">Apellido</label>
      <input type="text" name="lastname" id="lastname" />
      <label for="email">Email</label>
      <input type="email" name="email" id="email" />
      <label for="phone">Teléfono</label>
      <input type="tel" name="phone" id="phone" />
      <label for="message">Mensaje</label>
      <textarea name="message" id="message"></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>
</template>
