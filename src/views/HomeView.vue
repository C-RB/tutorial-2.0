<template>
    <MostrarMensaje/>
    <DirectivaShowComponent/>
    <DirectivaFor/>
    <BotonDeshabilitado/>
    <MensajeComponent/>
    <ContadorComponent/>
    <PadreComponent/>
 
</template>

<script>
// @ is an alias to /src

import MostrarMensaje from '@/components/MostrarMensaje.vue';
import DirectivaFor from'@/components/DirectivaFor.vue';
import DirectivaShowComponent from'@/components/DirectivaShowComponent.vue';
import BotonDeshabilitado from'@/components/BotonDeshabilitado.vue';
import MensajeComponent from'@/components/MensajeComponent.vue';
import ContadorComponent from '@/components/ContadorComponent.vue';
import PadreComponent from '@/components/PadreComponent.vue';


export default {
  name: 'HomeView',
  components: {
    MostrarMensaje,
    DirectivaShowComponent,
    DirectivaFor,
    BotonDeshabilitado,
    MensajeComponent,
    ContadorComponent,
    PadreComponent

  }
}
</script>
