Pure CSS Loader
=============

When I was learning about SASS I had some difficulties understanding the uses of loops like the for-loop. A monochromatic palette of colors could be achieved, but what else?

I came across an article that opened my mind in that regard. It talks about CSS animations, and particularly mentioned the use of the for-loop to create the necessary classes for the animation.



```javascript
@for $i from 1 to 12 {
  .loader:nth-of-type(#{$i}) {
    animation: 1s $i * 0.08s opacityLoader infinite;
  }
}
 
```


It seemed like an excellent idea to me, so I started to write my own animation code, and this is the result. Take a look [here](https://valessol.github.io/pure-css-loader/)