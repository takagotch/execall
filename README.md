### execall
--- 
https://github.com/sindresorhus/execall

```js
// test.js
import test from 'ava';
import execall from '.';

test('main', t => {
  t.is(result.match, '200');
  t.is(result.subMatches[0], '200');
  t.is(result.index, 1);
  t.is(execall(/d\+/g, '$20 and $400')[1].match, '400');
  t.is(execall(/d+/g, 'unicorn').length, 0);
});


```

```
```

```
```


