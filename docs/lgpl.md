# LGPL License (LGPL) - Module Documentation

The LGPL license module provides a function to generate a LGPL License (LGPL) license statement.

### Function: `getLGPL(year: int, name: str) -> str`

Generates a LGPL license statement.

**Parameters:**

- `year` (int): The year of the dedication.
- `name` (str): The name of the person making the dedication.

**Returns:**

- `str`: The LGPL license statement.

**Example:**

```python
from licensio.lgpl import getLGPL

# Generate LGPL license statement
lgpl_license = getLGPL(year=2023, name="Your Name")

# Print the license statement
print(lgpl_license)
```