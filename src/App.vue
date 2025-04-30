<template>
  <header>
    <div id="logo-wrapper">
      <img id="logo" src="@/assets/atos_logo_white.svg" />
    </div>
    <img id="header-curves" src="@/assets/header-curves.svg" />
  </header>
  <iframe src="https://www.example.com"></iframe>
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
