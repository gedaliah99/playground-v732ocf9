# PYTHON: Fill-in-the-Blanks Program

If you're given a string that has "blanks" (underscores) and an array of words, you can easily fill in the blanks to that string:

## Program:
```python runnable
string = "This _ a _ really _ _"

words = ["is", "really,", "long", "string."]

for i in words:
    string = string.replace("_", i, 1)

print(string)
```
Try it out for yourself, the underscores will be replaced by each word in ```words```.


Feel free to use this code for yourself.

Happy Coding,
@Code-Parser