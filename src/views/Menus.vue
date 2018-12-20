<template>
  <div class="menu">
    <MenuUm/>
  </div>
</template>

<script>
// @ is an alias to /src
import MenuUm from '@/components/menu/MenuUm.vue';

export default {
  name: 'menu',
  components: {
    MenuUm,
  },
};
</script>
