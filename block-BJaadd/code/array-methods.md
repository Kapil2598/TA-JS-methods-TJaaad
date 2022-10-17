Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

## Getting To Know Array Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (2-3 times to understand)
2. Data types of parameters
3. Return value type
4. Write three examples
5. In your words what this method does.
6. Does it mutate the original value or not (check https://doesitmutate.xyz)

Example:

1. `concat`

   - Parameter: n (any) number of values (number, string, boolean, array, null, undefined, object and function etc)
   - Return: a single Array consisting of by all the values passed as parameters in the same order.
   - Example:
     ```js
     let numbers = [1, 2, 3];
     numbers.concat(4); //[1,2,3,4]
     let sentanceArray = 'A quick brown fox jumped over a lazy'.split(' ');
     sentanceArray.concat('dog').join(' '); //"A quick brown fox jumped over a lazy dog"
     let colors = ['red', 'green', 'blue'];
     colors.concat('black', 'red', 21, true); // ['red','green','blue','black', 'red', 21, true]
     ```
   - `concat` accepts n number of values and returns one array with all the values in same order. It does not change the original array.
   - No it does not mutate the original array

2. `join`
  parameter - it is optional. but we also give a saparator(" ,")
  return - a string thath joined the element
Example:
 ```js
     a= [ `yash`, `vardhan`];
Array [ "yash", "vardhan" ]

a.join("")

"yashvardhan"
     ```


3. `flat`

parameter - depth
return - a new array
Example:
``
   b = [1,2,[3,334,[44]]];
Array(3) [ 1, 2, (3) […] ]

b.flat()
Array(5) [ 1, 2, 3, 334, (1) […] ]
```

4. `push`
parameter - used to add a alement to last
return - new length
mutate- yes
eg-
```js
a = [1,2,3]
a.push(4);
```

5. `indexOf`
parameter - search
return - index of an element
no mutate
eg -
``` js
c= [1,2,3];
c.indexof(2);
```

6. `lastIndexOf`

parameter - search backward
return - index of an element
no mutate
eg -
``` js
c= [1,2,3];
c.lastindexof(2);
```

7. `includes`
parameter - search backward
return -boolean value
no mutate
eg -
``` js
c= [1,2,3];
c.includes(2);
```

8. `reverse`
parameter - 
return - reverse array
 mutate
eg -
``` js
c= [1,2,3];
c.reverse();
```

9. `every`
10. `shift`
11. `splice`
12. `find`
13. `unshift`
14. `findIndex`
15. `filter`
16. `flat`
17. `forEach`
18. `map`
19. `pop`
20. `reduce`
21. `slice`
22. `some`
