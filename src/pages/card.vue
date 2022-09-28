<template>
  <div class="text-h2">Employee List</div>
  <q-btn color="primary" icon="check" label="OK" @click="getemploy" />
</template>
<script>
import axios from "axios";

export default {
  setup() {
    async function getemploy() {
      await axios
        .get("https://jsonplaceholder.typicode.com/todos/1")
        .then((resp) => {
          console.log(resp.data);
        });
    }
    return { getemploy };
  },
};
</script>
