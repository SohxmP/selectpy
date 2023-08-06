# SelectPy ( selectpy )
Selectpy is a simple python module to integrate a fully customizable select menu in your python projects.

## How To Use

Installing The Module

```python
pip install selectpy
```

Importing The Module in The Project

```python
from selectpy import select
```

Adding The Select Menu And Getting The Result

```python
ans = select(["Option 1", "Option 2"], "Choose an Option:", c=">", cursor_color="#ff0000", selected_color="#ff0000", unselected_color="#ffffff")
print(ans)
```

Output

```
Choose an Option
> Option 1
  Option 2

Option 1
```
