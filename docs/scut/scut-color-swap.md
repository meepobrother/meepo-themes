```scss
@import "themes/common";
.eg-color-swap-1 {
    background: #fff; // only text `color` changes, with a transition
    @include scut-color-swap($eg-dark, $eg-light, 1s);
}

.eg-color-swap-2 {
    // both text `color` and `background-color` change,
    // with no transition
    @include scut-color-swap($eg-light $eg-dark, $eg-dark $eg-light);
}

.eg-color-swap-3 {
    color: #fff; // only `background-color` changes, with a transition
    @include scut-color-swap($eg-dark, $eg-light, 0.5s, true);
}
```