# WTFPL License (WTFPL) - Module Documentation

The WTFPL license module provides a function to generate a WTFPL License (WTFPL) license statement.

### Function: `getWTFPL(year: int, name: str) -> str`

Generates a WTFPL license statement.

**Parameters:**

- `year` (int): The year of the dedication.
- `name` (str): The name of the person making the dedication.

**Returns:**

- `str`: The WTFPL license statement.

**Example:**

```python
from licensio.wtfpl import getWTFPL

# Generate WTFPL license statement
wtfpl_license = getWTFPL(year=2023, name="Your Name")

# Print the license statement
print(wtfpl_license)
```