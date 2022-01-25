<template>
  <p>{{ $t('hello') }}</p>
</template>

<script>
export default {
  name: 'HelloI18n'
}
</script>



<!-- Para poner la traducción directamente en el componente. Sobre escribe lo que hay en locale al ser más especifico -->
<!-- <i18n>
{
  "en": {
    "hello": "Hello i18n in SFC!"
  }
}
</i18n> -->
