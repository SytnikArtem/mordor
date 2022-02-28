<template>
  <p>{{ $t("hello") }}</p>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>

<i18n>
{
  "en": {
    "hello": "Hello"
  },
  "ua": {
    "hello": "Привiт"
  },
  "ru": {
    "hello": "Привет"
  }
}
</i18n>
