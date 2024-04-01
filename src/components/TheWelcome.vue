<script setup lang="ts">
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
    <template #heading>Tentang Saya</template>
    Saya adalah mahasiswa di kampus universitas islam riau yang berada di jalan Kaharuddin Nst
    Pekanbaru. Saat ini saya mengambil jurusan Teknik Informatika Universitas Islam Riau dan sekarang saya berada di semester 4 .
    Saya Berasal dari Batam dan kini tinggal di pekanbaru.
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Riwayat Pendidikan</template>

    SDIP YLPI <br />
    MTS IMAM IBNU KATSIR<br />
    MA IMAM IBNU KATSIR<br />
    UNIVERSITAS ISLAM RIAU 2022
  </WelcomeItem>
  <hr />a
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman</template>
    Pernah menjadi osis bagian bahasa <br />
     <br />
    <ul>
      
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
    <ul>
     
      <li>HTML</li>
      <li>PHP</li>
      <li>C++</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hubungi Saya</template>

    Instagram :<a href="https://www.instagram.com/dwiyudaa_/" target="_blank">dwiyudaa_ </a
    ><br />
    Email : dwiyuda2004@gmail.com<br />
    No HP : 082287808720
  </WelcomeItem>
</template>