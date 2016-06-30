# viewport-resizer
HTTPS hosted Viewport Resizer by @maltewassermann

Add this bookmarklet to use it. It is configured with current devices and screen sizes as of mid 2016.

```
javascript:void((function(d)%7Bif(self!%3Dtop%7C%7Cd.getElementById(%27toolbar%27)%26%26d.getElementById(%27toolbar%27).getAttribute(%27data-resizer%27))return false%3Bd.write(%27<!DOCTYPE HTML><html style%3D"opacity:0%3B"><head><meta charset%3D"utf-8"/></head><body><a data-viewport%3D"320x480" data-icon%3D"mobile">iPhone, iPod Touch</a><a data-viewport%3D"320x568" data-icon%3D"mobile" data-version%3D"5">iPhone 5/5c/5s/SE</a><a data-viewport%3D"375x667" data-icon%3D"mobile" data-version%3D"6">iPhone 6/6S</a><a data-viewport%3D"414x736" data-icon%3D"mobile" data-version%3D"6%2B">iPhone 6/6S Plus</a><a data-viewport%3D"768x1024" data-icon%3D"tablet">iPad</a><a data-viewport%3D"1024x1366" data-icon%3D"tablet" data-version%3D"Pro">iPad Pro</a><a data-viewport%3D"1280×720" data-icon%3D"display" data-version%3D"720">720p</a><a data-viewport%3D"1920×1080" data-icon%3D"display" data-version%3D"1080">1080p</a><a data-viewport%3D"2560×1440" data-icon%3D"display" data-version%3D"1440">1440p</a><script src%3D"https://kane-c.github.io/viewport-resizer/resizer.min.js"></script></body></html>%27)%7D)(document))%3B
```
