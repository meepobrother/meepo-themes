```scss
.eg-side-lined-1 {
  @include scut-side-lined;
  // or @extend %scut-side-lined;
}
.eg-side-lined-2 {
  font-size: 2em;
  @include scut-side-lined(0.3em, 1em, $eg-light, $v-adjust: 0.1em);
}
.eg-side-lined-3 {
  @include scut-side-lined($double: 0.3em, $color: $eg-muted, $v-adjust: 0.05em);
}
.eg-side-lined-4 {
  @include scut-side-lined($style: dotted);
}
```