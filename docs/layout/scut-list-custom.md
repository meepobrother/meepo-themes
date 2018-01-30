```scss
.eg-list-custom-1 {
  @include scut-list-custom {
    color: $eg-light;
  }
}
.eg-list-custom-2 {
  @include scut-list-custom("\00bb", 1.3em, 1em);
}
.eg-list-custom-3 {
  @include scut-list-custom(count, 2em, 2em);
}
.eg-list-custom-4 {
  @include scut-list-custom(count ")" lower-alpha, 1.5em) {
    color: $eg-dark;
    font-size: 1.5em;
    font-weight: bold;
    top: -0.25em;
  }
  & > li + li {
    margin-top: 1em;
  }
}
```