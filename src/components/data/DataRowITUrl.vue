<template>
  <div class="url">
    <label><input type="checkbox" />Protocol</label>
    <label><input type="checkbox" />HostName</label>
    <label><input type="checkbox" />Path</label>
    <label><input type="checkbox" />QueryPrams</label>
  </div>
</template>
<script>
import { defineComponent } from 'vue';

export default defineComponent({
  setup() {},
});
</script>

<style lang="scss" scoped>
.url {
  align-items: center;
  display: flex;
  font-size: 0.75rem;

  label {
    display: flex;
    align-items: center;
    margin-right: 1rem;
    input {
      margin-right: 0.25rem;
    }
  }
}
</style>
