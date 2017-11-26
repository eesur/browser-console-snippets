# browser-console-snippets
useful snippets for working in the browser

-----------------

### add a library to page

Example showing d3 added so it can be used to play with a page it's not loaded on :)

```js
const s = document.createElement('script')
s.src = 'https://d3js.org/d3.v4.min.js'
document.body.appendChild(s)
```

-----------------

### Copying arrays form console: 

Let say the outputted array is `var data = [{x:"xyz"}, {y:"foo"}, {z:"baz"}]`  
You can use `copy` command in console as follows: 
```
copy(data)
```
array/object is now available to the clipboard. You can now use `Ctrl+V/Cmd+V` to use paste in a txt editor 

if needed you can [stringify](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify):
```
 copy(JSON.stringify(data))
```
*may want to use  [jsbeautifier](http://jsbeautifier.org/) prior pasting into text editor 

-----------------

### shuffle an array

```
const data = [0, 1, 2, 3, 4, 5, 6]

const shuffleArray = d => d.sort(() => Math.random() - 0.5)

const randomOrder = shuffleArray(data.slice())
```

-----------------
