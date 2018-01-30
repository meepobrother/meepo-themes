```scss
@import "themes/common";
.eg-center-block-1 {
    width: 8em;
    @include scut-center-block; // or @extend %scut-center-block;
    min-height: 100px;
    background: gray;
}

.eg-center-block-2 {
    margin-top: 1em;
    @include scut-center-block(80%);
    min-height: 100px;
    background: red;
}
```