<script lang="ts" setup>
import IconHtml5 from '~icons/simple-icons/html5'
import IconCss3 from '~icons/simple-icons/css3'
import IconTailwindcss from '~icons/simple-icons/tailwindcss'
import IconBootstrap from '~icons/simple-icons/bootstrap'
import IconNode from '~icons/simple-icons/nodedotjs'
import IconTypescript from '~icons/simple-icons/typescript'
import IconJavascript from '~icons/simple-icons/javascript'
import IconFigma from '~icons/simple-icons/figma'
import IconVuedotjs from '~icons/simple-icons/vuedotjs'
import IconReact from '~icons/simple-icons/react'
import IconDocker from '~icons/simple-icons/docker'
import IconPostman from '~icons/simple-icons/postman'
import IconGit from '~icons/simple-icons/git'
import IconGithub from '~icons/simple-icons/github'
</script>

<template>
  <section class="md:px-8 py-6 colorGray flex flex-col items-center">
    <h2 class="font-bold text-center text-2xl p-4">Herramientas</h2>
    <div class="flex overflow-x-auto scrollbar-none justify-evenly gap-14 md:gap-20 py-6 mx-8 lg:w-3/4">
      <div>
        <IconHtml5 class="hover:text-[#E34F26] text-4xl" />
      </div>
      <div>
        <IconCss3 class="hover:text-[#663399] text-4xl" />
      </div>
      <div>
        <IconTailwindcss class="hover:text-[#06B6D4] text-4xl" />
      </div>
      <div>
        <IconBootstrap class="hover:text-[#7952B3] text-4xl" />
      </div>
      <div>
        <IconNode class="hover:text-[#5FA04E] text-4xl" />
      </div>
      <div>
        <IconJavascript class="hover:text-[#F7DF1E] text-4xl" />
      </div>
      <div>
        <IconTypescript class="hover:text-[#3178C6] text-4xl" />
      </div>
      <div>
        <IconFigma class="hover:text-[#F24E1E] text-4xl" />
      </div>
      <div>
        <IconVuedotjs class="hover:text-[#4FC08D] text-4xl" />
      </div>
      <div>
        <IconReact class="hover:text-[#61DAFB] text-4xl" />
      </div>
      <div>
        <IconDocker class="hover:text-[#2496ED] text-4xl" />
      </div>
      <div>
        <IconPostman class="hover:text-[#FF6C37] text-4xl" />
      </div>
      <div>
        <IconGit class="hover:text-[#F03C2E] text-4xl" />
      </div>
      <div>
        <IconGithub class="hover:text-[#181717] text-4xl" />
      </div>
    </div>
  </section>
</template>
