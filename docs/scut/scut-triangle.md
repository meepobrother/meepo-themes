```scss
@import "themes/common";
.eg-triangle-default {
    @include scut-triangle; // or @extend %scut-triangle;
}

.eg-triangle-equilateral {
    @include scut-triangle(up, 100px 87px, $eg-muted);
}

.eg-triangle-top-right {
    @include scut-triangle(top-right, 2em, $eg-dark);
}

.eg-triangle-bottom-left {
    @include scut-triangle(bottom-left, 80px 40px, $eg-light);
}

.eg-triangle-button {
    &:after {
        content: "";
        margin-left: 0.3em;
    }
    &.m-down:after {
        @include scut-triangle(down);
    }
    &.m-up:after {
        @include scut-triangle(up);
    }
    &.m-right:after {
        @include scut-triangle;
    }
}
```