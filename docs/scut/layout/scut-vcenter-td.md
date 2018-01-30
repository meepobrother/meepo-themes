```scss
.eg-vcenter-td-1 {
  @include scut-vcenter-td;
  // or @extend %scut-vcenter-td;
  height: 8em;
}
.eg-vcenter-td-2 {
  @include scut-vcenter-td(".eg-vcenter-td-inner");
  height: 12em;
}
// illustrating a list of selectors
.eg-vcenter-td-3 {
  @include scut-vcenter-td(".special-selector-1", ".special-selector-2", ".special-selector-3");
  height: 9em;
}
```