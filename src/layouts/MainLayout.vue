<template>
  <HeaderContent />
  <main>
    <slot></slot>
  </main>
  <FooterContent />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeaderContent from '@/components/HeaderContent.vue';
import FooterContent from '@/components/FooterContent.vue';

export default defineComponent({
  components: {
    HeaderContent,
    FooterContent
  }
});
</script>
