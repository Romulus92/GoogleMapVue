<template>
  <div id="app">
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
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>

</style>
