<template>
  <div class="lang">
    <ul class="lang-list">
      <li
        class="lang-list-item"
        v-for="(lang, value) in langs"
        :key="`Lang${value}`"
        v-on:click="handleClick(value)"
      >
        {{ lang }}
      </li>
    </ul>
  </div>
</template>

<script>
const LANGUAGES = {
  ua: "Укр",
  ru: "Rus",
  en: "Eng",
};

export default {
  name: "locale-changer",

  data() {
    return {
      langs: LANGUAGES,
    };
  },
  methods: {
    handleClick(lang) {
      this.$i18n.locale = lang;
    },
  },
};
</script>

<style lang="scss" scoped>
.lang {
  padding: 32px 80px 20px;
  &-list {
    display: flex;
    justify-content: end;
    &-item {
      margin-right: 15px;
      font-size: 13px;
      font-weight: 400;
      line-height: 16px;
      cursor: pointer;
      &:last-child {
        margin-right: 0;
      }
    }
  }
}
</style>
