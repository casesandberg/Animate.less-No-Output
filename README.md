#Animate LESS Hat.less
*Cross-browser CSS3 animation library using LESS Hat Mixins*

Animate.css was originally created by [Dan Eden](https://github.com/daneden/animate.css "Dan Eden"). It's a bunch of cool, fun, and cross-browser animations converted into LESS (using LESS Hat) for you to use in your Bootstrap projects (v3.1.1). Great for emphasis, home pages, sliders, and general just-add-water-awesomeness.

This now is integrated with [LESS Hat 3.0](https://github.com/madebysource/lesshat "LESS Hat 3.0"). I have also cleaned up some stuff that [machito](https://github.com/machito/animate.less "machito") had started in his conversion to animate.less.

##Files

-  `./animateCSS/...` is a folder submodule for the https://github.com/daneden/animate.css repo
-  `./bootstrap-examples/...` is a folder with examples on how to implement this library with your Bootstrap project
-  `./lesshat/...` is a folder submodule for the https://github.com/madebysource/lesshat repo
-  `./modules/...` is a folder for all the animation modules (used in `animate-lesshat.less`)
-  `./modules-prefixed/...` is a folder for all the animation modules prefixed (used in `animate-lesshat-prefixed.less`)
-  `./tests/...` is a folder used just for testing the animations (you can pretty much ignore this)
-  `animate-lesshat.less` (4kb) is the compiled version of animate.css using Less Hat
-  `animate-lesshat-prefixed.less` (5kb) is the compiled version of animate.css using Less Hat Prefixed


##Bootstrap
To use animate-lesshat.less in your Bootstrap project (v3.1.1), simply add this import into `bootstrap.less`:

```css
/* non-prefixed version */
@import "animate-lesshat.less";

/* prefixed version */
@import "animate-lesshat-prefixed.less";
```

See `./bootstrap-examples/bootstrap.less` or `./bootstrap-examples/bootstrap-lesshat-prefixed.less` for examples.

##Usage
[See animate.css docs for how to use](https://github.com/daneden/animate.css)

##Live demo

View the animation library in action over at http://daneden.me/animate/.

##Learn more

You can learn more about animate.css over at http://daneden.me/animate and Twitter Bootstrap over at http://getbootstrap.com/

##Animation Library

####attention_seekers
-  bounce
-  flash
-  pulse
-  rubberBand
-  shake
-  swing
-  tada
-  wobble

####bouncing_entrances
-  bounceIn
-  bounceInDown
-  bounceInLeft
-  bounceInRight
-  bounceInUp

####bouncing_exits
-  bounceOut
-  bounceOutDown
-  bounceOutLeft
-  bounceOutRight
-  bounceOutUp

####fading_entrances
-  fadeIn
-  fadeInDown
-  fadeInDownBig
-  fadeInLeft
-  fadeInLeftBig
-  fadeInRight
-  fadeInRightBig
-  fadeInUp
-  fadeInUpBig

####fading_exits
-  fadeOut
-  fadeOutDown
-  fadeOutDownBig
-  fadeOutLeft
-  fadeOutLeftBig
-  fadeOutRight
-  fadeOutRightBig
-  fadeOutUp
-  fadeOutUpBig

####flippers
-  flip
-  flipInX
-  flipInY
-  flipOutX
-  flipOutY

####lightspeed
-  lightSpeedIn
-  lightSpeedOut

####rotating_entrances
-  rotateIn
-  rotateInDownLeft
-  rotateInDownRight
-  rotateInUpLeft
-  rotateInUpRight

####rotating_exits
-  rotateOut
-  rotateOutDownLeft
-  rotateOutDownRight
-  rotateOutUpLeft
-  rotateOutUpRight

####sliders
-  slideInDown
-  slideInLeft
-  slideInRight
-  slideInUp
-  slideOutLeft";
-  slideOutDown
-  slideOutRight
-  slideOutUp

####specials
-  hinge
-  rollIn
-  rollOut

####zooming_entrances
-  zoomIn
-  zoomInDown
-  zoomInLeft
-  zoomInRight
-  zoomInUp

####zooming_exits
-  zoomOut
-  zoomOutDown
-  zoomOutLeft
-  zoomOutRight
-  zoomOutUp