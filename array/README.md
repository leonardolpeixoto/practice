# Array

## Definition

## Create an array
```js
const fruits = ['Apple', 'Banana']
```

## Access an Array item using the index position
```js
let apple = fruits[0]
let banana = fruits[fruits.length - 1]
```

## Loop over an Array
```js
fruits.forEach(fruit => console.log(fruit))
```

## Add an item to the end of an Array
```js
const newLength = fruits.push('Orange')
```
## Remove an item from the end of an Array
```js
const last = fruits.pop()
```

## Remove an item from the beginning of an Array
```js
const first = fruits.shift()
```

## Add an item to the beginning of an Array
```js
const newLength = fruits.unshift('Strawberry'))
```

## Find the index of an item in the Array
```js
let index = fruits.indexOf('Banana')
```

## Remove an item by index position
```js
let fruit = fruits.splice(index, 1)
```

## Copy an Array
```js
const fruitsCopy = fruits.slice()
```