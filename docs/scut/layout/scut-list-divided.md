```scss

.eg-list-bar {
  @include scut-list-divided;
  // or @extend %scut-list-bar;
}
.eg-list-breadcrumb {
  @include scut-list-divided("/");
  // or @extend %scut-list-breadcrumb;
}
.eg-list-divided-1 {
  @include scut-list-divided("...", 0, right, $no-margin: false);
}
.eg-list-divided-2 {
  @include scut-list-divided("", 0.5em, left, 3em) {
    background-color: $eg-dark;
    width: 1em;
  }
}
```