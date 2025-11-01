<script>
export default {
  data() {
    return {
      name: "VueApp",
      status: "active",
    };
  },
};
</script>

<template>
  <h1>New Vue App {{ name }}</h1>
  <p v-if="status === 'active'">User is active</p>
  <p v-else-if="status === 'pending'">User is pending</p>
  <p v-else>User is inactive</p>
</template>
