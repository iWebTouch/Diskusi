<template>
  <Layout>
    <div class="flex flex-wrap">
      <div class="w-full px-4">
        <CardSettings />
      </div>
    </div>
  </Layout>
</template>
<script>
import CardSettings from "@/components/Cards/CardSettings.vue";
import Layout from "@/layouts/Admin.vue";

export default {
  components: {
    CardSettings,
    Layout
  },
};
</script>
