# EPL License (EPL) - Module Documentation

The EPL license module provides a function to generate a EPL License (EPL) license statement.

### Function: `getEPL(year: int, name: str) -> str`

Generates an EPL license statement.

**Parameters:**

- `year` (int): The year of the dedication.
- `name` (str): The name of the person making the dedication.

**Returns:**

- `str`: The EPL license statement.

**Example:**

```python
from licensio.epl import getEPL

# Generate EPL license statement
epl_license = getEPL(year=2023, name="Your Name")

# Print the license statement
print(epl_license)
```