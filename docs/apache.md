# Apache License (Apache) - Module Documentation

The Apache license module provides a function to generate a Apache License (Apache) license statement.

### Function: `getApache(year: int, name: str) -> str`

Generates an Apache license statement.

**Parameters:**

- `year` (int): The year of the dedication.
- `name` (str): The name of the person making the dedication.

**Returns:**

- `str`: The Apache license statement.

**Example:**

```python
from licensio.apache import getApache

# Generate Apache license statement
apache_license = getApache(year=2023, name="Your Name")

# Print the license statement
print(apache_license)
```