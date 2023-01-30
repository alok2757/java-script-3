# JavaScript- coding ninja
 **************************************************************************************************************************************************************************************************************** Starting with Javascript **********************************************************

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

 ***************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************** Functions and Arrays *********************************************
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

## Q-40
![image](https://user-images.githubusercontent.com/122484692/215396060-8bbe8c82-df02-4671-aa32-62be10ce081a.png)

## Q-41
![image](https://user-images.githubusercontent.com/122484692/215396106-2cd85f7a-73b2-442a-bebe-5097f5449493.png)


******************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************** Objects and Timing Events  **************************************

## Q-1
![image](https://user-images.githubusercontent.com/122484692/215392464-8ba3bf54-a781-4277-855c-7d6604f0a365.png)

## Q-2
![image](https://user-images.githubusercontent.com/122484692/215392546-13336725-291c-4952-9c6e-4d41a37b08a1.png)

## Q-3
![image](https://user-images.githubusercontent.com/122484692/215392587-b5db3184-5b2c-45e8-922f-f7e4adc30c5a.png)

## Q-4
![image](https://user-images.githubusercontent.com/122484692/215392653-3b4a4c8b-4f2e-4204-993d-53f21d7465a1.png)

## Q-5
![image](https://user-images.githubusercontent.com/122484692/215392721-ab0b8a97-3c7d-4ed1-9000-770de02a303f.png)

## Q-6
![image](https://user-images.githubusercontent.com/122484692/215392771-3a3b045b-a1ef-46fb-ad3b-8af3a4813873.png)

## Q-7
![image](https://user-images.githubusercontent.com/122484692/215392825-4e9dbe7d-b74c-4f1a-a1e7-4da4778ce01c.png)

## Q-8
![image](https://user-images.githubusercontent.com/122484692/215392882-7539992c-9286-41f7-bfa9-37c5d246d261.png)

## Q-9
![image](https://user-images.githubusercontent.com/122484692/215392919-9cfa8007-2768-4967-a223-34b8ecc9284f.png)

## Q-10
![image](https://user-images.githubusercontent.com/122484692/215392958-18406510-645c-4982-9883-9827718b9222.png)

## Q-11
![image](https://user-images.githubusercontent.com/122484692/215393002-60ea404f-bb7f-4ccd-af8a-d754b5df95bd.png)

## Q-12
![image](https://user-images.githubusercontent.com/122484692/215393042-48116f4c-4908-4a9b-955c-cc764004109a.png)

## Q-13
![image](https://user-images.githubusercontent.com/122484692/215393115-3579dd4f-c6fc-4da0-9f34-683581996788.png)

## Q-14
![image](https://user-images.githubusercontent.com/122484692/215393189-f848b43c-62d1-4edc-bbf3-2ecdfb977bd2.png)

## Q-15
![image](https://user-images.githubusercontent.com/122484692/215393258-6192474f-c83f-436a-89f6-06406668a055.png)

## Q-16
![image](https://user-images.githubusercontent.com/122484692/215393300-af1f4405-8d2b-4b7f-a8d8-39bc6a0b43ba.png)

## Q-17
![image](https://user-images.githubusercontent.com/122484692/215393350-e64d142b-24a7-48ee-8882-b0c416e70db4.png)

## Q-18
![image](https://user-images.githubusercontent.com/122484692/215393411-9a0fe684-4fe5-4bf3-9300-9ae2edd265d4.png)

## Q-19
![image](https://user-images.githubusercontent.com/122484692/215393472-5928452e-a61e-4670-baf7-0fd530ac04f9.png)

## Q-20
![image](https://user-images.githubusercontent.com/122484692/215393517-bb387bbd-d875-45e6-a8fe-4dc0074b6a88.png)

## Q-21
![image](https://user-images.githubusercontent.com/122484692/215393579-6191839b-7358-4c8e-9293-fcd1522d1512.png)

## Q-22
![image](https://user-images.githubusercontent.com/122484692/215393629-a175140c-09e8-4181-80a2-9e54126e2d1e.png)

## Q-23
![image](https://user-images.githubusercontent.com/122484692/215393692-5fb6a8a0-b74f-4873-8d61-7869c85b635c.png)

## Q-24
![image](https://user-images.githubusercontent.com/122484692/215393945-b575ec31-2ad2-4604-943c-eb5b1ca0031c.png)

## Q-25
![image](https://user-images.githubusercontent.com/122484692/215393998-831e5a2e-e15e-49b4-9be8-e26b4afa6120.png)

## Q-26
![image](https://user-images.githubusercontent.com/122484692/215394096-2b7feba1-54b5-4138-8ae5-9b4ed6e65783.png)

## Q-27
![image](https://user-images.githubusercontent.com/122484692/215394151-af3ef85f-87e3-4a5f-8cf3-7d52f4af6331.png)

## Q-28
![image](https://user-images.githubusercontent.com/122484692/215394207-5c1bb521-406e-44cf-a2bc-48248360acc5.png)

## Q-29
![image](https://user-images.githubusercontent.com/122484692/215394261-233b69bf-e114-4e5f-9d85-6d0ad012ab41.png)



 ***************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************** Understanding DOM  *********************************************

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

***************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************** Closures  ********************************************


## Q-1
![image](https://user-images.githubusercontent.com/122484692/215403285-b27d149c-07bc-4d40-94ea-c26d5b286534.png)

## Q-2
![image](https://user-images.githubusercontent.com/122484692/215403355-694b0be9-32d8-4154-b6cb-592744e8af21.png)

## Q-3
![image](https://user-images.githubusercontent.com/122484692/215403411-363f7efe-2459-4e8a-b795-814d6c09cdd2.png)

## Q-4
![image](https://user-images.githubusercontent.com/122484692/215403480-d728f5de-d6f2-46da-bb4f-81243cdd69d1.png)

## Q-5
var a =10;
var b;
function outer(){
    var b = 30;
    function inner(a){
        var a = 30;
        console.log(a++ ,b++)
        }
        console.log(a, ++b);
        inner(a);
}
outer();
console.log(a++,b++);
<details><summary><b>Answer</b></summary>
      10 31;
      30 31;
      10 NaN
</details>

## Q-6
var a =10;
function outer(){
    var a = 20;
    var b = 30;
    function inner(a){
        var a = 30;
        console.log(a++ ,b++)
        }
    console.log(a, ++b);
    inner(a);
}
outer();
console.log(a++);
<details><summary><b>Answer</b></summary>
      20 31
      30 31
      10
</details>

## Q-7
![image](https://user-images.githubusercontent.com/122484692/215404935-5a2d882e-3fd6-40ec-afce-ddef580830b7.png)

## Q-8
![image](https://user-images.githubusercontent.com/122484692/215404996-89215fc3-287e-4504-9fb6-d7e9915d92f7.png)

## Q-9
![image](https://user-images.githubusercontent.com/122484692/215405153-9fe33208-d41a-40ce-9091-05613f1217ba.png)

## Q-10
![image](https://user-images.githubusercontent.com/122484692/215405225-bb0d38a9-9b57-4f75-aeb8-8eb7be6a999b.png)

## Q-11
![image](https://user-images.githubusercontent.com/122484692/215405283-797ee24a-b4d5-4b87-9257-c5c335db6af4.png)

## Q-12
![image](https://user-images.githubusercontent.com/122484692/215405359-fa6e722a-a42d-4c24-a5b8-53bd19dc9d75.png)

## Q-13
![image](https://user-images.githubusercontent.com/122484692/215405408-89db7b03-c7e9-405c-93f6-e8fc7f67578a.png)

## Q-14
![image](https://user-images.githubusercontent.com/122484692/215405455-04cd6b27-3242-41e9-9ebe-576f689e728f.png)

## Q-15
![image](https://user-images.githubusercontent.com/122484692/215405510-e70a0442-ac31-43b7-84ca-d60ef1344215.png)

## Q-16
![image](https://user-images.githubusercontent.com/122484692/215405551-917756b9-86f3-4a57-8089-955f12cba9e5.png)

## Q-17
![image](https://user-images.githubusercontent.com/122484692/215405743-c24547c7-b1bc-42fa-a607-2c4ba94fd0a6.png)

## Q-18
![image](https://user-images.githubusercontent.com/122484692/215412286-22c59548-ee27-4708-9d99-3b1a0d5258c9.png)

## Q-19
![image](https://user-images.githubusercontent.com/122484692/215412363-86a759fc-1ed4-444d-9ec2-f944270e0a27.png)

## Q-20
![image](https://user-images.githubusercontent.com/122484692/215412435-854f4426-7e45-44dc-9f2a-c2d312ed106d.png)

## Q-21
![image](https://user-images.githubusercontent.com/122484692/215412508-3c23fe46-4e25-4573-8fa3-874a5de7e9ea.png)

## Q-22
![image](https://user-images.githubusercontent.com/122484692/215412586-c15c4d3e-9aae-4d24-86a8-99263e0841ae.png)

## Q-23
![image](https://user-images.githubusercontent.com/122484692/215412664-95980293-bd6d-4992-a864-caa5ee560a51.png)

## Q-24
![image](https://user-images.githubusercontent.com/122484692/215412782-5d6cbf9a-8a2a-4994-a5b8-4897259d2af8.png)

## Q-25
![image](https://user-images.githubusercontent.com/122484692/215412871-87bad3b1-0a02-4ec8-a84a-20bf07251ec6.png)

## Q-26
![image](https://user-images.githubusercontent.com/122484692/215412942-9e77725a-3473-418f-8c07-6b291daa6298.png)

## Q-27
![image](https://user-images.githubusercontent.com/122484692/215413000-b0e9716b-c6c0-4df5-ac79-537587b9f001.png)

## Q-28
![image](https://user-images.githubusercontent.com/122484692/215413096-efce5be6-6227-48c6-bcc4-2fd5ca42462f.png)

## Q-29
![image](https://user-images.githubusercontent.com/122484692/215413196-6d945e22-875f-4c3f-ae96-caf2165fb2d3.png)

## Q-3

