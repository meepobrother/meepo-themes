```scss
@import "themes/common";
.eg-image-replace {
    @include scut-image-replace; // or @extend %scut-image-replace;
    background: url("//placehold.it/200x200") no-repeat;
    background-size: contain;
    height: 8em;
}
```