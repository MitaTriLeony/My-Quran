<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <p>
      Al Quran adalah kitab suci yang diwahyukan Allah SWT kepada Nabi Muhammad
      Saw sebagai rahmat dan petunjuk bagi manusia yang beriman dan bertakwa
      daam hidup dan kehidupannya.
    </p>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <p>
      My Qur'an adalah Al-qur'an digital online yang dilengkepi dengan
      terjemahan dalam bahasa indonesia dan juga murotal Qur'an
    </p>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <p>
      Al-Quran terdiri atas 30 juz, 114 surat, 6.236 ayat, dan 77.845 kata
    </p>
    <WelcomeItem>
      <template #icon>
        <SupportIcon />
      </template>

      <template #heading></template>

      <p>Al Quran pertama kali turun pada tanggal 17 Ramadhan saat usia Rasulullah mencapai 40 tahun (sekitar 608-609 M). Ketika Rasulullah sedang beruzlah di gua Hira (sekira 5 kilometer dari Makkah), tiba-tiba Jibril datang membawa wahyu. Jibril memeluk dan melepaskan Rasulullah SAW. Hal ini diulanginya sebanyak 3 kali.</p>
    </WelcomeItem>
  </WelcomeItem>
</template>
