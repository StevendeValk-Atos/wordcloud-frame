<template>
  <header>
    <div id="logo-wrapper">
      <img id="logo" src="@/assets/atos_logo_white.svg" />
    </div>
    <img id="header-curves" src="@/assets/header-curves.svg" />
  </header>
  <div id="frame-wrapper" style=''>
      <iframe sandbox='allow-scripts allow-same-origin allow-presentation'
        allowfullscreen='true'
        allowtransparency='true'
        frameborder='0' height='315'
        src='https://www.mentimeter.com/app/presentation/alh34eyg4xop2ydnwr5gbns6fwerp7iw/embed'
        style='position: absolute; top: 0; left: 0; width: 100%; height: 100%;' width='420'>
      </iframe>
      </div>
</template>

<style scoped>
  header {
    background-color: #0073e6;
    color: white;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }

  #logo-wrapper {
    display: flex;
    flex-direction: column;
    justify-content: center ;
  }

  #logo {
    height: 2em;
    margin: 1em;
  }

  #header-curves {
    max-height: 5em;
  }

  #frame-wrapper {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    overflow: hidden;
    margin-top: 5em;
  }

  iframe {
    border: 0;
    height: 99vh;
    width: 100%;
  }
</style>
