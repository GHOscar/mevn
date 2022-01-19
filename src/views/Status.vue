<template>
  <div class="status">
    <Status />
  </div>
</template>

<script>
// @ is an alias to /src
import Status from '@/components/Status.vue'

export default {
  name: 'Status',
  components: {
    Status
  }
}
</script>