<template>
  <h3>The steps to start a Vue app...</h3>
  <p>
    Starting a Vue app is simple. These steps are for Vue beginners, written by
    me, a Vue beginner, as I learn. I am using VSCode and the integrated
    terminal as I write this.
  </p>

  <p class="emphasis">
    You will need to intall Vue on your computer first.
  </p>
  <p>
    1. To start, create a folder in VSCode to hold your Vue app, then open your
    terminal and type in:
  </p>
  <code>vue create app-name</code>
  <p class="emphasis">(app-name is the name you give to your app)</p>
  <p>
    You will be given options for different installations or to do a manual
    installation. This has to do with dependencies. For now, just choose the
    default for Vue3.
  </p>
  <p>2. Once the app is done installing, cd into the app folder.</p>
  <code>cd app-name</code>
  <p>3. Now you can start the server</p>
  <code>npm run serve</code>
  <p>
    Once the server is started, open your browser to localhost:8080. You should
    see the welcome Vue page in the browser window.
  </p>
</template>

export default { name: 'HowToVue' }

<style scoped>
body {
  text-align: start;
}
code {
  background-color: grey;
  padding: 0.5rem;
  font-weight: bold;
}
.emphasis {
  font-size: 0.8rem;
  font-weight: bold;
  font-style: italic;
}
</style>
