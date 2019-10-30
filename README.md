# A Guide to CSS Animation (Demo Code)

![A Guide to CSS Animation](https://cdn-images-1.medium.com/max/800/1*YMIFMQyYdSkmGAus_VZiPw.gif)

This is the demo code for "A Guide to CSS Animation"

* [A Guide to CSS Animation - Part 1](https://medium.com/@jh3y/a-guide-to-css-animation-part-1-8777f5beb1f8)
* [A Guide to CSS Animation - Part 2](https://medium.com/@jh3y/a-guide-to-css-animation-part-2-2cd422f78567)
* [A Guide to CSS Animation - Part 3](https://medium.com/@jh3y/a-guide-to-css-animation-part-3-2e497110119)

## Getting started
You'll want to run `npm i` to get started. This will install `browser-sync` locally so you can serve the demos on localhost.

Once installed, run `make serve` from the root of the repository.

Any changes you make to code in the `public` directory will be automatically reflected in the browser with live reload goodness! 😋

## CSS Animation properties

[animation](https://developer.mozilla.org/en-US/docs/Web/CSS/animation) - The animation shorthand CSS property applies an animation between styles. It is a shorthand for animation-name, animation-duration, animation-timing-function, animation-delay, animation-iteration-count, animation-direction, animation-fill-mode, and animation-play-state.
```css
 animation: name duration timing-function delay iteration-count direction fill-mode play-state;
```

#### The animation property is a shorthand property for the properties below:

---
[animation-name](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-name) - The animation-name CSS property sets one or more animations to apply to an element. Each name is an @keyframes at-rule that sets the property values for the animation sequence.
```css
animation-name: keyframename|none|initial|inherit;
```
---
[animation-duration](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-duration) - The animation-duration CSS property sets the length of time that an animation takes to complete one cycle.
```css
animation-duration: time|initial|inherit;
```
---
[animation-timing-function](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function) - The animation-timing-function CSS property sets how an animation progresses through the duration of each cycle.
```css
animation-timing-function: linear|ease|ease-in|ease-out|ease-in-out|step-start|step-end|steps(int,start|end)|cubic-bezier(n,n,n,n)|initial|inherit;
```
---
[animation-delay](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-delay) - The animation-delay CSS property sets when an animation starts. The animation can start later, immediately from its beginning, or immediately and partway through the animation.
```css
animation-delay: time|initial|inherit;
```
---
[animation-iteration-count](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-iteration-count) - The animation-iteration-count CSS property sets the number of times an animation cycle should be played before stopping.

If multiple values are specified, each time the animation is played the next value in the list is used, cycling back to the first value after the last one is used.
```css
animation-iteration-count: number|infinite|initial|inherit;
```
---
[animation-direction](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-direction) - The animation-direction CSS property sets whether an animation should play forwards, backwards, or alternating back and forth.
```css
animation-direction: normal|reverse|alternate|alternate-reverse|initial|inherit;
```
---
[animation-fill-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-fill-mode) - The animation-fill-mode CSS property sets how a CSS animation applies styles to its target before and after its execution.
```css
animation-fill-mode: none|forwards|backwards|both|initial|inherit;
```
---
[animation-play-state](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-play-state) - The animation-play-state CSS property sets whether an animation is running or paused.
```css
animation-play-state: paused|running|initial|inherit;
```
---

This

```css
div {
    animation-name: spin;
    animation-duration: .5s;
    animation-timing-function: ease-out;
    animation-delay: 1s;
    animation-iteration-count: infinite;
    animation-direction: normal;
    animation-fill-mode: none;
    animation-play-state: running;
}
```

is equivalent to this

```css
div {
    animation: spin .5s ease-out 1s infinite normal none running;
}
```


## License
MIT

---

Any problems or questions, feel free to post an issue or reach out!

