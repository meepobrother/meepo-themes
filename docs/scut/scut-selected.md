```scss
@import "themes/common";
.eg-selected-1 {
    @include scut-selected {
        background-color: $eg-light;
    }
}

.eg-selected-2 {
    @include scut-selected(true) {
        background-color: $eg-light;
    }
}
```