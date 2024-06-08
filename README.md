## Basic Operations

1. Check if a variable is an array:
    ```javascript
    Array.isArray(variable);

2. Check if a variable is an object (excluding null):
    ```javascript
    typeof variable === 'object' && variable !== null;

3. Convert a string to uppercase:
    ```javascript 
    'hello'.toUpperCase();

4. Convert a string to lowercase:
    ```javascript
    'HELLO'.toLowerCase();
    
5. Generate a random number between 0 and 1:
    ```javascript
    Math.random();

6. Generate a random number between a specific range (e.g., 1 and 10):
    ```javascript
    Math.floor(Math.random() * (max - min + 1)) + min;

7. Get the current date and time:
    ```javascript
    new Date();

8. Remove duplicate elements from an array:
    ```javascript
    [...new Set(array)];

9. Reverse a string:
    ```javascript
    'hello'.split('').reverse().join('');

10. Check if a string contains another string:
    ```javascript
    'hello world'.includes('world');

11. Check if an object has a specific property:
    ```javascript
    'propertyName' in object;

12. Flatten an array of arrays:
    ```javascript
    array.flat();

13. Convert a number to a string with a specific number of decimal places:
    ```javascript
    number.toFixed(decimalPlaces);

14. Convert a string to a number:
    ```javascript
    parseInt('10');

15. Sort an array in ascending order:
    ```javascript
    array.sort((a, b) => a - b);

16. Get the unique values from an array:
    ```javascript
    [...new Set(array)];

17. Check if a number is an integer:
    ```javascript
    Number.isInteger(number);

18. Get the last element of an array:
    ```javascript
    array[array.length - 1];

19. Truncate a string to a specific length and add ellipsis if it exceeds:
    ```javascript
    string.length > maxLength ? string.substring(0, maxLength) + '...' : string;

20. Check if a variable is undefined:
    ```javascript
    typeof variable === 'undefined';
