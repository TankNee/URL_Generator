<template>
  <div class="url-input">
    <q-form>
      <q-input label="链接" filled dense></q-input>
      <q-btn
        color="primary"
        label="Primary"
        type="submit"
        size="xg"
        style="width:100%; margin-top:7px;"
      />
    </q-form>
    <q-separator></q-separator>
  </div>
</template>

<script>
export default {
  name: "URLInput",
  data() {
    return {
      link: ""
    };
  }
};
</script>

<style>
.url-input {
  margin-top: 20px;
}
</style>
