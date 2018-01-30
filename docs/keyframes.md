```scss
@include keyframes(bob-float) {
	100% {
		@include prefixed(transform, translateY(-8px));
	}
}
```
```
@mixin prefixed($property, $value) {
    @if $webkit==true {
        -webkit-#{$property}: #{$value};
    }
    @if $moz==true {
        -moz-#{$property}: #{$value};
    }
    @if $ms==true {
        -ms-#{$property}: #{$value};
    }
    @if $o==true {
        -o-#{$property}: #{$value};
    }
    #{$property}: #{$value};
}

@mixin keyframes($name) {
    @if $webkit==true {
        @-webkit-keyframes #{$name} {
            @content;
        }
    }
    @if $moz==true {
        @-moz-keyframes #{$name} {
            @content;
        }
    }
    @if $ms==true {
        @-ms-keyframes #{$name} {
            @content;
        }
    }
    @if $o==true {
        @-o-keyframes #{$name} {
            @content;
        }
    }
    @keyframes #{$name} {
        @content;
    }
}
```