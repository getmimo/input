# @mimo-org/input-sync

A simple, synchronous input function to read from stdin, inspired by Python's `input()`.

## Installation

```bash
npm install @mimo-org/input-sync
```

## Usage

```javascript
const input = require('@mimo-org/input-sync');

const name = input('Enter your name: ');
console.log(`Hello, ${name}!`);
```
