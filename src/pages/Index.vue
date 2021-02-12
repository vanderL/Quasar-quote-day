<template>
  <q-page class="flex column flex-center">
    <h1>Teste!</h1>
  </q-page>
</template>

<script>
  export default {
    name: 'PageIndex',
    data() {
      return {
        phrases: [
          'Enfrente os problemas e leve a melhor!',
          'Dê mais atenção ao que você tem de bom na sua vida',
          'De nada adianta ter sonhos, se você não se empenhar em correr atrás',
          'Preste atenção nas oportunidades que estão à sua frente!'
        ],
      }
    },
    computed: {
      currentPhrases(){
        return
      }
    }
  }
</script>
