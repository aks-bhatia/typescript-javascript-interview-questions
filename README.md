# TypeScript & JavaScript interview Questions

Conceptual and coding interview questions on typescript and javascript.

| No. | Questions                                                                   | Topic   |
| --- | --------------------------------------------------------------------------- | ------- |
| 1   | [Explain Call, Apply and Bind](#explain-call-apply-and-bind)                | Core    |
| 2   | [Difference between slice and splice](#difference-between-slice-and-splice) | Array   |
| 3   | [Differences between object and map](#differences-between-object-and-map)   | Objects |

1. ### Explain Call, Apply and Bind.

   Call: The call() method invokes a function with a given this value and arguments provided one by one.\
   Apply: Invokes the function with a given this value and allows you to pass in arguments as an array.\
   Bind: returns a new function, allowing you to pass any number of arguments.

2. ### Difference between slice and splice.

   The slice() method returns the selected elements in an array as a new array object. It selects the elements starting at the given start argument, and ends at the given optional end argument without including the last element. If you omit the second argument then it selects till the end.\
   The splice() method is used either adds/removes items to/from an array, and then returns the removed item. The first argument specifies the array position for insertion or deletion whereas the optional second argument indicates the number of elements to be deleted. Each additional argument is added to the array.

3. ### Differences between object and map.
   Objects are very similar to maps and are used very often. Both let you set key and its value, retrieve values, find if key exists, delete keys, and check if value is stored for key.\
   Maps should be preferred when frequent addition and removal of keys is required.
   Below are few differences between objects and maps.
   1. Key type: Objects allow only String and Symbol type for keys whereas we can have any value for Map - including functions, objects, and any primitive.
   2. Key ordering: Insertion ordering is maintained in maps but not in Objects. Hence while iterating over object we don't get keys in insertion order.
   3. Finding Size: We can find the size of map easily whereas the size of the object needs to be calculated manually.
   4. Iterating: We can directly iterate over maps easily. we can iterate Object by first finding keys and iterating over it.
