# Optional one-liner algos

Congratulations on getting here !!! :)

This last (optional) challenge is pretty interesting.

The exercises aren't necessarily difficult, but there is a catch ! You will have to solve them with one line, with the implicit return of an arrow function.

So you're code should look like :

```js
const myFunc = ()=> //Your code here in one line
```

---

### 1.

Create a function that remove duplicates from an array.

ex:

```js
removeDuplicates([4, 9, 5, 1, 3, 2, 4, 1, 8]);
// Result : [4, 9, 5, 1, 3, 2, 8]

removeDuplicates(["hello", "world", "goodbye", "world"]);
// Result : ['hello', 'world', 'goodbye']

removeDuplicates([true, true, false, true, true, false]);
// Result : [true, false]
```

---

### 2.

Create a function that capitalizes a string.

ex:

```js
capitalize("belgium");
// Result : "Belgium"

capitalize("brazil");
// Result : "Brazil"

capitalize("brussels");
// Result : "Brussels"
```

---

### 3.

Find the days between 2 given days

ex :

```js
dayDif(new Date("2020-10-21"), new Date("2021-10-22"));
// Result : 366
```

---

### 4.

Find the average between multiple numbers using reduce method.

ex:

```js
average(1, 2, 3, 4);
// Result: 2.5
```

---

### 5.

Get the Smallest Element of an Array

ex :

```js
const arr = [13, 7, 11, 3, 9, 15, 17];

getSmallest(arr);
// Result: 3
```

---

### 6.

Check if Two Arrays Contain the Same Values

ex :

```js
const arr1 = [1, 2, 3, 4];
const arr2 = [3, 1, 4, 2];
const arr3 = [1, 2, 3];

areEqual(arr1, arr2);
// Result : true

areEqual(arr1, arr3);
// Result : false
```

---

### 7.

Create a function that generates a random rgb value. The outcome should be the same as we declare it in CSS : rgb(?, ?, ?)

ex :

```js
randomRGB();
// Result : "rgb(232, 115, 164)"
```

---

### 8.

Create a function that takes a `string` and a `letter` and counts how many times the letter appears in the string

ex :

```js
occurencies("hello", "l");
// Result : 2

occurencies("abracadabra", "a");
// Result : 5

occurencies("oups", "z");
// Result : 0
```

---

### 9.

Create a function that returns the sum of all positive numbers in an array. (negative numbers should be ignored).
If only negative numbers are present, it should return 0

ex :

```js
onlyPositives([1, 6, 2, -3, 5, -12]);
// Result : 14

onlyPositives([-3, -4, -2]);
// Result : 0
```

---

### 10.

Create a function that takes an `array of objects` and an `object` with one key/value pair as arguments.
The function should return every entries that are the same than the object.

(This exercise will be very usefull in many scenarios later in the future)

Example :

```js
scanAndFind(
  [
    {
      firstName: "Vito",
      lastName: "Corleone",
    },
    {
      firstName: "Jon",
      lastName: "Snow",
    },
    {
      firstName: "Harry",
      lastName: "Potter",
    },
    {
      firstName: "Michal",
      lastName: "Corleone",
    },
  ],
  {
    lastName: "Corleone",
  }
);

// Result : [{firstName: Vito, lastName: Corleone}, {firstName: Michael, lastName: Corleone}]

scanAndFin(
  [
    { fullName: "Roi Baudoin", id: 49762 },
    { fullName: "Margareth Tatcher", id: 94357 },
    { fullName: "Barack Obama", id: 76458 },
    { fullName: "Emmanuel Macron", id: 10687 },
    { fullName: "Charles de Gaulle", id: 67098 },
    { fullName: "Boris Johnson", id: 16437 },
  ],
  { id: 10687 }
);
// Result : [{fullName: "Emmanuel Macron", id: 10687}]
```

---

**CONGRATULATIONS !!!**

One small reminder :

Making it one liner is not always the best solution !

If readability is compromised, you should really choose an easier-to-read solution.

This was just for practice ! ;)
