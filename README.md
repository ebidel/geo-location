[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ebidel/geo-location)

## \<geo-location\>

Geolocation API Polymer web component.

Example to get the device geolocation values:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="geo-location.html">
    <div>
      <dom-bind>
        <template is="dom-bind">
          <next-code-block></next-code-block>
        </template>
      </dom-bind>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<geo-location
    latitude="{{latitude}}"
    longitude="{{longitude}}">
</geo-location>

<ul>
  <li>Latitude: [[latitude]]</li>
  <li>Longitude: [[longitude]]</li>
</ul>
```
