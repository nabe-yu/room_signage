<template>
  <section>
    <div class="columns">
      <div class="column is-5 has-background-dark">
        <RoomState />
        <Schedule />
      </div>
      <div class="column is-7 has-background-white">
        <Clock class="has-text-centered" />
        <p class="title">
          Next Meeting
        </p>
        <Schedule />
        <Schedule />
        <Schedule />
        <Schedule />
        <Schedule />
      </div>
    </div>
  </section>
</template>

<script>
// export default {
//   async asyncData ({ $axios }) {
//     return {
//       questionnaires: await $axios.$get('http://localhost:3301/questionnaires')
//     }
//   }
// }
</script>
