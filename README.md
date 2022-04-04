# dsna-lists-primitives

## Problem 1

### Reverse Words

Write a function that takes a sentence string and returns a new string that is the same sentence, but with each word reversed (backwards). The order of words does not change.

### Test Cases

|        input         |        output        |
| :------------------: | :------------------: |
| 'alchemy rocks gold' | 'ymehcla skcor dlog' |

#### Answer

```js
function reverseWords(sentence) {
  const words = sentence.split();
  const letter = words.split().reverse().join(" ");
  return letter;
}
console.log("alchemy rocks gold");
```

## Problem 2

### Title Case Words

Write a function that takes a sentence string and returns a new string that is the same sentence, but with the first letter of each word capitalized, and the rest lowercase

### Test Cases

|        input         |        output        |
| :------------------: | :------------------: |
| 'alchemy ROCKS goLD' | 'Alchemy Rocks Gold' |

#### Answer

```js
function titleCase(sentence) {
  const lowerCase = sentence.toLowerCase();
  const words = lowerCase
    .split(" ")
    .map((item) => {
      item.slice(0, 1).toUpperCase();
    })
    .join(" ");
  return words;
}
console.log("alchemy ROCKS goLD");
```

## Problem 3

### Fizz-buzz

Write a function that takes a positive integer n, and returns an array that contains, in order, all of the numbers from 1 to n. But for multiples of three (evenly divisible by three) print “Fizz” instead of the number and for the multiples of five use “Buzz”. For numbers which are multiples of both three and five use “FizzBuzz”.

### Test Cases

| input |                                           output                                           |
| :---: | :----------------------------------------------------------------------------------------: |
|  16   | [1, 2, 'Fizz', 4, 'Buzz', 'Fizz', 7, 8, 'Fizz', 'Buzz', 11, 'Fizz' 13, 14, 'FizzBuzz', 16] |

#### Answer

## Problem 4

### Anagrams

Write a function that takes two words as arguments and returns true if they are anagrams (contain the exact same letters) and false otherwise.

### Test Cases

|              input               | output |
| :------------------------------: | :----: |
| 'superintended', 'unpredestined' |  true  |
| 'pictorialness', 'documentarily' | false  |

## Problem 5

### Unique-string

Write a function that takes an array of strings. All strings contains similar letters except one. Try to find it!

### Test Cases

|                         input                         | output |
| :---------------------------------------------------: | :----: |
| ['Aa', 'aaa', 'aaaaa', 'BbBb', 'Aaaa', 'AaAaAa', 'a'] | 'BbBb' |
|   ['abc', 'acb', 'bac', 'foo', 'bca', 'cab', 'cba']   | 'foo'  |

#### Answer

## Probelm 6

## Unique-char

Write a function that takes a string and finds and returns the any (STRETCH: first) instance of a non-repeating character in it. If there is no such character, return `_`.

### Test Cases

|      input       |                 output                 |
| :--------------: | :------------------------------------: |
|   'abdacabad'    |                  'c'                   |
| 'abacabaabacaba' |                  `_`                   |
|    'abacabad'    | 'c' (not 'd' because it occurs second) |

#### Answer

## Problem 7

### Oddish Evenish

Write a function that determines whether a number is Oddish or Evenish. A number is Oddish if the sum of all of its digits is odd, and a number is Evenish if the sum of all of its digits is even. If a number is Oddish, return "Oddish". Otherwise, return "Evenish".

### Test Cases

| input |  output   |    because    |
| :---: | :-------: | :-----------: |
|  121  | 'Evenish' | 1 + 2 + 1 = 4 |
|  41   |  'Oddish  |   4 + 1 = 5   |

#### Answer

## Problem 8

### At

JavaScript has a new array method at. It's not yet available in all browsers, but you can write your own!

### Test Cases

|             input             | output |
| :---------------------------: | :----: |
| ['a', 'b', 'c', 'd', 'e'], 1  |  'b'   |
| ['a', 'b', 'c', 'd', 'e'], -2 |  'd'   |

#### Answer
