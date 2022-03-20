<template>
  <v-row justify="center" align="center">
    <video width="320" height="240" controls>
      <source :src="video" type="video/mp4">
    </video>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
  data: () => ({
    video: process.env.videoAPI
  })
}
</script>
