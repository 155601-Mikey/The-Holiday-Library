# The Holiday Overlay

A simple JavaScript library to add a festive Holiday-themed overlays to your website.

## Christmas Demo
Check out the live demo:  
[Christmas Overlay Demo](https://155601-mikey.github.io/christmas-overlay-snow)

## Installation

Include the library in your HTML file:

```html
<script src="https://155601-mikey.github.io/christmas-overlay-snow/ChristmasOverlay.js"></script>
```

Usage
Use the public API to enable or disable the overlay.

Enable the Overlay
```javascript
christmasOverlaySnow.enable();
```
Disable the Overlay
```javascript
christmasOverlaySnow.disable();
```
Custom Options
You can customize the overlay by passing options to the enable method:

```javascript
christmasOverlaySnow.enable({
  snowflakeCount: 100,       // Number of snowflakes (default: 50)
  snowflakeColor: 'red',     // Color of snowflakes (default: 'white')
  zIndex: 99999              // Z-index of the overlay (default: 9999)
});
```
Contributing
```
Feel free to submit issues or pull requests to improve this library!
```

License
```
This project is licensed under the MIT License.
```
