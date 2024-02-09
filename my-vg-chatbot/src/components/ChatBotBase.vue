<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template class="iframe">
  <div class="chat_container">
    <iframe src="https://app.stammer.ai/es/chatbot/embed/b4bfbbfe-5447-4bd9-9d80-c0bc2e74404f" width="100%" height="100vh" frameborder="0" ></iframe>
  </div>

</template>

<style scoped>
.chat_container {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 99vh;
  width: 99vw;
}
iframe{
  height: 98vh;
  width: 99vw;
}
</style>
