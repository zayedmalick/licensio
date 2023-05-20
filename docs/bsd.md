# BSD License (BSD) - Module Documentation

The BSD license module provides a function to generate a BSD License (BSD) license statement.

### Function: `getBSD(year: int, name: str) -> str`

Generates a BSD license statement.

**Parameters:**

- `year` (int): The year of the dedication.
- `name` (str): The name of the person making the dedication.

**Returns:**

- `str`: The BSD license statement.

**Example:**

```python
from licensio.bsd import getBSD

# Generate BSD license statement
bsd_license = getBSD(year=2023, name="Your Name")

# Print the license statement
print(bsd_license)
```