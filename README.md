# viewport-resizer
HTTPS hosted Viewport Resizer by @maltewassermann

Note at the time this was built, the official site for this did not support HTTPS. It appears that it now does, so there's no real need for this.

It remains as a convenient source for the below pre-configured bookmarklet. It is configured with current devices and screen sizes as of April 2020. These presets include:

* iPhone < 5, iPod Touch < 5th gen (320x480)
* iPhone 5/5c/5s/SE 1st gen, iPod Touch 5th gen+ (320x568)
* iPhone 6/6s/7/8/SE 2nd gen (375x667)
* iPhone X/Xs/11 Pro (375x812)
* iPhone 6/6s/7/8 Plus (414x736)
* iPhone XR/Xs Max/11/11 Pro Max (414x896)
* iPad (most models) (768x1024)
* iPad 10.2" (810x1080)
* iPad Air/Pro 10.5" (834x1112)
* iPad Pro 12.9" (1024x1366)
* 720p (1280x720)
* 768p (1366x768)
* 1080p (1920x1080)
* 1440p (2560x1440)
* 4K (3840x2160)
* 5K (5120x2880)

```
javascript:void((function(d)%7Bif(self!%3Dtop%7C%7Cd.getElementById(%27toolbar%27)%26%26d.getElementById(%27toolbar%27).getAttribute(%27data-resizer%27))return false%3Bd.write(%27<!DOCTYPE HTML><html style%3D"opacity:0%3B"><head><meta charset%3D"utf-8"/></head><body><a data-viewport%3D"320x480" data-icon%3D"mobile">iPhone &lt; 5, iPod Touch < 5th gen</a><a data-viewport%3D"320x568" data-icon%3D"mobile" data-version%3D"5s">iPhone 5/5c/5s/SE 1st gen, iPod Touch 5th gen%2B</a><a data-viewport%3D"375x667" data-icon%3D"mobile" data-version%3D"8">iPhone 6/6s/7/8/SE 2nd gen</a><a data-viewport%3D"414x736" data-icon%3D"mobile" data-version%3D"8%2B">iPhone 6/6s/7/8 Plus</a><a data-viewport%3D"375x812" data-icon%3D"mobile" data-version%3D"11">iPhone X/Xs/11 Pro</a><a data-viewport%3D"414x896" data-icon%3D"mobile" data-version%3D"Max">iPhone XR/Xs Max/11/11 Pro Max</a><a data-viewport%3D"768x1024" data-icon%3D"tablet">iPad</a><a data-viewport%3D"810x1080" data-icon%3D"tablet" data-version%3D"10.2%22">iPad 10.2"</a><a data-viewport%3D"834x1112" data-icon%3D"tablet" data-version%3D"10.5%22">iPad Air/Pro 10.5"</a><a data-viewport%3D"1024x1366" data-icon%3D"tablet" data-version%3D"Pro 12">iPad Pro 12.9"</a><a data-viewport%3D"1280×720" data-icon%3D"display" data-version%3D"720">720p</a><a data-viewport%3D"1366x768" data-icon%3D"display" data-version%3D"768">768</a><a data-viewport%3D"1920×1080" data-icon%3D"display" data-version%3D"1080">1080p</a><a data-viewport%3D"2560×1440" data-icon%3D"display" data-version%3D"1440">1440p</a><a data-viewport%3D"3840x2160" data-icon%3D"display" data-version%3D"4K">4K (2160p)</a><a data-viewport%3D"5120x2880" data-icon%3D"display" data-version%3D"5K">5K (2880p)</a><script src%3D"https://kane-c.github.io/viewport-resizer/resizer.min.js"></script></body></html>%27)%7D)(document))%3B
```
