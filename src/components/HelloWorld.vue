<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="greetings">
    <h1 class="text-success">{{ msg }}</h1>
    <p>"Sesungguhnya Al Quran ini memberikan petunjuk kepada (jalan) yang lebih lurus dan memberi kabar gembira kepada orang-orang mu’min yang mengerjakan amal saleh bahwa bagi mereka ada pahala yang besar.” (QS. Al Isra : 9)</p>
  </div>
</template>
