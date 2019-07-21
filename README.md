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


*Student's Final Grade*
https://www.codewars.com/kata/5ad0d8356165e63c140014d4
```javascript
function finalGrade(exam, projects) {
  if(exam > 90 || projects > 10) return 100;
  if(exam > 75 && projects >= 5) return 90;
  if(exam > 50 && projects >= 2) return 75;
  return 0;
 } 
 ```
 
 
 *Get list sum recursively*
 https://www.codewars.com/kata/57a84137cf1fa5f9f80000d6
 ```javascript
 function sumR(x) {
 
   if(x.length === 0){
   return 0;
   } else {
   return x.shift() + sumR(x);
   }
 }
=============== or =================
 function sumR(x) {
  let sum = 0;
   for(let i = 0; i < x.length; i++) {
   if( typeof x[i] === 'string') {
   x[i] = Number (x[i]);
   }
   sum += x[i];
   } 
   return sum;
 }
 ```
 
 
 *Switch it Up!*
 https://www.codewars.com/kata/5808dcb8f0ed42ae34000031
 ```javascript
 function switchItUp(number){
 let arr = ['Zero', 'One', 'Two', 'Three', 'Four', 'Five', 'Six', 'Seven', 'Eight', 'Nine'];
 return arr[number];
 
 }
 ```
 
 
 *Super Duper Easy*
 https://www.codewars.com/kata/55a5bfaa756cfede78000026
 ```javascript
 function problem(x){
 
   if( typeof x === 'number') return x * 50 + 6;
   if( typeof x === 'string') return "Error";
 }
 ```
 
 
 *sPoNgEbOb MeMe*
 https://www.codewars.com/kata/5982619d2671576e90000017
 ```javascript
 function spongeMeme(sentence) {
   let newStr = '';
   for(let i = 0; i < sentence.length; i++) {
   if( i % 2 === 0) {
   newStr += sentence[i].toUpperCase();
   } else {
   newStr += sentence[i].toLowerCase();
   }
   }
   return newStr;
 }
 ```
 
 
 *Grasshopper - Summation*
 https://www.codewars.com/kata/55d24f55d7dd296eb9000030
 ```javascript
 function summation(num) {
   let summation = 0;
   for(i = 0; i <= num; i++) {
   summation += i;
  } 
  return summation;
 }
 ```
 
 *Unfinished Loop - Bug Fixing #1*
 https://www.codewars.com/kata/55c28f7304e3eaebef0000da
 ```javascript
 function createArray(number){
   var newArray = [];
   
   for(var counter = 1; counter <= number; counter++){
     newArray.push(counter);
   }
   
   return newArray;
 }
 ```
 
 *A Gift Well Spent*
 https://www.codewars.com/kata/54554846126a002d5b000854
 ```javascript
 var buy = function(x, arr) {
   let res = [];
   for (let i = 0; i < arr.length - 1; i++) {
     for (let q = i + 1; q < arr.length; q++) {
 
       if (arr[i] + arr[q] === x) {
         return [i, q];
       }
     }
   }
   return null;
 };
 ```
 
 *Maximum Triplet Sum (Array Series #7)*
 https://www.codewars.com/kata/5aa1bcda373c2eb596000112
 ```javascript
 function maxTriSum(numbers){
  let sum = 0;
   let res = numbers.sort((a, b) => b - a);
   let arr = [];
   for (let i = 0; i < res.length; i++){
     if (arr.length >= 3){
       break
     }
     if (!arr.includes(res[i])){
       arr.push(res[i]);
       sum += res[i];
     }
   }
  return sum;
 }
 ```
 
 