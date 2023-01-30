# JavaScript- coding ninja
 ***************************************** Starting with Javascript **********************************************************

## Q-1
![image](https://user-images.githubusercontent.com/96730792/211337930-4bf1cd6d-5ae1-4d3d-8c78-a7da3bc41797.png)

## Q-2
![image](https://user-images.githubusercontent.com/96730792/211338194-dac23333-4093-4768-8f39-059ada287447.png)

## Q-3  ECMAscript officially released -1997

## Q-4 
![image](https://user-images.githubusercontent.com/96730792/211338518-8bb6aded-feb9-4ade-88b6-3fc6f699897b.png)

## Q-5
![image](https://user-images.githubusercontent.com/96730792/211338624-7c4d6c43-738b-45cd-a741-ef497277b906.png)

## Q-6
![image](https://user-images.githubusercontent.com/96730792/211338757-eb98e5e2-dd84-4c0c-814c-37fc2ffa642e.png)

## Q-7 
var a = 10;
console.log(a);
a = " 'Coding Ninjas' ";
console.log(a);
<details><summary><b>Answer</b></summary>
  10,
Coding Ninjas
</details>

## Q-8
var a;
console.log(a);
<details><summary><b>Answer</b></summary>
undefined
</details>

## Q-9
var a = "A";
console.log(65 - a);
<details><summary><b>Answer</b></summary>
  NaN
</details>

## Q-10
typeof("-1")
<details><summary><b>Answer</b></summary>
 string
</details>

## Q-11
var a = null
typeof(a)
<details><summary><b>Answer</b></summary>
object
</details>

## Q-12
var x = 4;
var y = x++;
y += 1;
console.log(y);
<details><summary><b>Answer</b></summary>
5
</details>

## Q-13
console.log(20 + 12 * 2 - 10 / 2)
<details><summary><b>Answer</b></summary>
39
</details>

## Q-14
console.log(1 + '1')
<details><summary><b>Answer</b></summary>
11
</details>
  
 ## Q-15
  var a;
console.log(a + "b");
<details><summary><b>Answer</b></summary>
undefinedb
</details>

## Q-16
console.log(1 - '1')
<details><summary><b>Answer</b></summary>
0
</details>

## Q-17
"1" == 1
<details><summary><b>Answer</b></summary>
true
</details>

## Q-18
null == undefined
<details><summary><b>Answer</b></summary>
true
</details>

## Q-19
if( -1 ) {
    console.log("true")
}
else {
    console.log("false")
}
<details><summary><b>Answer</b></summary>
true
</details>

## Q-20
if( "" ) {
    console.log("true")
}
else {
    console.log("false")
}
<details><summary><b>Answer</b></summary>
false
</details>

## Q-21
for(var i=0; i<5; ++i) { 
      console.log("Hello") ; 
   }
<details><summary><b>Answer</b></summary>

</details>
  
## Q-22
 var i , j ;    
   for(i=0, j = 10; i < 10, j < 100) {
   console.log("Hello"); 
   }
<details><summary><b>Answer</b></summary>

</details>
  
  ## Q-23
var i ;    
   for(i=0; i<5) { 
     console.log("Hello");  
   }
<details><summary><b>Answer</b></summary>

</details>

## Q-24
var i , j ;    
   for(i=0, j=10; i<5; ++i) { 
      console.log("Hello"); 
   }
<details><summary><b>Answer</b></summary>

</details>

## Q-25
var a = 2;
var b = 0;
while(a <= 4){
    a++;
    b += a * 2;
    console.log(b);
}
<details><summary><b>Answer</b></summary>
6 14 24
</details>

## Q-26
![image](https://user-images.githubusercontent.com/96730792/211344971-a572fe9a-1d3c-4b70-8f9e-6ff45c761353.png)

## Q-27
![image](https://user-images.githubusercontent.com/96730792/211345185-c7647eb0-519b-43fe-873c-5f03438d3601.png)

## Q-28
var a = 10/0;
console.log(a);
<details><summary><b>Answer</b></summary>
infinity
</details>

## Q-29
console.log(null == undefined);
console.log(typeof(null) == typeof(undefined));
<details><summary><b>Answer</b></summary>
true false
</details>

## Q-30
console.log(65 + "H")
<details><summary><b>Answer</b></summary>
65H
</details>

## Q-31
null === undefined
<details><summary><b>Answer</b></summary>
false
</details>

## Q-32
typeof( typeof( typeof( 100 ) ) )
<details><summary><b>Answer</b></summary>
string
</details>

## Q-33
var a;
if( typeof(a) ) {
    console.log("true")
}
else {
    console.log("false")
}
<details><summary><b>Answer</b></summary>
true
</details>

## Q-34
![image](https://user-images.githubusercontent.com/96730792/211346634-886ab21f-a3ba-4dc7-959c-896ee09ab30f.png)

## Q-35
![image](https://user-images.githubusercontent.com/96730792/211346774-decff162-313a-4575-8a2e-562da15aad52.png)

 ******************************************************************************************************************************************************************************************************************************************* Functions and Arrays *****************************************************************************
## Q-1
![image](https://user-images.githubusercontent.com/96730792/211347450-060eadf4-aad9-4324-83a0-0009aa9ba51f.png)

## Q-2
![image](https://user-images.githubusercontent.com/96730792/211347529-b98bb470-a66e-4c5c-8645-aa1ea311cfab.png)


## Q-3 More Arguments Passed-
function test(a, b) {
    console.log( a + b );
}
test( 2 , 3 , 4);
<details><summary><b>Answer</b></summary>
5
</details>

## Q-4 Fewer Arguments-
function test(a, b, c) {
    console.log( a + b * c);
}
test(2,3);
<details><summary><b>Answer</b></summary>
Nan
</details>

## Q-5
x = 5;
console.log(x);
var x;
<details><summary><b>Answer</b></summary>
5
</details>

## Q-6
hoisted();

function hoisted() {
    console.log('Hoisted');
}
<details><summary><b>Answer</b></summary>
Hoisted
</details>

## Q-7 Variable Hoisting-
function demo() {
    console.log(x);
    var x = 10;
}
demo();
<details><summary><b>Answer</b></summary>
undefined
</details>

## Q-8 Multiplication-
function multiply(a, b) {
    return a*b;
};
console.log(multiply);
<details><summary><b>Answer</b></summary>
f multiply(a,b){return a*b; }
</details>

## Q-9 Global and Local Variable-
var a = 10;
function test() {
    var a = 20;
}
test(); 
console.log(a);
<details><summary><b>Answer</b></summary>
10
</details>

## Q-10 Global Vs Local-
var a = 10;
function test() {
    var a = 20;
    console.log(a);
}
test();
<details><summary><b>Answer</b></summary>
20
</details>

## Q-11 Function Within Function-
function a() {
    console.log("Inside a");
    function b() {
        console.log("Inside b");
    }
}
a();
<details><summary><b>Answer</b></summary>
Inside a
</details>
  
  ## Q-12 Calling Inner Function-
  function a() {
    console.log("Inside a");
    function b() {
        console.log("Inside b");
    }
}
b();
<details><summary><b>Answer</b></summary>
Uncaught ReferenceError:b is not defined 
</details>

## Q-13 Function Call Inside Function-
var combinedString = "";
function a() {
    combinedString = "Inside a";
    function b() {
        combinedString = combinedString + " Inside b";
    }
    b();
}
a();
console.log(combinedString);
<details><summary><b>Answer</b></summary>
  inside a inside b
</details>

## Q-14 Function Expression-
var RectArea = function(width, height) {
    return width * height;
}
console.log(RectArea(5,4));
<details><summary><b>Answer</b></summary>
 20
</details>

## Q-15 Nested Variable Function-
function a() {
    console.log("Inside a");

    function b() {
        console.log("Inside b");
    }
}

a()b();
<details><summary><b>Answer</b></summary>
  Uncaught SyntaxError: Unexpected identifier 
</details>

## Q-16
![image](https://user-images.githubusercontent.com/96730792/211356332-23718bdf-b056-46a8-aa75-7f9f8e4b0654.png)

## Q-17 Run Subtract-
var add = function (a, b) {
    return a+b;
}
var subtract = function (a, b) {
    return a-b;
}
var op = function (func) {
    var x = 2;
    var y = 3;
    return func(x, y);
}
console.log(op(subtract));
<details><summary><b>Answer</b></summary>
-1
</details>

## Q-18 Pass Function to Function-
  var add = function(a, b) {
    return a+b;
}

var subtract = function(a, b) {
    return a-b;
}

var op = function (func) {
    var x = 2;
    var y = 3;
    return func(x, y);
}

console.log(op(add));
  <details><summary><b>Answer</b></summary>
5
</details>

## Q-19 
![image](https://user-images.githubusercontent.com/96730792/211356899-b08caacb-ca22-4fc8-bb25-db0b77053315.png)

## Q-20
![image](https://user-images.githubusercontent.com/96730792/211357033-f8685628-7c88-439b-8e0b-91c8bbd294b9.png)

## Q-21 Push in Array-
var color= ["Orange", "Blue", "Green"];
color.push("Red");
console.log(color[0]+ " " +color[color.length-1]);
 <details><summary><b>Answer</b></summary>
Orange Red
</details>

## Q-22 Shift Array-
var fruits = ["Red", "Orange", "Blue", "Green"];
console.log(fruits.shift());
 <details><summary><b>Answer</b></summary>
 Red
</details>

## Q-23
![image](https://user-images.githubusercontent.com/96730792/211357530-02f79399-b5a4-4dfe-9fe3-7ec75fd631bd.png)

## Q-24 Array Splice-
var fruits = ['Apple', 'Orange', 'Kiwi', 'Strawberry'];

fruits.splice(4, 1, 'Banana');

console.log(fruits);
<details><summary><b>Answer</b></summary>
['Apple', 'Orange', 'Kiwi', 'Strawberry', 'banana'];
</details>


## Q-25 Array Splice -
var fruits = ['Apple', 'Orange', 'Kiwi', 'Strawberry'];
fruits.splice(1, 0, 'Banana');
console.log(fruits);
<details><summary><b>Answer</b></summary>
['Apple', 'banana', 'orange', 'kiwi', 'Strawberry'];
</details>

## Q-26
![image](https://user-images.githubusercontent.com/96730792/211364397-d75da4ba-4b8d-430b-8b29-e42481141d3e.png)

## Q-27
var sum = 0; 
var arr = [1, 2, 3];
arr.forEach(getSum);
console.log(sum);

function getSum(ele) {
   sum += ele;
}
<details><summary><b>Answer</b></summary>
6
</details>

## Q-28 Global and Local Variable-
var a = 10;
function test() {
    a = 20;
}
test();
console.log(a);
<details><summary><b>Answer</b></summary>
20
</details>

## Q-29
![image](https://user-images.githubusercontent.com/96730792/211364935-2108b44e-5722-48ee-8a08-437e2b4269d9.png)

## Q-30 Function in Function-
function sqSum(a, b) {
    function square(x) {
        return x*x;
    }
    return square(a) + square(b);
}
<details><summary><b>Answer</b></summary>
sum of square of a and b
</details>

## Q-31 Passing Fewer Arguments-
function test(a, b) {
    console.log( a + b );
}
test(2);
<details><summary><b>Answer</b></summary>
NaN
</details>

## Q-32 Hoisting in Javascript-
var a = 1;
function b() {
    a = 10;
    return;
    function a() { }
}
b();
console.log(a);
<details><summary><b>Answer</b></summary>
1
</details>

## Q-33 Iterate Array-
array = [ 60, 70, 20, 10, 40, 90 ];
const test = function(x) {
    return x > 5;
}
if(!array.every(test)) {
    console.log("statement 1"); 
}
else {
    console.log("statement 2"); 
}
<details><summary><b>Answer</b></summary>
statement 2
</details>

## Q-34 Hoisted Function-
hoisted(); 
var hoisted = function() {
    console.log('bar');
};
<details><summary><b>Answer</b></summary>
TypeError:Hoisted is not a function
</details>

## Q-35 For Each Word-
var words = ['one', 'two', 'three', 'four'];
words.forEach(function(word) {
    console.log(word);
    if (word === 'two') {
        words.shift();
    }
});
<details><summary><b>Answer</b></summary>
one two four
</details>

## Q-36 Splice-
var color = ['red', 'orange', 'blue', 'violet'];
var removed = color.splice(2);
console.log(color);
console.log(removed);
<details><summary><b>Answer</b></summary>
var color = ['red', 'orange', 'blue', 'violet'];
</details>
  
## Q-37 
function a(){
    function b() {
        return 3;
    }
    function b() {
        return 8;
   }
} 
console.log(a());
<details><summary><b>Answer</b></summary>
8
</details>
 
 ## Q-38 Rest Parameter-
 function fun(...input){
    var sum = 0;
    for(var i = 0; i < input.length; i++){
        sum += input[i];
    }
    return sum;
}
console.log(fun(1,2,3,4,5)); 
<details><summary><b>Answer</b></summary>
15
</details>
 
## Q-39 Default parameters-
 function f(a,b = 1) {
  console.log(a*b)
}
var x = // some hidden  value
f(5,x)
<details><summary><b>Answer</b></summary>
undefined
</details>



 ****************************************************** Understanding DOM  ***********************************************************

## Q-1
![image](https://user-images.githubusercontent.com/122484692/215387408-04f63e6c-2b56-48bb-9646-3387f8fb50ae.png)

## Q-2 
console.log(window.document==document);
<details><summary><b>Answer</b></summary>
 true
</details>

## Q-3 
console.log(window.location === document.location)
<details><summary><b>Answer</b></summary>
 true
</details>

## Q-3 
function test(){
return this;
}
console.log(test()==window);
<details><summary><b>Answer</b></summary>
 true
</details>

## Q-4
![image](https://user-images.githubusercontent.com/122484692/215388619-ad5679ee-aff1-43c7-8800-f74320aadfca.png)


## Q-5
![image](https://user-images.githubusercontent.com/122484692/215388792-94ac3f10-d306-44c0-abdc-1a4c0a70af51.png)

## Q-6
![image](https://user-images.githubusercontent.com/122484692/215388899-6320fc44-30e7-48b4-ae1e-da5f501504bf.png)

## Q-7
![image](https://user-images.githubusercontent.com/122484692/215389063-a87516c8-da0f-48a9-a7d3-649b05a623b7.png)

## Q-8
![image](https://user-images.githubusercontent.com/122484692/215389154-5f438aad-47ff-46a3-8f2f-c2b5bf656090.png)

## Q-9
![image](https://user-images.githubusercontent.com/122484692/215389218-dad0b872-2265-47d3-b92e-4c4e99af70fd.png)

## Q-10
![image](https://user-images.githubusercontent.com/122484692/215389264-4faa2338-d5df-4778-ac9d-6201cf41a51d.png)

## Q-11
![image](https://user-images.githubusercontent.com/122484692/215389367-0c49a58a-0528-4849-aea6-5c066e599f8b.png)

## Q-12
![image](https://user-images.githubusercontent.com/122484692/215389462-5f865f02-dc66-438f-a782-65692ae55f1b.png)

## Q-13
![image](https://user-images.githubusercontent.com/122484692/215389534-7bd3953d-78d7-4008-8f19-50c862fa5932.png)

## Q-14
![image](https://user-images.githubusercontent.com/122484692/215389580-c0af4657-8226-4405-879f-b71784b9036d.png)

## Q-15
![image](https://user-images.githubusercontent.com/122484692/215389623-a5b8bf28-1434-49cc-acb5-83f70995670c.png)

## Q-16
![image](https://user-images.githubusercontent.com/122484692/215389670-caae8035-79eb-413b-8abf-579a00700425.png)

## Q-17
![image](https://user-images.githubusercontent.com/122484692/215389719-c1dc5746-a17c-4234-85e6-b01bea663d29.png)

## Q-18
![image](https://user-images.githubusercontent.com/122484692/215390187-5a9bef90-e9d4-4ace-9dd7-0132245e67bc.png)

## Q-19
![image](https://user-images.githubusercontent.com/122484692/215390353-80509204-d2a5-4ffe-bdc3-5fbe03da8669.png)

## Q-20
![image](https://user-images.githubusercontent.com/122484692/215390404-2466806a-dcb0-4bfd-b10b-bb1fdf2189bb.png)

## Q-21
![image](https://user-images.githubusercontent.com/122484692/215390455-28019175-2750-4797-ace9-ca55c24c2e79.png)

## Q-22
![image](https://user-images.githubusercontent.com/122484692/215390618-32c20d44-adb3-4a7c-b3c4-3d1ba991ea0c.png)

## Q-23
![image](https://user-images.githubusercontent.com/122484692/215390665-f261741e-7e1c-4ec6-a950-5d8e06a05b2f.png)

## Q-24
![image](https://user-images.githubusercontent.com/122484692/215390730-55aa80f3-8b08-4ba3-9e99-5d7006c63365.png)

## Q-25
![image](https://user-images.githubusercontent.com/122484692/215390799-8815218b-ef4d-4ec5-bbe6-5cb62bf4607b.png)

## Q-26
![image](https://user-images.githubusercontent.com/122484692/215390852-fd8bbb8f-e31a-4eba-9cca-8423304fd108.png)




