```scss
@import "themes/common";
// scut-sticky-footer-fluid
// scut-sticky-footer-fixed
.eg-vcenter-ib>p {
    max-width: 90%;
}

.eg-vcenter-ib-1{
    height: 100px;
    background: gray;
}

.eg-vcenter-ib-1 {
    @include scut-vcenter-ib; // or @extend %scut-vcenter-ib;
}

.eg-vcenter-ib-2 {
    @include scut-vcenter-ib(".eg-vcenter-ib-inner");
} // illustrating a list of selectors
.eg-vcenter-ib-3 {
    @include scut-vcenter-ib(".special-selector-1", ".special-selector-2", ".special-selector-3");
}
```