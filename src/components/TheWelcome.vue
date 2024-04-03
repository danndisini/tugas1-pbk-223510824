<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Biodata</template>
    Nama lengkap : Dany Wahyu Saputra
    <br />
    Nama panggilan : Dany
    <br />
    Tempat dan tanggal lahir : Inhil, 28 Desember 2003
    <br />
    Jenis kelamin : Laki-Laki
    <br />
    Agama : Islam
    <br />
    Golongan Darah : A
    <br />
    Kewarganegaraan : Indonesia
    <br />
    No. Telpon : 082268759079
    <br />
    Pendidikan Terakhir : SMK TARUNA MANDIRI
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Media Sosial</template>

    Facebook :<a
      href="https://web.facebook.com/dany.wahyusyahputra"
      target="_blank"
      rel="noopener"
      >Dany</a
    >
    <br />
    Instagram :<a
      href="https://www.instagram.com/danywahyusyahputra_/?hl=en"
      target="_blank"
      rel="noopener"
      >danywahyusyahputra_</a
    >
  </WelcomeItem>
</template>
