<template>
  <div id="audio" class="player-wrapper">
    <AudioPlayer
        file="https://api.songofgod.ru/files/fr/crois_seulement/audios/005.mp3"></AudioPlayer>
    <AudioTailwind/>
  </div>
</template>

<script>
// @ is an alias to /src
import AudioPlayer from "@/components/AudioPlayer";
import AudioTailwind from "@/components/AudioTailwind";

export default {
  name: 'Home',
  components: {
    AudioTailwind,
    AudioPlayer
  }
}
</script>
