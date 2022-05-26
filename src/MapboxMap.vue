<script setup lang="ts">
import { type Map } from 'mapbox-gl';

let MyMap:Map

(async () => {
  MyMap = new (await import('mapbox-gl')).Map
})();
</script>


