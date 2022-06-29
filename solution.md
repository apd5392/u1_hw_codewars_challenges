## Return Negative
function makeNegative(num) {
  if (num < 0){
    return num;
  } else {
    return num = num * -1
  }
}
makeNegative(1)

## Sum of Positive

function positiveSum(arr) {
  let sum = 0;
  for (let i = 0; i < arr.length; i++){
    if (arr[i] > 0)
    sum += arr[i];
    }
  return sum
}

## Function 2

function square(num){
  return num*num
}


## Sum Arrays

// Sum Numbers
function sum(numbers) {
  let sum = 0;('use strict')
  for (let i = 0; i < numbers.length; i++) {
    if (numbers[i] !== 0) {
      sum += numbers[i]
    }
  }
  return sum
}

## Reversed Strings

function solution(str){
  return str.split('').reverse().join('');
}

solution('world')

Sources used:
freecodecamp.com
w3schools.com