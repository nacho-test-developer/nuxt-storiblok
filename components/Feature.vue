<template>
  <div v-editable="blok" class="column feature">
    {{ blok.name }}<br />
    <small v-text="blok.description" />
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
