<template>
  <header>
    <div id="logo-wrapper">
      <img id="logo" src="@/assets/atos_logo_white.svg" />
    </div>
    <img id="header-curves" src="@/assets/header-curves.svg" />
  </header>
  <div style='
    position: relative; padding-bottom: 56.25%;
    padding-top: 35px; height: 0;
    overflow: hidden;'>
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



  iframe {
    border: 0;
    height: 100vh;
    width: 100%;
  }
</style>
