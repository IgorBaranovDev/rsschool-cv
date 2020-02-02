# Igor Baranov

  ![photo](https://avatars0.githubusercontent.com/u/36860438?s=88&v=4)

## Contact:
  * phone: +37529 598-92-91
  * email: baranovigorjsdev@gmail.com
  * linkedin: [link to my profile](https://www.linkedin.com/in/igor-baranov-5807a1161/) 
  * telegram: @Baranov_Igor_dev
  * address: Belarus, Vitebsk region

  ---

## Summary:
  *The goal is to become an experienced web development professional. Why? Because I always liked to learn something new and aspecualy connected with computer technologys.*

  ---

## Skills:

  - programming languages:
	  * HTML
    * CSS(LESS, SASS)
    * JS(ES5/ES6)
    * MySQL
     
	- frameworks:
		* React	
		* node.js
    * pixiJS
    * AngularJS
    
	- other:
		* git
    * Babel
    * Webpack
    * Adobe Photoshop
    * Illustrator
    * VScode

    ---

## Code examples: 
  [Codewars - 6 kyu Backspaces in string](https://www.codewars.com/kata/5727bb0fe81185ae62000ae3/javascript)
``` JavaScript
function cleanString(s) {
const arr = s.split('');
let str;
for (let i = 0; i < arr.length; i++) {
  if (arr[i] === '#' && i === 0) {
    arr.splice([i], 1);
    } else if (arr[i] === '#') {
    arr.splice([i - 1], 2);
    break;
    }  
  }
str = arr.join('');
return (str.includes('#')) ? cleanString(str) : str;  
};
```
  
  [Codewars - 6 kyu Sum of Digits / Digital Root](https://www.codewars.com/kata/541c8630095125aba6000c00/javascript)
``` JavaScript
function digital_root(n) {
  let result = 0;
 while (n > 0) {
  result += n % 10;
  n = Math.floor(n / 10);
  if (n === 0 && result > 9) {
     n = result;
     result = 0;
  }
 }
  return result;
}
```

  [Codewars - 7 kyu Anagram Detection](https://www.codewars.com/kata/529eef7a9194e0cbc1000255)
```JavaScript
const isAnagram = (test, original) => 
  test.toLowerCase().split("").sort().join("") === original.toLowerCase().split("").sort().join("") ? true : false;
  ```

  ---

## Education: 

 * MSUF ( 2004 - 2008 ) engineer
 * PSU ( 2016 - 2018 ) civil engineer
 * The Rolling Scopes School ( 2018 - 2019 ) front-end 2019-Q1

 ---

## English:
  - A2
  - studying with a tutor
