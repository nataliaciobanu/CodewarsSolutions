*Sleigh Authentication*
https://www.codewars.com/kata/52adc142b2651f25a8000643
```javascript
function Sleigh() {}

Sleigh.prototype.authenticate = function(name, password) {
  if(name === 'Santa Claus' && password === 'Ho Ho Ho!') return true;
  if(name === 'Santa' && password === 'Ho Ho Ho!') return false;
  if(name === 'Santa Claus' && password === 'Ho Ho!') return false;
  if(name === 'jhoffner' && password === 'CodeWars') return false;
  return false;
};
```
*Return Negative*
https://www.codewars.com/kata/55685cd7ad70877c23000102
```javascript
function makeNegative(num) {
  if(num <= 0) {
    return num
  } else {
    return -num;
  }
}
```

*Even or Odd*
https://www.codewars.com/kata/53da3dbb4a5168369a0000fe
```javascript
function even_or_odd(n) {
  if(n % 2 === 0) return 'Even';
  else return 'Odd';
  }
```
