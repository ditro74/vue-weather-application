<template>
  <header class="header">
    <h2>Weather Application</h2>
    <p>{{ username }} 님 반갑습니다.</p>
  </header>
</template>

<script>
export default {
  name: "HeaderDisplay",
};
</script>

<style scoped>
.header {
  background: linear-gradient(15deg, #8a2387, #e94057, #f27121);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1em; /* 1em = 16px */
}
.header h2 {
  color: #fff;
}
.header p {
  font-size: 12px;
  color: #fff;
}
</style>
