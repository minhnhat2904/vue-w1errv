<template>
  <div id="app">
    <span :title="message" v-if="seen">
      Rê chuột lên đây một vài giây để xem thuộc tính `title` được bind!
    </span>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'hello',
      seen: true,
    };
  },
};
</script>

<style></style>
