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
    components and the App.vue follow this same structure.
  </p>
  <h3>Here is a basic model:</h3>

  <p class="model-title">HTML</p>
  <li class="details">
    Place for all of your html. In the main App.vue file it will primarily
    contain components. More about components in a later section.
  </li>
  <p class="model-title">Javascript</p>
  <li class="details">
    Place for all of your javascript. Always contains an export object, with a
    name property.
  </li>
  <li class="details">
    In the App.vue file you will also be importing your components, and
    registering them. More on this in a later section.
  </li>
  <p class="model-title">CSS</p>
  <li class="details">
    This is where all of your css will go. If you add 'scoped' to the tag then
    the css will only apply to the component it is part of. The CSS in App.vue
    over-rides the individual styles.
  </li>
</template>

export default { name: 'AboutApp' };

<style>
.model-title {
  background-color: grey;
  padding: 0.5rem 0.25rem;
  color: white;
}

li {
  list-style-type: none;
}
</style>
