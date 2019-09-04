# A Guide to CSS Animation (Demo Code)

![A Guide to CSS Animation](https://cdn-images-1.medium.com/max/800/1*YMIFMQyYdSkmGAus_VZiPw.gif)

This is the demo code for "A Guide to CSS Animation"

* [A Guide to CSS Animation - Part 1](https://medium.com/@jh3y/a-guide-to-css-animation-part-1-8777f5beb1f8)
* [A Guide to CSS Animation - Part 2](https://medium.com/@jh3y/a-guide-to-css-animation-part-2-2cd422f78567)
* [A Guide to CSS Animation - Part 3](https://medium.com/@jh3y/a-guide-to-css-animation-part-3-2e497110119)

## Getting started
You'll want to run `make setup`, `yarn`, or `npm i` to get started. This will install `browser-sync` locally so you can serve the demos on localhost.

Once installed, run `make serve` from the root of the repository.

Any changes you make to code in the `public` directory will be automatically reflected in the browser with live reload goodness! 😋

## CSS Animation

**animation-name**: used to 
```css
animation-name: spin;
```
---
```css
animation-duration: .5s;
```
---
```css
animation-timing-function: ease-out;
```
---
```css
animation-delay: 1s;
```
---
```css
animation-iteration-count: infinite;
```
---
```css
animation-direction: normal;
```
---
```css
animation-fill-mode: none;
```
---
```css
animation-play-state: running;
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

@jh3y 2018 :smile:
