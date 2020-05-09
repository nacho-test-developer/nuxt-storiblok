<template>
  <div v-editable="blok" class="column test">
    {{ blok.sub_title }}
    <pre>{{blok}}</pre>
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
