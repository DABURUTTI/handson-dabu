<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/cps_logo.png')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">Welcome to IWAI-LAB</h1>

        <p class="subheading font-weight-regular">
          岩井研へようこそ！
          <br />今回はWEB制作のハンズオンを行います
        </p>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
    model: 0,
    pics: ["download.jpeg", "access_01.jpeg"],
  }),
};
</script>
