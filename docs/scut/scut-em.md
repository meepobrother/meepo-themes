- scut-em

```scss
// first pair
.eg-em-1 { width: scut-em(150); }
.eg-em-2 { width: 150px; }
// second pair
.eg-em-3,
.eg-em-4 { font-size: 20px; }
.eg-em-3 { width: scut-em(250, 20); }
.eg-em-4 { width: 250px; }
// third pair
.eg-em-5,
.eg-em-6 { font-size: 0.6em; }
.eg-em-5 { width: scut-em(275, 0.6em); }
.eg-em-6 { width: 275px; }
// list and units demonstration
.eg-em-7 {
  margin: scut-em(50 30px 0 60);
  padding: scut-em(50 20px 0)
}
// changing the default $scut-em-base value
// (compare to the second pair, above)
$scut-em-base: 20;
.eg-em-8 {
  font-size: 20px;
  width: scut-em(250);
}
```