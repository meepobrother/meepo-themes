
[sassdoc](http://davidkpiano.github.io/sassdash/sassdoc/index.html)

```scss
$maps: (
  ('name': 'barney', 'age': 36),
  ('name': 'fred', 'age': 40)
);

_pluck($maps, 'name'); // ('barney', 'fred')
```


```scss
$foobar: ('a' 'b' 'c', 'd' 'e' 'f', 'g' 'h' 'i');

_($foobar,
  _map _join,
  _reduce _str-concat,
  _concat 'jkl',
  _join ' -- '); // 'abcdefghi -- jkl'
```


```scss
$capitals: ('Tallahassee', 'Springfield', 'Austin');

$uppercase-capitals: _map($capitals, to-upper-case);
// => ('TALLAHASSEE', 'SPRINGFIELD', 'AUSTIN')
```

```scss
$map: ('foo': ('bar': ('baz': 'quo')));
$list: (1, ('a': 2), 3);

$baz: _get($map, 'foo' 'bar' 'baz'); // => 'quo'
$something: _get($list, 2 'a'); // => 2

// You can also do this:
$baz: _get($map, 'foo.bar.baz'); // => 'quo'

$map: _set($map, 'foo' 'bar' 'test', 42);
// => ('foo': ('bar': ('baz': 'quo', 'test': 42)))

$list: _set($list, 2 'a', 42);
// => (1, ('a': 42), 3)
``