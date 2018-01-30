```scss
.eg-link-bb-1 a {
  @include scut-link-bb;
  // or @extend %scut-link-bb;
}
.eg-link-bb-2 a {
  color: $eg-muted;
  @include scut-link-bb(inherit, double, 4px);
  &:hover {
    color: $eg-dark;
    border-bottom-color: $eg-light;
  }
}
```