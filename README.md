# select4sh

## Name
select4sh - element selection for shell

## Usage
```bash
selected=$(select4sh a b c d e)
#Then you choose an element with arrow keys(up/down) and return key.
echo $selected
```
```bash
selected=$(select4sh -p "Select:" a b c d e)
#Then a prompt appears before options.
Select:a
```
```bash
array=(a b c)
selected=$(select4sh ${array[@]})
#Argument is available even if it is an array
```
```bash
selected=$(select4sh -a a b c d e)
#Then all options appear.
a #Only the active option is highlighted.
b
c
d
e
```

## License
MIT
