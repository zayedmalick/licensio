# MIT License (MIT) - Module Documentation

The MIT license module provides a function to generate a MIT License (MIT) license statement.

### Function: `getMIT(year: int, name: str) -> str`

Generates a MIT license statement.

**Parameters:**

- `year` (int): The year of the dedication.
- `name` (str): The name of the person making the dedication.

**Returns:**

- `str`: The MIT license statement.

**Example:**

```python
from licensio.mit import getMIT

# Generate MIT license statement
mit_license = getMIT(year=2023, name="Your Name")

# Print the license statement
print(mit_license)
