<template>
  <div>
    <p :class="$style.myParagraph">Paragraph 1</p>
    <p :class="$style.myParagraph">Paragraph 2</p>
    <p :class="$style.myParagraph">Paragraph 3</p>
  </div>
</template>

<script>
export default {
  name: 'Example'
}
</script>

<style lang="postcss" module>
.myParagraph {
  composes: m-2 p-2 border border-grey text-blue from global;
}
</style>
