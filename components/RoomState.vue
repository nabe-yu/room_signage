<template>
  <section>
    <b-field>
      <b-switch v-model="inUse" type="is-success" size="is-large" />
    </b-field>
    <p v-if="inUse">
      使用中
    </p>
    <p v-else>
      空室
    </p>
    <!-- <button @click="switchState">ボタン</button> -->
  </section>
</template>

<script>
export default {
  data() {
    return {
      inUse: false
    }
  },
  mounted() {},
  methods: {}
}
</script>
