<template>
  <div
    class="q-ml-xl text-weight-bold q-mt-md text-grey-4 text-h2"
  >
    Post data
  </div>
  <div class="bg-grey-9 q-pa-xl" style="max-width: 300px">
    <q-input
      class="text-white"
      color="black"
      width="300px"
      v-model="posts.company"
      type="text"
      label="CompanyName"
    ></q-input>
    <q-input
      class="text-white q-mt-lg"
      color="black"
      width="300px"
      v-model="posts.name"
      type="text"
      label="UserName"
    />
    <q-input
      class="text-white"
      color="black"
      width="300px"
      v-model="posts.password"
      type="password"
      label="password"
    />
  </div>
</template>
<script>
import { ref } from "vue";
export default {
  setup() {
    const posts = ref({
      company: null,
      name: null,
      password: null,
    });
    return { posts };
  },
};
</script>
