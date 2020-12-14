# renpy-mods-system
Mods system for Renpy7

# Using
Add this string to you screen
```python
modList()
```

to add a custom mod write this line at the beginning of the file
```python
init python:
    mods["label_name"] = "mod_name"
```

### Example
```python
init python:
    mods["es2"] = "Everlasting Summer 2.0"
```
