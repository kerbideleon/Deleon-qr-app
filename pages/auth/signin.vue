<template>
    <div class="d-flex align-center justify-center" style="height: 100vh;">
    <v-card width="500">
  <v-form>
    <h1> LOGIN PAGE</h1>
    <v-text-field

      v-model="name"
      label="Email"
    ></v-text-field>

    <v-text-field
      label="password"
    ></v-text-field>

    <v-btn block>
    Sign in
    </v-btn>

  </v-form>
  </v-card>
  </div>
</template>
<script>
export default {
    layout: "auth"
}
</script>