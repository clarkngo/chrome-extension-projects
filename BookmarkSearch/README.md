# Hello World in Chrome Extension

## Video Guide

[![Curriculum App Demo](http://img.youtube.com/vi/bxeuZBY_i2c/0.jpg)](https://www.youtube.com/watch?v=bxeuZBY_i2c "Curriculum App Demo")


## Create `manifest.json`
```
{
  "manifest_version": 2,
  "name": "Hello World",
  "version": "1.0",
  "description": "A hello world extension!",
  "icons": {
    "128": "icon128.png",
    "48": "icon48.png",
    "16": "icon16.png"
  },
  "browser_action":{
    "default_icon": "icon16.png",
    "default_popup": "popup.html"
  }
}
```

## Download icons for different sizes:
- 128 x 128
- 48 x 48
- 16 x 16

## Create `popup.html`
```
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    <h2 id="greet">Hello World!</h2>
  </body> 
</html>
```