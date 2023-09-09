<template>
  <v-container>
    <v-row no-gutters class="text-center">
      <v-col cols="12" md="4">
        <v-img style="border-radius: 20%;"
          src="https://avatars.githubusercontent.com/u/38020318?v=1"
          class="my-3 imagem-redonda"
          contain
          height="300"
        />
      <h1 class="display-2 font-weight-bold mb-3">
         Nelson Marques
      </h1>

      💻Desenvolvedor Front-End.<br>
      📚 Análise e Desenvolvimento de Sistemas Estácio<br>

      </v-col>

  
      <v-col col="8" class="pt-12">

  

   
  <div>
    <a href="https://github.com/nelson-ti"></a>
    <img height="150em" src="https://github-readme-stats.vercel.app/api?username=Nelson-ti&show_icons=true&theme=dark"/>
    <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nelson-ti&layout=compact&langs_count=7&theme=dark"/>
  </div>


    <div style="display: inline_block"><br>
      <img align="center" alt="Lamas-vuejs" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original-wordmark.svg" />      
      <img align="center" alt="Lamas-vuetify" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuetify/vuetify-original.svg" />
      <img align="center" alt="Lamas-html5" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain-wordmark.svg" />
      <img align="center" alt="Lamas-css" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain-wordmark.svg" />
      <img align="center" alt="Lamas-js" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />       
      <img align="center" alt="Lamas-typescript" height="40" width="60" src= "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" />
      <img align="center" alt="Lamas-csharp" height="40" width="60" src="https://www.cdnlogo.com/logos/c/27/c.svg" />   
    <img align="center" alt="Lamas-Git" height="40" width="60" src= "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
    </div>

    <br>
    <br>
    
      <div> 
        <a href="https://www.linkedin.com/in/nelson-marques-5764a5191/" target="_blank">
        <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
        <a href="https://t.me/Nelsontaveira" target="_blank">
        <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" target="_blank"></a> 
        <a href="https://wa.me/5521966210600" target="_blank">
        <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a> 
        <a href="https://www.instagram.com/1nelsonmarques/" target="_blank">
        <img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
        <a href = "mailto:nelson.taveira.ti@gmail.com">
        <img src="https://img.shields.io/badge/-Hotmail-%23333?style=for-the-badge&logo=hotmail&logoColor=white" target="_blank"></a>
      </div>   
      </v-col>     
    </v-row>
  </v-container>
</template>

<script lang="ts">
  import Vue from 'vue'

  export default Vue.extend({
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  })
</script>
<style>
  .imagem-redonda {
    max-width: 100%; /* Defina o tamanho máximo */
    border-radius: 50%;
    overflow: hidden;
  }
</style>
