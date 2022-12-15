# suprise-test
1.
function countVowel(str) {
  var count = 0;
  str=str.toLowerCase();
  for(var i=0;i<str.length;i++){
    if(str.charAt(i)=="a"||str.charAt(i)=="e"||str.charAt(i)=="i"||
       str.charAt(i)=="o"||str.charAt(i)=="u"){
       count++; //Increment vowel count
    }
  }
  return count;
}

console.log(countVowel("Hello")) //2
console.log(countVowel("Umbrella")) //3

2.
function simpleInt(principle, rate, time) {
  var finalAmt=principle + principle*time*rate;
  return finalAmt; 
}

console.log(simpleInt(20000,5,2)) //220000
console.log(simpleInt(150000,25,1)) //3900000
11. Write a function to

3.function howManySeconds(hours) {
	let seconds = (hours * 60) * 60;
	return seconds;
}

4.const baseValue = prompt('Enter the base of a triangle: ');
const heightValue = prompt('Enter the height of a triangle: ');

// calculate the area
const areaValue = (baseValue * heightValue) / 2;

console.log(
  `The area of the triangle is ${areaValue}`
);

5. function sumTriple (x, y) {
  if (x == y) {
    return 3 * (x + y);
    } 
   else
   {
    return (x + y);
   }
 }
console.log(sumTriple(10, 20));
console.log(sumTriple(10, 10));
