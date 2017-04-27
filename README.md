# browser-console-snippets
useful snippets for working in the browser

-----------------

### Copying arrays form console: 

Let say the outputted array is `var data = [{x:"xyz"}, {y:"foo"}, {z:"baz"}]` You can use command in console as follows: 
```
 copy(JSON.stringify(data))
```
array/objsect is now available to the clipboard. You can now use `Ctrl+V/Cmd+V` to use paste in a txt editor (may want to use  [jsbeautifier](http://jsbeautifier.org/) prior pasting) 

[source](http://stackoverflow.com/a/41032640)


-----------------
