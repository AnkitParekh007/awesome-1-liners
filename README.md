# One-Liner JavaScript Code Snippets 

## For Arrays
This file contains a collection of useful one-liner JavaScript code snippets for array manipulation and operations. These snippets cover various common tasks and scenarios encountered while working with arrays in JavaScript.

## Snippets

| #   | Description                                                                                         | Code Snippet                                                                                                       |
| --- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| 1   | Concatenate two arrays                                                                              | `array1.concat(array2);`                                                                                          |
| 2   | Clone an array                                                                                      | `[...array];`                                                                                                     |
| 3   | Remove the last element from an array                                                               | `array.pop();`                                                                                                    |
| 4   | Add elements to the end of an array                                                                 | `array.push(element1, element2);`                                                                                 |
| 5   | Remove the first element from an array                                                              | `array.shift();`                                                                                                  |
| 6   | Add elements to the beginning of an array                                                           | `array.unshift(element1, element2);`                                                                              |
| 7   | Get the length of an array                                                                          | `array.length;`                                                                                                   |
| 8   | Find the index of an element in an array                                                            | `array.indexOf(element);`                                                                                         |
| 9   | Check if an array includes a specific element                                                       | `array.includes(element);`                                                                                        |
| 10  | Reverse an array                                                                                    | `array.reverse();`                                                                                                |
| 11  | Sort an array (in place)                                                                            | `array.sort();`                                                                                                   |
| 12  | Create a new array with elements filtered based on a condition                                       | `array.filter(element => condition);`                                                                             |
| 13  | Create a new array with elements mapped based on a function                                          | `array.map(element => transformedElement);`                                                                       |
| 14  | Flatten a nested array                                                                              | `array.flat();`                                                                                                   |
| 15  | Get the first n elements of an array                                                                | `array.slice(0, n);`                                                                                             |
| 16  | Get the last n elements of an array                                                                 | `array.slice(-n);`                                                                                                |
| 17  | Find the maximum element in an array                                                                | `Math.max(...array);`                                                                                             |
| 18  | Find the minimum element in an array                                                                | `Math.min(...array);`                                                                                             |
| 19  | Check if all elements in an array satisfy a condition                                                | `array.every(element => condition);`                                                                              |
| 20  | Check if any element in an array satisfies a condition                                               | `array.some(element => condition);`                                                                               |
| 21  | Convert an array to a string                                                                        | `array.join(separator);`                                                                                          |
| 22  | Remove elements from an array at specific positions                                                 | `array.splice(index, count);`                                                                                     |
| 23  | Replace elements in an array at specific positions                                                   | `array.splice(index, count, newElement1, newElement2);`                                                           |
| 24  | Find the sum of all elements in an array                                                            | `array.reduce((accumulator, currentValue) => accumulator + currentValue, initialValue);`                         |
| 25  | Find the average value of elements in an array                                                      | `array.reduce((accumulator, currentValue) => accumulator + currentValue, 0) / array.length;`                     |
| 26  | Create an array filled with a specific value                                                        | `Array(length).fill(value);`                                                                                     |
| 27  | Remove duplicate elements from an array                                                             | `[...new Set(array)];`                                                                                            |
| 28  | Check if two arrays are equal                                                                      | `array1.every((value, index) => value === array2[index]) && array1.length === array2.length;`                    |
| 29  | Find the union of two arrays (unique elements from both arrays)                                      | `[...new Set([...array1, ...array2])];`                                                                           |
| 30  | Find the intersection of two arrays (common elements in both arrays)                                 | `array1.filter(value => array2.includes(value));`                                                                 |
| 31  | Find the difference between two arrays (elements present in the first array but not in the second)   | `array1.filter(value => !array2.includes(value));`                                                                |
| 32  | Check if an array is empty                                                                         | `array.length === 0;`                                                                                             |
| 33  | Check if an array is not empty                                                                     | `array.length !== 0;`                                                                                             |
| 34  | Find the last index of a specific element in an array                                               | `array.lastIndexOf(element);`                                                                                     |
| 35  | Convert an array-like object to an array                                                            | `Array.from(arrayLikeObject);`                                                                                    |
| 36  | Iterate over array elements using a for loop                                                        | `for (let i = 0; i < array.length; i++) { /* access array[i] */ }`                                                |
| 37  | Iterate over array elements using forEach method    | `array.forEach(element => { /* process element */ });`                                                                                                                         |
   | 38  | Iterate over array elements using for...of loop                                                                                                                        | `for (const element of array) { /* process element */ }`                                                                                                                     |
   | 39  | Find the first occurrence of a specific element in an array                                                                                                           | `array.find(element => condition);`                                                                                                                                            |
   | 40  | Check if an array is a subset of another array                                                                                                                        | `array.every(element => otherArray.includes(element));`                                                                                                                      |
   | 41  | Check if an array contains only unique elements                                                                                                                       | `new Set(array).size === array.length;`                                                                                                                                        |
   | 42  | Shuffle an array                                                                                                                                                     | `array.sort(() => Math.random() - 0.5);`                                                                                                                                       |
   | 43  | Remove falsy values (false, null, 0, "", undefined, and NaN) from an array                                                                                            | `array.filter(Boolean);`                                                                                                                                                      |
   | 44  | Get the n smallest elements from an array                                                                                                                             | `array.sort((a, b) => a - b).slice(0, n);`                                                                                                                                     |
   | 45  | Get the n largest elements from an array                                                                                                                              | `array.sort((a, b) => b - a).slice(0, n);`                                                                                                                                     |
   | 46  | Group array elements based on a criterion                                                                                                                             | `array.reduce((acc, element) => { acc[criterion(element)] = acc[criterion(element)] || []; acc[criterion(element)].push(element); return acc; }, {});`                         |
   | 47  | Find the frequency of each element in an array                                                                                                                        | `array.reduce((acc, element) => { acc[element] = (acc[element] || 0) + 1; return acc; }, {});`                                                                                 |
   | 48  | Flatten a nested array (recursive)                                                                                                                                    | `array.reduce((acc, element) => acc.concat(Array.isArray(element) ? flatten(element) : element), []);`                                                                        |
   | 49  | Get the unique elements and their counts in an array                                                                                                                  | `Object.entries(array.reduce((acc, element) => { acc[element] = (acc[element] || 0) + 1; return acc; }, {}));`                                                                 |
   | 50  | Rotate elements in an array to the left by n positions                                                                                                                | `array.slice(n).concat(array.slice(0, n));`                                                                                                                                    |
   

## For Objects

| #   | Description                                                                                   | Code Snippet                                                                                                       |
| --- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| 1   | Clone an object                                                                               | `{ ...object };`                                                                                                  |
| 2   | Merge two objects                                                                             | `{ ...object1, ...object2 };`                                                                                      |
| 3   | Check if an object has a property                                                             | `'propertyName' in object;`                                                                                        |
| 4   | Get the keys of an object                                                                     | `Object.keys(object);`                                                                                            |
| 5   | Get the values of an object                                                                   | `Object.values(object);`                                                                                          |
| 6   | Check if an object is empty                                                                   | `Object.keys(object).length === 0 && object.constructor === Object;`                                               |
| 7   | Check if two objects are equal                                                                | `JSON.stringify(object1) === JSON.stringify(object2);`                                                              |
| 8   | Iterate over object keys                                                                      | `for (let key in object) { /* access object[key] */ }`                                                             |
| 9   | Iterate over object values                                                                    | `Object.values(object).forEach(value => { /* process value */ });`                                                 |
| 10  | Iterate over object entries                                                                   | `Object.entries(object).forEach(([key, value]) => { /* process key and value */ });`                               |
| 11  | Get the number of properties in an object                                                     | `Object.keys(object).length;`                                                                                     |
| 12  | Remove a property from an object (mutates the original object)                                 | `delete object.propertyName;`                                                                                     |
| 13  | Freeze an object (prevent adding or modifying properties)                                      | `Object.freeze(object);`                                                                                          |
| 14  | Seal an object (prevent adding properties, but allow modifying existing ones)                  | `Object.seal(object);`                                                                                            |
| 15  | Prevent extension of an object (prevent adding new properties, but allow modifying existing ones) | `Object.preventExtensions(object);`                                                                               |
| 16  | Get the prototype of an object                                                                | `Object.getPrototypeOf(object);`                                                                                  |
| 17  | Check if an object is an array                                                                | `Array.isArray(object);`                                                                                          |
| 18  | Get a deep copy of an object                                                                  | `JSON.parse(JSON.stringify(object));`                                                                             |
| 19  | Check if a property exists in an object (including prototype chain)                            | `object.hasOwnProperty('propertyName');`                                                                         |
| 20  | Get a property value from an object using a variable key                                        | `object[variableKey];`                                                                                            |
| 21  | Get a property value from an object with a default value if the property does not exist         | `object.propertyName || defaultValue;`                                                                            |
| 22  | Get a nested property value from an object                                                     | `object.nestedObject.propertyName;`                                                                               |
| 23  | Set a property value in an object                                                              | `object.propertyName = value;`                                                                                     |
| 24  | Merge multiple objects into one                                                                 | `Object.assign({}, object1, object2, object3);`                                                                    |
| 25  | Check if an object contains all properties of another object                                    | `Object.keys(subsetObject).every(key => object.hasOwnProperty(key) && object[key] === subsetObject[key]);`        |
| 26  | Get the first key of an object                                                                 | `Object.keys(object)[0];`                                                                                         |
| 27  | Get the last key of an object                                                                  | `Object.keys(object)[Object.keys(object).length - 1];`                                                             |
| 28  | Convert an object to an array of key-value pairs                                               | `Object.entries(object);`                                                                                         |
| 29  | Convert an array of key-value pairs to an object                                               | `Object.fromEntries(array);`                                                                                      |
| 30  | Get a property descriptor of an object's property                                              | `Object.getOwnPropertyDescriptor(object, 'propertyName');`                                                      |
| 31  | Check if an object is extensible (new properties can be added)                                  | `Object.isExtensible(object);`                                                                                    |
| 32  | Check if an object is frozen (properties cannot be added, modified, or removed)                | `Object.isFrozen(object);`                                                                                        |
| 33  | Check if an object is sealed (properties cannot be added, but existing ones can be modified or removed) | `Object.isSealed(object);`                                                                                   |
| 34  | Get an object's own property names                                                             | `Object.getOwnPropertyNames(object);`                                                                            |
| 35  | Get an object's own property symbols                                                           | `Object.getOwnPropertySymbols(object);`                                                                          |
| 36  | Create an object with a prototype                                                              | `Object.create(prototypeObject);`                                                                                  |
| 37  | Check if an object is an instance of a specific class                                           | `object instanceof ClassName;`                                                                                    |
| 38  | Check if an object is plain (created by '{}')                                                   | `Object.prototype.toString.call(object) === '[object Object]';`                                                    |
| 39  | Flatten an object (convert nested properties to a flat structure)                               | `Object.entries(object).reduce((acc, [key, value]) => { if (typeof value === 'object') { Object.assign(acc, flatten({ [key]: value })); } else { acc[key] = value; } return acc; }, {});` |
| 40  | Convert object keys to camelCase                                                                | `Object.keys(object).reduce((acc, key) => { acc[camelCase(key)] = object[key]; return acc; }, {});`               |
| 41  | Convert object keys to snake_case                                                              | `Object.keys(object).reduce((acc, key) => { acc[snake_case(key)] = object[key]; return acc; }, {});`              |
