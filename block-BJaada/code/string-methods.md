Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

#### Getting To Know String Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (4-5 times to understand)
2. Data types of parameters
3. Return value type
4. Write three examples
5. In your own words and one sentence explain what this method does.

Example:

1. `charAt`

   - Parameter: (index) defaults to 0 - (number data type)
   - Return: character at specific index in the string (string data type)
   - Example:
     ```js
     let name = 'Arya Stark';
     name.charAt(2); //"y"
     let sentance = 'A quick brown fox jumped over a lazy dog';
     sentance(4); // "i"
     let houseName = 'Starks';
     houseName.charAt(0); // "S"
     ```
   - `charAt` accepts a index (number data type) and return the character on that index in the string.

2. `toUpperCase`
    return- it convert lower case to upper case and accept only string value.
        EXAMPLE-
```js
    let name = `arya`;
    name.toupperCase();
```
3. `toLowerCase`
    return- it convert upper case to  lower case and accept only string value.
        EXAMPLE-
```js
    let name = `ARYA`;
    name.toLowerCase();
```

4. `trim` ``
```js
it reomves space from start and end    
 Example :
 let name = "   Ey"
 name.trim()
 Ey

```
5. `trimEnd`
```js
it reomves space from end
name = "   arya   "
"   arya   "

name.trimend()

"   arya"
```
6. `trimStart`

```js
it reomves space from start 
name = "   arya   "
"   arya   "

name.trimStart()

"arya   "
```
7. `concat`
It is used to concat to stirng
example
name = " ar  ya"
" ar  ya"
name.concat()
" ar  ya"
s = "dd"
"dd"
name.concat(s)
" ar  yadd" 
8. `endsWith`
9. `includes`
10. `indexOf`
11. `lastIndexOf`
12. `padEnd`
13. `padStart`
14. `repeat`
15. `replace`
16. `slice`
17. `split`
18. `substring`
