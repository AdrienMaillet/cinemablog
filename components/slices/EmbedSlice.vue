<template>
  <section class="post-part single container">
    <prismic-embed :field="slice.primary.embed_field"/>
  </section>
</template>

<script>
export default {
  props: ['slice'],
  name: 'embed-slice'
}
</script>
