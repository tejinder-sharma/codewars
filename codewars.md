# Code Wars

```js
function squareSum(numbers){
  const initialValue = 0;
 return ( numbers.reduce(
  (previousValue, currentValue) => previousValue  + currentValue * currentValue, initialValue
)
         )
}
```
