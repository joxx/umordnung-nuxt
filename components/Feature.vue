<template>
  <div
    v-editable="blok"
    class="py-2">
    <h1 class="text-lg">{{ blok.name }}</h1>
  </div>
</template>

<script>
export default {
  name: 'FeatureComponent',
  props: {
    blok: {
      type: Object,
      required: true
    }
  }
}
</script>
