# AGPL License (AGPL) - Module Documentation

The AGPL license module provides a function to generate a AGPL License (AGPL) license statement.

### Function: `getAGPL(year: int, name: str) -> str`

Generates an AGPL license statement.

**Parameters:**

- `year` (int): The year of the dedication.
- `name` (str): The name of the person making the dedication.

**Returns:**

- `str`: The AGPL license statement.

**Example:**

```python
from licensio.agpl import getAGPL

# Generate AGPL license statement
agpl_license = getAGPL(year=2023, name="Your Name")

# Print the license statement
print(agpl_license)
```