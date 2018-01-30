```scss
@import "themes/common";
.eg-hd-bp {
    background-color: $eg-muted;
    @include scut-hd-bp(3.0) {
        background-color: $eg-light;
    }
}
```