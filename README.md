# Lazy Loading
Start to load a your images after loading html page and you can use a css animation to show it.

## How to use
Rename `src` attribute in `img` of the html tag to `data-src` and add this script below on your end page:

```<script src="dist/lazy-loading.js"></script> ```

## Animation
If you want use animation to show the images when scrolling in view page, include this css:

```
.LazyLoading {
  transition: all ease-out 1s;
  transition-delay: .25s;
}
.Loading {
  transform: translateY(50px);
  opacity: 0;
}
```

## Demo

[See a exemplo](https://jsfiddle.net/shcj9L5t/2/)
