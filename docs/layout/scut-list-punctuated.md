```scss
.eg-punctuated-list {
  @include scut-list-punctuated;
  // or @extend %scut-list-comma;
}
.eg-semicolon-list {
  @include scut-list-punctuated("; ", $no-margin: false);
}
.eg-circle-list {
  @include scut-list-punctuated("\0020\2022\0020");
}
```