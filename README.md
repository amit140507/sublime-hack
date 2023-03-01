## Remove Line space
`CTRL`+`H`
type ```^\n```  or `^(\r|\n\r?)`
Replace with Nothing.

## ReIndentation Key Binding

Go to Preference -> Key Binding
Add this code
```
[
	{ "keys": ["ctrl+shift+x"], "command": "reindent"}
]
```
