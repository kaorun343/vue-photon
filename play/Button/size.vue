<template lang="html">
  <div>
    <btn size="large">large button</btn>
    <btn>normal button</btn>
    <btn size="mini">mini button</btn>
  </div>
</template>

<script>
import { Button as Btn } from '../../src'

export default {
  components: { Btn }
}
</script>

<style lang="sass">
@import '~photon/dist/css/photon.css'
</style>
