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

*Sum of positive*
https://www.codewars.com/kata/5715eaedb436cf5606000381
```javascript
function positiveSum(arr) {
  let res = 0;
  for(let i = 0; i < arr.length; i++){
    if(arr[i] > 0) {
    res += arr[i];
    }
  }
  return res;
}
```
*Remove First and Last Character*
https://www.codewars.com/kata/56bc28ad5bdaeb48760009b0
```javascript
function removeChar(str){
  let str1 = '';
  for(let i = 1; i < str.length-1; i++){
  str1 +=str[i];
  }  
  return str1;
}
```

*Will you make it?*
https://www.codewars.com/kata/5861d28f124b35723e00005e
```javascript
function zeroFuel (distanceToPump, mpg, fuelLeft) {
  if (distanceToPump <= mpg * fuelLeft) return true;
  else return false;
}
```

*Capitalization and Mutability*
https://www.codewars.com/kata/595970246c9b8fa0a8000086
```javascript
function capitalizeWord(word) {
 let wordNew = word[0].toUpperCase();
 for(let i = 1; i < word.length; i++){
 wordNew += word[i];
 }
 return wordNew;
}
```

*Count Odd Numbers below n*
https://www.codewars.com/kata/59342039eb450e39970000a6
```javascript
function oddCount(n){
  return Math.floor(n/2)
}
```

*Multiples of 3 or 5*
https://www.codewars.com/kata/514b92a657cdc65150000006
```javascript
function solution(number){
  let sum = 0;
  for(let i = 3; i < number; i++) {
  if(i % 3 === 0 || i % 5 === 0) {
  sum += i;
  }
 }
   return sum;
}
```

*Who is going to pay for the wall?*
https://www.codewars.com/kata/58bf9bd943fadb2a980000a7
```javascript
function whoIsPaying(name){
  let arr = [name];
  let str =name.substring(0, 2);
  if (name. length > 2) {
  arr.push(str)
  } 
  return arr;
}
```


*Array plus array*
https://www.codewars.com/kata/5a2be17aee1aaefe2a000151
```javascript
function arrayPlusArray(arr1, arr2) {
  let sum = 0;
  for(let i = 0; i < arr1.length; i++) {
  sum += arr1[i];
  }
  for(let i = 0; i < arr2.length; i++) {
  sum += arr2[i];
  }
  return (sum);
  }
```


*Man in the west*
https://www.codewars.com/kata/59bd5dc270a3b7350c00008b
```javascript
function checkTheBucket(bucket){
  let gols = 'gold';
  for( let i = 0; i < bucket.length; i++) {
  if (bucket [i] === 'gold') {
  return true;
  }
  }
  return false;
}
```


*Reversed Strings*
https://www.codewars.com/kata/5168bb5dfe9a00b126000018
```javascript
function solution(str){
  let str1 = "";
  for( let i = str.length - 1; i >= 0; i--) {
  str1 += str[i];
  }
  return str1;
}
```

*Pick a Set of First Elements*
https://www.codewars.com/kata/572b77262bedd351e9000076
```javascript
function first(arr, n = 1) {
  let array = [];
  if(n > arr.length) return arr;
  for (let i = 0; i <n; i++) {
    array.push(arr[i]);
    //array += arr[i];
    }
  return array;
}
```

*Convert a string to an array*
https://www.codewars.com/kata/57e76bc428d6fbc2d500036d
```javascript
function stringToArray(string){
  return string.trim().split(' ');
}
```


*If you can't sleep, just count sheep!!*
https://www.codewars.com/kata/5b077ebdaf15be5c7f000077
```javascript
var countSheep = function (num){
  let murmur = '';
  for( let i = 0; i < num; i++){
  murmur += (i + 1) + ' sheep...';
  }
  return murmur;
}
```


*Opposite number*
https://www.codewars.com/kata/56dec885c54a926dcd001095
```javascript
function opposite(number) {
  return -number;
}
```


*The Feast of Many Beasts*
https://www.codewars.com/kata/5aa736a455f906981800360d
```javascript
function feast(beast, dish) {
  if(beast[0] === dish[0] && beast[beast.length - 1] === dish[dish.length - 1]){
  return true;
  } else {
  return false;
 }
}
```

*Simple multiplication*
https://www.codewars.com/kata/583710ccaa6717322c000105
```javascript
function simpleMultiplication(number) {
    return number % 2 ? number * 9 : number * 8;
    }
```


*Type of sum*
https://www.codewars.com/kata/5a2e9ae2b6cfd7692a0000ba
```javascript
function typeOfSum(a, b) { 
  return typeof(a+b);
}
```


*Reverse a Number*
https://www.codewars.com/kata/555bfd6f9f9f52680f0000c5
```javascript
function reverseNumber(n) {
  if(n >= 0) {
  let arr = n.toString().split('').reverse();
  return +(arr.join(''));
  } else {
  n = n * (-1);
  let arr = n.toString().split('').reverse();
  return (-1) * (arr.join(''));
  }
}
```
