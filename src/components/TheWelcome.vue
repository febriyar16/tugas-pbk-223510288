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
    <template #heading>RIWAYAT PENDIDIKAN</template>
    *SDN 002 LUbuk Keranji, Pelalawan(2010-2016) <br>
    *SMPN 1 Bandar Petalangan, Pelalawan(2016-2018) <br>
    *Madrasah Aliyah Al-Qosimiah Sorek satu, pelalawan(2018-2022) <br> 
    
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>KEMAMPUAN</template>
<p>Seorang profesional yang berpengalaman di bidang ILMU TEKNOLOGI (IT) dengan 15 tahun pengalaman dalam SOFTWARE ENGINNER. Memiliki kemampuan yang kuat dalam menguasai FRAMEWORK , dengan rekam jejak yang terbukti dalam membuat aplikasi gojek & tokopedia. Saya memiliki komitmen yang kuat terhadap perkembangan teknologi, dan saya selalu berusaha untuk meningkatkan diri dan memberikan kontribusi yang maksimal di lingkungan kerja saya.</p>
    
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener"></a>
    
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"></a> 
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener"></a>
    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a>
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"
      ></a>

    <br />

     <code></code>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>PENGALAMAN KERJA</template>
  *2010-2015   GOjek sebagai Software enginner <br>
  *2015-2020   Tokopedia sebagai Software enginner
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"></a>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Media Sosial</template>
Instagram: @febriyar__
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      ></a>
    <a href="https://news.vuejs.org" target="_blank" rel="noopener"></a> 
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Kontak</template>
  febriyardarmawansyah@gmail.com / 089509085697
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>
  </WelcomeItem>
</template>
