<template>
  <header>
    <div id="logo-wrapper">
      <img id="logo" src="@/assets/atos_logo_white.svg" />
    </div>
    <img id="header-curves" src="@/assets/header-curves.svg" />
  </header>
  <div id="frame-wrapper" style=''>
    <img id="menti-qr-code" src="@/assets/mentimeter_qr_code.png" />
      <div id="logo-hider"></div>
      <iframe id="menti-frame" 
        sandbox='allow-scripts allow-same-origin allow-presentation'
        allowfullscreen='true'
        allowtransparency='true'
        frameborder='0'
        src='https://www.mentimeter.com/app/presentation/al2tsd45b619wthff7rpbz7tbrkbhe81/embed'
      >
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

  #menti-qr-code {
    position: absolute;
    right: 0;
    z-index: 2;
    height: 27%;
  }

  #logo-hider {
    background-color: white;
    position: absolute;
    z-index: 1;
    width: 25vw;
    right: 0;
    top: 0;
    height: 5em;
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

  #menti-frame {
    position: absolute;
    top: 0;
    left: 0;
    border: 0;
    height: 100%;
    width: 100%;
  }
</style>
