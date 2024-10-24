# Check Your Code Against the Following Points

1. If the function definition line is too long, place each parameter on a new line.
```
def long_function_name(
        var_one,
        var_two,
        var_three,
        var_four
) -> None:
```

2. Use absolute imports only.

Good example:
```python
from app.module import Component
```

Bad example:
```python
from .module import Component
```
