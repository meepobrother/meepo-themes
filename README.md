### meepo themes

- [scut-em 转化为em](docs/scut-em.md)

> normalize.css, weui, hover , animate 等常用库

- [ionic](https://github.com/ionic-team/ionic)

- [weui](https://github.com/Tencent/weui),[awesome-wepy](https://github.com/aben1188/awesome-wepy)


```sh
wepy new myproject
```
- [scss](http://sass.bootcss.com/docs/sass-reference/)
- [less](http://less.bootcss.com/)

- 预设变量

```scss
// normalize
$base-font-size: 16px !default;
$base-line-height: 24px !default;
$base-unit: 'em' !default;
$base-font-family: null !default;
$h1-font-size: 2 * $base-font-size !default;
$h2-font-size: 1.5 * $base-font-size !default;
$h3-font-size: 1.17 * $base-font-size !default;
$h4-font-size: 1 * $base-font-size !default;
$h5-font-size: 0.83 * $base-font-size !default;
$h6-font-size: 0.67 * $base-font-size !default;
$indent-amount: 40px !default;
$normalize-vertical-rhythm: false !default;
// hover
$nameSpace: 'hvr' !default;
$fastDuration: .1s !default;
$mediumDuration: .3s !default;
$slowDuration: .5s !default;
$primaryColor: #e1e1e1 !default;
$secondaryColor: #666 !default;
$highlightColor: #ccc !default;
$activeColor: #2098D1 !default;
$shadowColor: rgba(0, 0, 0, .6) !default;
$tipWidth: 10px !default;
$tipHeight: 10px !default;
$tipColor: $primaryColor !default;
$spaceBetweenTextAndArrows: 2.2em !default;
$curlWidth: 25px !default;
$curlHeight: 25px !default;
$revealAreaColor: white !default;
$curlLineColor: #aaa !default;
$curlTransitionColor: #ccc !default;
$curlLastColor: white !default;
$webkit: true !default;
$moz: false !default;
$ms: false !default;
$o: false !default;
$includeClasses: true !default;
// burger
$sass-burger-add-vendor-prefixes: true !default;
// loader
$loader-color: #0052ec !default;
$loader-size: 56px !default;
$loader-height: 20px !default;
$loader-border-size: 8px !default;
$loader-gap: 12px !default;
$loader-animation-duration: 1s !default;

/**
 * animate
 */

$countDefault: 1 !default;
$durationDefault: 1s !default;
$delayDefault: 0s !default;
$functionDefault: ease !default;
$fillDefault: both;
$visibilityDefault: hidden !default;

/**
 * modularscale
 */

$double-octave: 4;
$pi: 3.14159265359;
$major-twelfth: 3;
$major-eleventh: 2.666666667;
$major-tenth: 2.5;
$octave: 2;
$major-seventh: 1.875;
$minor-seventh: 1.777777778;
$major-sixth: 1.666666667;
$phi: 1.618034;
$golden: $phi;
$minor-sixth: 1.6;
$fifth: 1.5;
$augmented-fourth: 1.41421;
$fourth: 1.333333333;
$major-third: 1.25;
$minor-third: 1.2;
$major-second: 1.125;
$minor-second: 1.066666667;
$ms-base: 1em !default;
$ms-ratio: $fifth !default;
$modularscale: () !default;

/**
 * scut
 */


/**
  * flex
  */

$flexiblegs-method: ( "css", "bem");
$flexiblegs-breakpoint: ( "xl": "", "lg": "(max-width: 1024px)", "md": "(max-width: 768px)", "sm": "(max-width: 667px)");
$wrap-col: ( "auto", 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12);
$wrap-prop: ( "table", "flexbox", "normal", "left", "center", "right", "top", "middle", "bottom", "between", "around", "baseline", "reverse", "not-reverse");
$col-row: ( 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12);
$col-width: ();
$col-prop: ( "hidden", "not-hidden", "first", "not-first", "last", "not-last");
$wrap-gutter: ( 0, 8, 16, 24, 40);
$wrap-outside: ( 0, 8, 16, 24, 40);
$wrap-masonry: ( 2, 3, 4, 5, 6);

/**
 * ionicons
 */

$ionicons-font-path: "./app/themes/fonts" !default;
$ionicons-font-family: "Ionicons" !default;
$ionicons-version: "2.0.1" !default;
$ionicons-prefix: ion- !default;
```



- install

```
yarn add meepo-themes
```

- change veriable , themes/variables.scss and copy the fonts to your folder

```scss
$ionicons-font-path: "./assets/fonts";
```

- use tools

```scss
@import "meepo-themes/global";
```

- use style

```scss
@import "meepo-themes";
```

