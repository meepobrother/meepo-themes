```scss
.burger-icon {
    @include burger(25px, 3px, 5px, #222);
}
.circle.is-active .burger-icon {
    @include burger-to-cross;
}
```

```html
<div class="circle is-active">
  <div class="burger-icon"></div>
</div>
```