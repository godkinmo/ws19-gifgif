<template>
  <div class="flex items-center">
    <div class="md:w-1/2 md:mx-auto">
      <gif-gif :data-votes="votes"></gif-gif>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import GifGif from '@/components/GifGif.vue'

export default {
  name: 'home',
  components: {
    GifGif
  },
  data() {
    return {
      votes: [
        { picked: 'git', reason: 'Reason...', name: 'Jack' },
        { picked: 'gif', reason: 'Reason...', name: 'David' },
        { picked: 'git', reason: 'Reason...', name: 'Mary' },
      ],
    }
  }
}
</script>
