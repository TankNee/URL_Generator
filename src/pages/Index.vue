<template>
  <q-page class="flex flex-center">
    <URLInput></URLInput>
    <iframe
      style="margin-top: 50px;"
      src="https://ljscq.bmcx.com/"
      height="500px"
      seamless="seamless"
    ></iframe>
  </q-page>
</template>

<script>
import URLInput from "components/URLInput.vue";
export default {
  name: "PageIndex",
  components: { URLInput }
};
</script>
