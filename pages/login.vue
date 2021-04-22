<template>
  <v-container>
    <v-form>
      <v-input type="email" v-model="email" />
      <v-input type="password" v-model="password" />
    </v-form>
  </v-container>
</template>

<script>
export default {
  name: 'Login',
  layout: 'blank',
  auth: false
}
</script>

<style scoped>

</style>
