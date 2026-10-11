# json-flatten

Utilities for turning nested dictionaries into dotted keys and back.

## Why

I kept rewriting the same thirty lines in every project, so I pulled them out.

## Install

```bash
pip install json-flatten
```

## Usage

```python
from json_flatten import jsonFlatten

result = jsonFlatten("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
