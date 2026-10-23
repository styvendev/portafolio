<script lang="ts" setup>
import IconGitHub from '~icons/simple-icons/github'
import IconLinkedin from '~icons/simple-icons/linkedin'
import IconGitLab from '~icons/simple-icons/gitlab'
import IconDiscord from '~icons/simple-icons/discord'
</script>

<template>
  <section class="md:flex md:flex-row colorGray">
    <div class="md:w-1/2 md:h-100 relative">
      <img
        src="https://res.cloudinary.com/styvendev/image/upload/v1792121414/styvendev.png"
        class="object-contain w-full md:h-100 md:absolute md:bottom-10"
      />
    </div>
    <div class="md:w-1/2 py-4 mx-4 md:h-100">
      <h1 class="text-3xl p-4 min-lg:text-5xl font-bold">STYVEN CASTRO</h1>
      <P class="text-lg px-4 md:py-2 font-bold">SOFTWARE DEVELOPER</P>
      <ul class="p-4">
        <li class="md:text-lg">Desarrollo de aplicaciones web y móviles</li>
        <li class="md:text-lg">Diseño de interfaces de usuario</li>
      </ul>
      <div class="flex flex-row p-4 gap-4">
        <a href="https://www.linkedin.com/in/styvendev/?isSelfProfile=true" class="p-2">
          <IconLinkedin class="text-2xl" />
        </a>
        <a href="https://github.com/styvendev" class="p-2">
          <IconGitHub class="text-2xl" />
        </a>
        <a href="https://gitlab.com/styvendev" class="p-2">
          <IconGitLab class="text-2xl" />
        </a>
        <a href="" class="p-2">
          <IconDiscord class="text-2xl" />
        </a>
      </div>
    </div>
  </section>
</template>
