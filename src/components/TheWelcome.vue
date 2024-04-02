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
    <template #heading>Pendidikan</template>
SD AL-AZHAR SYIFA BUDI PEKANBARU<br>
SMP NEGERI 5 PEKANBARU<br>
SMA NEGERI 9 PEKANBARU<br>
TEKNIK INFORMATIKA UNIVERSITAS ISLAM RIAU
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Specialist</template>
    Software Engineer
    memahami cara-cara pengembangan peranti lunak termasuk pembuatan, pemeliharaan, manajemen organisasi pengembangan peranti lunak dan manajemen mutu.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>
Olahraga(Futsal, badminton, berenang, jogging)<br>
Bermain Game<br>
Nonton<br>
Mendengar Musik
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>
Tergabung dalam komunitas:
<ul>
  <li>Teknik Informatika</li>
  <li>Data Analyst Indonesia</li>
  <li>UI/UX Designer Indonesia</li>
</ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Status</template>

    Single (jomblo)
  </WelcomeItem>
</template>