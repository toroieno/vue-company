<template>
  <v-app>
    <v-main>
      <GetMonthTime/>
    </v-main>
  </v-app>
</template>

<script>
import GetMonthTime from '@/components/GetMonthTime.vue';

export default {
  name: 'App',
  components: {
    GetMonthTime,
  },
};
</script>
