```scss
.eg-list-floated-1 {
  @include scut-list-floated;
  // or @extend %scut-list-floated;
}
.eg-list-floated-2 {
  @include scut-list-floated(1em, $no-margin: false);
}
.eg-list-floated-3 {
  @include scut-list-floated(2em, right);
}
```