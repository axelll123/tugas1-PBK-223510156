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
    Saat ini, saya tengah meniti perjalanan pendidikan sebagai mahasiswa di Universitas Islam Riau yang terletak di Jalan Kaharuddin Nst, Pekanbaru. Saat ini, saya telah mencapai semester 4 dan dengan penuh semangat menjalani studi dalam bidang Teknik Informatika di institusi tersebut







    Sebelumnya, saya bersekolah di Sekolah Menengah Atas
    <a href="https://sman1siak.sch.id/" target="_blank" rel="noopener">SMAN 1 Siak</a>
    Saya Tinggal Di Benteng Hulu, Kec. Siak Kabupaten Siak Provinsi Riau
  </WelcomeItem>
  <hr />

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Sekilas Tentang TI</template>
    Saya memilih Program Studi Teknik Informatika (S1) karena saya merasa tertarik untuk mendalami aspek-aspek teknologi yang menarik. Bergabung dalam kelas D angkatan 2022, saya mendapati bahwa di lingkungan kelas ini, saya memiliki banyak teman sekelas yang juga memiliki semangat yang tinggi untuk belajar dan tumbuh bersama.







  

    <br />

  </WelcomeItem>
  <hr/>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hobi</template>
    <li>Musik</li>
    <li>Gitar</li>
    <li>Bass</li>
    <li>Drum</li>
      
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
    
      <ToolingIcon />
    </template>
    <template #heading>Skill</template>
<ul>
   <li> 1. Manajemen waktu </li>
  <li> 2. Interpersonal</li>
<li> 3. Analitis </li>
<li> 4. Komunikasi </li>
<li> 5. Kepemimpinan</li>
  </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Person</template>

    Email: raindrairawan@student.uir.ac.id <br>
    Instagram : <a href="https://www.instagram.com/raindra_irawan" target="_blank">raindra_irawan</a>
     <br>
   
    
  </WelcomeItem>
</template>
