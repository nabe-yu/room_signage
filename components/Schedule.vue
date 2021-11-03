<template>
  <section>
    <p>
      {{ title }}
    </p>
    <p>
      {{ registered }}
    </p>
    <p>
      {{ start_time }}
    </p>
    <p>
      {{ end_time }}
    </p>
  </section>
</template>

<script>
export default {
  data() {
    return {
      title: 'mtg',
      registered: 'wasabi',
      start_time: '2021-11-03 15:00',
      end_time: '2021-11-03 16:00'
    }
  },
  mounted() {},
  methods: {}
}
</script>
