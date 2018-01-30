```scss
@import "themes/common";
.eg-center-absolutely-container {
    position: relative;
    height: 800px;
}

.eg-center-absolutely-1 {
    @include scut-center-absolutely(22em 2.5em);
}

.eg-center-absolutely-2 {
    @include scut-center-absolutely(20em n);
}

.eg-center-absolutely-3 {
    @include scut-center-absolutely(n 2.5em);
}
```


```html
<div class="eg-center-absolutely-container">
  <div class="eg-center-absolutely-1">eg-center-absolutely-1</div>
  <div class="eg-center-absolutely-2">eg-center-absolutely-2</div>
  <div class="eg-center-absolutely-3">eg-center-absolutely-3</div>
</div>
```