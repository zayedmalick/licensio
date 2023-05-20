# GNU License (GNU) - Module Documentation

The GNU license module provides a function to generate a GNU License (GNU) license statement.

### Function: `getGNU(year: int, name: str) -> str`

Generates a GNU license statement.

**Parameters:**

- `year` (int): The year of the dedication.
- `name` (str): The name of the person making the dedication.

**Returns:**

- `str`: The GNU license statement.

**Example:**

```python
from licensio.gnu import getGNU

# Generate GNU license statement
gnu_license = getGNU(year=2023, name="Your Name")

# Print the license statement
print(gnu_license)
```