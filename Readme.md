
# mutation-observer

  Exposes the `MutationObserver` constructor without testing for prefixes.

## Installation

```
$ component install component/matches-selector
```

## API

```js
require('mutation-observer')
```

will return one of the following:

```
MutationObserver
WebKitMutationObserver
MozMutationObserver
```

## License

  MIT
