<template>
  <h3>The Basic Structure of a Vue File</h3>
  <p>
    You can see what I am talking about in this section by comparing it to the
    App.vue and/or the HelloWorld.vue files.
  </p>
  <p>
    Each component in your app is in the components folder as a .vue file. Each
    one has the same basic structure of html, js, and css.
  </p>

  <p>
    The top of the file contains your html, wrapped in template tags. All of the
    html goes into this section of the vue file. Next you have the javascript
    wrapped in script tags, followed by the css wrapped in style tags. Take a
    look at HelloWorld.vue and see the basic structure there. All of your
    components and the App.js follow this same structure.
  </p>
</template>

export default { name: 'AboutApp' }
