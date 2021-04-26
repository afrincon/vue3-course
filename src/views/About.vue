<template>
  <div class="about">
    <h1>A site for events to better the world</h1>

    <SimpleForm />
  </div>
</template>

<script>
import SimpleForm from '@/views/SimpleForm.vue'
export default {
  name: 'About',
  components: {
    SimpleForm,
  },
}
</script>
