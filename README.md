# select4sh

## Name
select4sh - element selection for shell

## Usage
```bash
array=(a b c)
selected=$(select4sh $array)
#Then you choose an element with arrow keys(up/down) and return key.
echo $selected
```
```bash
selected=$(select4sh -p "Select:" $array)
#Then a prompt appears before options.
Select:a
```
```bash
selected=$(select4sh a b c d e)
#Argument is available even if it is not an array
```

## License
MIT
