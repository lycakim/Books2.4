<template>
  <div>
    <div>OOPS!</div>
    <div>
      <div>404 - PAGE COULD NOT BE FOUND</div>
      <v-btn
        @click="redirectTo()"
        rounded="xl"
        size="x-large"
        class="elevation-12"
        color="#519043"
        >go back to homepage</v-btn
      >
    </div>
  </div>
</template>
            <script>
export default {
  name: "PageNotFound",
  methods: {
    redirectTo() {
      this.$router.push("/");
    },
  },
};
</script>
            <style scoped>
.container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -100%);
}
.oops {
  position: relative;
  width: 50%;
  font-size: 15rem;
  text-align: center;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  margin: auto;
}

._404 {
  width: 50%;
  display: grid;
  font-size: 20px;
  text-align: center;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  margin: auto;
}
</style>
                        