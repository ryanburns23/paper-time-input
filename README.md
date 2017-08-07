# \<paper-time-input\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ryanburns23/paper-time-input)


Polymer element to accept a time with paper-input & paper-dropdown-menu
Inspired by the time-input in google forms

Polymer 2 supported

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-time-input.html">
    <style>
      paper-time-input{
      	max-width: 400px;
        margin: 0 auto;
        padding: 10px;
      }
      body{
        margin-bottom: 50px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<paper-time-input hour="3" min="05" am-pm="PM"></paper-time-input>
```

- paper-menu-button 2.0 depends on neon-animation 2.0, which doesn't import the Web Animations polyfill, so you'll have to import it
