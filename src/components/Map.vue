<template>
  <GmapMap
  :center="{lat: 54.713471, lng: 55.994398}"
  :zoom="12"
  map-type-id="roadmap"
  style="width: 800px; height: 600px"
>
  <GmapMarker
    :position="{lat: 54.713471, lng: 55.994398}"
  />
</GmapMap>
</template>

<script>
export default {
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

</style>

