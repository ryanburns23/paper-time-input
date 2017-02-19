# \<paper-time-input\>

Polymer element to accept a time with paper-input & paper-dropdown-menu

Inspired by the time-input in google forms

<!--
```
<custom-element-demo height="330px">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-time-input.html">
    <style>
      paper-time-input{
      	max-width: 400px;
        margin: 0 auto;
        padding: 10px;
      }
    </style>
    <template is="dom-bind">
      <next-code-block></next-code-block>
    </template>
  </template>
</custom-element-demo>
```
-->

```html
<paper-time-input
  value="{{result}}"
  hour="4"
  min="20"
  am-pm="AM">
</paper-time-input>

<p>[[result]]</p>
```
