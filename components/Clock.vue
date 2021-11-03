<template>
  <section>
    <p>{{ currentDate }}</p>
    <p>{{ currentTime }}</p>
  </section>
</template>

<script>
export default {
  data: () => ({
    currentTime: '',
    currentDate: ''
  }),
  mounted() {
    setInterval(this.updateTime, 1000)
  },
  methods: {
    updateTime() {
      this.currentDate = this.$dayjs().format('YYYY年MM月DD日（ddd）')
      this.currentTime = this.$dayjs().format('HH:mm ss')
    }
  }
}
</script>
