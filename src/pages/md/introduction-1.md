**react-spring** is a spring-physics based animation library that should cover most of your UI related animation needs. It gives you tools flexible enough to confidently cast your ideas into moving interfaces.

This library represents a modern approach to animation. It is very much inspired by Christopher Chedeau's [animated](https://github.com/animatedjs/animated) and Cheng Lou's [react-motion](https://github.com/chenglou/react-motion). It inherits animated's powerful interpolations and performance, as well as react-motion's ease of use. But while animated is mostly imperative and react-motion mostly declarative, react-spring bridges both. You will be surprised how easy static data is cast into motion with small, explicit utility functions that don't necessarily affect how you form your views.

## Why springs and not durations

The principle you will be working with is called a `spring`, it *does not have a defined curve or a set duration*. In that it differs greatly from the animation you are probably used to. We think of animation in terms of time and curves, but that in itself causes most of the struggle we face when trying to make elements on the screen move naturally, because nothing in the real world moves like that.

<p align="middle">
  <img height="250" src="https://i.imgur.com/7CCH51r.gif" />
</p>

We are so used to time-based animation that we believe that struggle is normal, dealing with arbitrary curves, easings, time waterfalls, not to mention getting this all in sync. As Andy Matuschak (ex Apple UI-Kit developer) [expressed it once](https://twitter.com/andy_matuschak/status/566736015188963328): *Animation APIs parameterized by duration and curve are fundamentally opposed to continuous, fluid interactivity*.

Springs change that, animation becomes easy and approachable, everything you do looks and feels natural by default. For a detailed explanation watch the video below:

<br />