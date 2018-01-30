```scss
@import "themes/common";
.eg-fill-container {
    color: $eg-light;
    position: relative;
    height: 100px;
}

.eg-fill-1 {
    background-color: rgba(0, 0, 0, 0.4);
    @include scut-fill; // or @extend %scut-fill;
}

.eg-fill-2 {
    @include scut-fill;
}

.eg-fill-3 {
    @include scut-fill(true);
}
```
