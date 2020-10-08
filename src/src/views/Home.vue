<template>
  <div class="home">
    <div class="bg"></div>
    <div class="bg-image" style="background-image: url('https://i.imgur.com/ilXmv0U.png');"></div>
    <div class="bg-overlay"></div>
    <div class="header">
      <div class="branding">
        <img src="https://i.imgur.com/DFEWujo.png" alt="">
        <div class="text">
          <h1>Little Los Santos RP</h1>
          <h2>Discord.gg/LLS</h2>
        </div>
      </div>
    </div>

    <div class="image-container" v-tilt="{ max: 2 }">
      <img src="https://i.imgur.com/ilXmv0U.png" alt="">
      <div class="author">
        <span>JackDMack</span>
      </div>
    </div>

    <div class="music-container">
      <div class="music-bar">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="white" width="48px" height="48px"><path d="M8 6.82v10.36c0 .79.87 1.27 1.54.84l8.14-5.18c.62-.39.62-1.29 0-1.69L9.54 5.98C8.87 5.55 8 6.03 8 6.82z"/></svg>

        <span class="details">
          Author - Title
        </span>

        <div class="volume">
          <div class="volume-popup">
            <input type="range" orient="vertical">
          </div>
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="white" width="48px" height="48px"><path d="M3 10v4c0 .55.45 1 1 1h3l3.29 3.29c.63.63 1.71.18 1.71-.71V6.41c0-.89-1.08-1.34-1.71-.71L7 9H4c-.55 0-1 .45-1 1zm13.5 2c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 4.45v.2c0 .38.25.71.6.85C17.18 6.53 19 9.06 19 12s-1.82 5.47-4.4 6.5c-.36.14-.6.47-.6.85v.2c0 .63.63 1.07 1.21.85C18.6 19.11 21 15.84 21 12s-2.4-7.11-5.79-8.4c-.58-.23-1.21.22-1.21.85z"/></svg>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>
