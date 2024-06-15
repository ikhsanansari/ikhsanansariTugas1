<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Introduction</template>

    
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    Perkenalkan nama saya ikhsan ansari kelas 4G NPM 223510216
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Penididkan</template>

    <ul>
      <li>SD : SDN 025 Sekeladi</li>
      <li>MTS : Darut Taqwa</li>
      <li>SMK : Pembangunan</li>
    </ul>
   

    <br />

   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>

    Hobi saya :
    <ul>
        <li>Tenis Meja</li>
        <li>Game</li>
    </ul>
   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sosial Media</template>
instagram
    <a href="https://www.instagram.com/ikhsan_ansari/" target="_blank" rel="noopener">Instagram</a>,Facebook
    <a href="https://www.facebook.com/ikhsan.ansari.9" target="_blank" rel="noopener">Facebook</a>,Twitter
    <a href="https://twitter.com/ikhsan_ansari" target="_blank" rel="noopener">Twitter</a>,
   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Quotes</template>

    Tetap semangat dikala terjangan masalah yang tak berhujung.
    
  </WelcomeItem>
</template>
