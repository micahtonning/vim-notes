# Macros
## Python dict to var
Easily convert a python "key" : value pair to var = value
```python
dictionary = {
  "name" : "Jeff",
  "age" : 42,
  "height" : 4.2,
}
# convert to 
# name = "Jeff"
# age = 42
# height = 4.2
```
Save one of the following to your clipboard.   

 - _Keys with double quotes_
```bash
0f"xf"xf:r=$x+
```
 - _Keys with single quotes_
```bash
0f'xf'xf:r=$x+
```
Move your cursor to the line you want to edit.   
Run the following in vim
```ex
@*
```
### Notes
- The macro will remove the last character of the line.   
- The key should be a string with all double quotes or all single quotes.   
