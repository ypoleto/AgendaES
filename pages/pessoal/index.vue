<template>
  <div class="bg-gray-100">
    <Navbar />
    <Calendario />
  </div>
</template>
<script>
import Navbar from "../components/navbar/index.vue";
import Calendario from "../calendarioSemanal/index.vue";
export default {
  components: { Navbar, Calendario },
};
</script>
