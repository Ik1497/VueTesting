<template>
  <h1>{{ title }}</h1>
  <title>{{ title }} | Streamer.bot Actions</title>
  <meta property="og:title" content="{{ title }}" />

  <h2>{{ description }}</h2>
  <meta property="og:description" content="{{ description }}" />

  <meta name="theme-color" content="#B80086" />

  <meta name="og:site_name" content="Streamer.bot Actions" />
  <meta
    property="og:image"
    content="https://raw.githubusercontent.com/Ik1497/Ik1497/main/assets/profile_picture/Logo-Round.png"
  />

</template>

<script>
  export default {
    name: "pageSettings",
    props: {
      title: String,
      description: String,
    },
  };
</script>
