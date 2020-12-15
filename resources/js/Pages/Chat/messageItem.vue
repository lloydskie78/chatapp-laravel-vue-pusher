<template>
  <div>
    <span class="font-extrabold">{{ message.user.name }}:</span> {{ message.message }}
  </div>
</template>

<script>
export default {
  props: ['message']
};
</script>