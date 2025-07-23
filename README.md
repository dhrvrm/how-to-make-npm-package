# how-to-make-npm-package

# string-manipulation-exampless

A simple npm package for common string manipulation functions: capitalize first letter, slugify text, truncate string, and reverse words.

## Installation

```bash
npm install string-manipulation-exampless
```

## Usage

```js
import {
  capitalizeFirstLetter,
  slugifyText,
  truncateString,
  reverseWords
} from 'string-manipulation-exampless';

console.log(capitalizeFirstLetter('hello')); // "Hello"
console.log(slugifyText('My Awesome Article!')); // "my-awesome-article"
console.log(truncateString('This is a long sentence.', 10)); // "This is a ..."
console.log(reverseWords('hello world')); // "world hello"
```

## API

### capitalizeFirstLetter(str: string): string
Returns the string with the first letter capitalized.

### slugifyText(str: string): string
Converts a string into a URL-friendly slug.

### truncateString(str: string, maxLength: number): string
Truncates the string to the specified length, adding "..." if needed.

### reverseWords(str: string): string
Reverses the order of words in a sentence.

## License
MIT
