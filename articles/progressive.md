# Article: Progressive enhancement

*Inspired by the talk Jasper Moelker gave on progressive enhancement*

## Progressive enhancement

*“This is also one of the thoughts behind mobile first; what you don’t need on a small device you might also not need on a bigger device.”*

### What do you really need?

The thought behind Progressive enhancement is that you build web apps that could work anywhere and at any time. When building an app using Progressive enhancement you think in layers. Content, styling and functionality. Working this way actually has multiple benefits. When leaving out features at the first layer you might come to realize that you don’t need those features at all, and that all they do is bloat your software. This is also one of the thoughts behind mobile first; what you don’t need on a small device you might also not need on a bigger device.

### HTML (Baseline)

The first layer you work with is HTML. Here you define what your content is and choose the right semantic elements for your content; using W3C standards. Building this first layer means making sure your web app works on any device and with slow connection. It’s the bare foundation of what a user would need. Usually this means this basic info, and maybe a basic form/links. Though it’s advisable to not use links and forms and instead focus on pure content.

### CSS (Acceptable)

Once your foundation is solid you can start making it more pleasing to the eye and improve user experience. By adding CSS you can enhance the users experience. It’s important to make sure you keep the usability working as intended. Using absolute positioning can be a nice trick, but make sure it doesn’t remove content from its logical position.

### Javascript (Enjoyable)

Once you’ve got a solid web app running on HTML and CSS you can start adding Javascript. This is where some of the heavy coding comes in and where your app can reach new heights both in terms of experience and features. It’s important to keep in mind what the actual goal of the web app is as to not bloat it with useless features.

### conclusion

Thinking in layers can help us as developers in more ways than one. Not only do we build usable products with clean code; but we can filter out what’s actually important in order for our web app to work as intended and deliver a solid user experience.

#### sources

* [Google dive into PWA](https://developers.google.com/web/progressive-web-apps/)
* [Smashing article on PWA](https://www.smashingmagazine.com/2016/08/a-beginners-guide-to-progressive-web-apps/)
* [Google talk on PWA](https://www.youtube.com/watch?v=m-sCdS0sQO8)
