<template>
  <h1>How to Make & Use Components</h1>
  <ol>
    <li>
      1. In the components directory make a new file. For components the
      standard way is to capitalize the file name.
    </li>
    <p>For example: NewFile.vue</p>

    <li>
      2. Add your template tags, to contain your html.
      &lt;template&gt;&lt;/template&gt;
    </li>
    <li>
      3. Add some html inside of the template tags, such as a simple
      &lt;h1&gt;Hello World!&lt;/h1&gt;
    </li>
    <li>
      4. Add your script tags, to contain your exports and other JS
      &lt;script&gt;&lt;/script&gt;
    </li>
    <p>Here is a sample export object...</p>
    <code>
      export default { name: 'NewFile.vue' }
    </code>
    <li>5. OPTIONAL: add CSS &lt;style&gt;&lt;/style&gt;</li>

    <li>6. Go to your App.vue file, and follow these three steps...</li>
    <ol>
      <li>a. Import your component like this:</li>
      <code>import MakeFile from './components/MakeFile'</code>
      <li>b. Register the component within your export object like this:</li>
      <code>
        export default { name: App, components: { NewFile } }
      </code>
      <li>c. Add the component to your template:</li>
      <code> &lt;NewFile /&gt; </code>
    </ol>
  </ol>

  <p>Now your new component should show up in your browser on the app page.</p>
</template>
