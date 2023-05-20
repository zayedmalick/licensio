# CC0 License (CC0) - Module Documentation

The CC0 license module provides a function to generate a CC0 License (CC0) license statement.

### Function: `getCC0(year: int, name: str) -> str`

Generates a CC0 license statement.

**Parameters:**

- `year` (int): The year of the dedication.
- `name` (str): The name of the person making the dedication.

**Returns:**

- `str`: The CC0 license statement.

**Example:**

```python
from licensio.cc0 import getCC0

# Generate CC0 license statement
cc0_license = getCC0(year=2023, name="Your Name")

# Print the license statement
print(cc0_license)
```