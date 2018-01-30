```scss
.example {
  @include wrap;
  &__item {
    @include col;
  }
}
``

```scss
.example {
  @include wrap;
  @include wrap("gutter",24);
  @include wrap("outside",24);
  @include wrap(3);
  @include wrap("auto");
  @include wrap("table");
  &__item {
    @include col;
    @include col(1,3);
    &.three {
      @include col("hidden");
    }
  }
}
```