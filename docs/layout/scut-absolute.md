```scss
@import "themes/common";
.eg-absolute-container {
    position: relative;
    height: 100px;
}

.eg-absolute-1 {
    @include scut-absolute; // or @extend %scut-absolute;
}

.eg-absolute-2 {
    @include scut-absolute(n 0.5em 1em n);
}

```