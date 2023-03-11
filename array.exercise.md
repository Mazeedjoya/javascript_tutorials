

  Question 1 Create an array with three elements and print out the second element.
  ```
 let arr = ["one" , "two" , "three"];
 document.write(arr[1])
 ```
  Question 2 Create an array with five elements and print out the length of the array.
 ```
 let arr2 = ["one" , "two" , "three", "four","five"];
 document.write(arr2.length)
 ```
 Question 3 Create an array with four elements and print out each element using a for loop.
 ```
let arr3 = ["one" , "two" , "three", "four"];
for(var i=0; i<arr3.length; i++){
     document.write(arr3[i],"<br>")
}
```
 Question 4 Create an array with six elements and print out each element using a forEach loop.
```
let arr4 = ["one" , "two" , "three", "four","five" , "six"];
arr4.forEach(element=>{
     document.write(element,"<br>")
})
```
 Question 5  Create an array with three elements and add a fourth element to the end of the array.
```
let arr5 = ["one" , "two" , "three"];
arr5.push("four");
 document.write(arr5 );
 ```
 Question 6 Create an array with four elements and remove the second element.
```
let arr6 = ["one" , "two" , "three", "four"];
 document.write(arr6.slice(1,2));
document.write("<br>")
 document.write(arr6.splice(1,1));
 ```
 Question 7 Create an array with five elements and remove the last element.
```
let arr7 = ["one" , "two" , "three", "four","five"];
document.write(arr7.pop())
```
 Question 8 Create an array with three elements and check if the array includes a specific value.
 ```
 let arr8 = ["one" , "two" , "three"];
 document.write(arr8.includes("one",0))
 ```
 Question 9 Create an array with four elements and sort the array in ascending order.
```
let arr9 = ["one" , "two" , "three", "four"];
let arr9 = [1,5,6,4,33,21,19];
 document.write(arr9.sort(test))
document.write("<br>")
function test(a, b){
    return a-b;
}
```
Question 10 Create an array with five elements and sort the array in descending order.
 ``` 
 let arr10 = [4,3,2,98,11,5]
  document.write(arr10.sort(descending))
 function descending (a,b){
    return b-a
 }
```
 Question 11 Create two arrays, concatenate them and print out the resulting array.
 ```
let array1 = ["array 1 ",1,2,3,4];
let array2 =["array 2 ",5,6,7,8];
let arr11=[]
 document.write(arr11.concat(array1,array2))
 ```
 Question 12 Create an array with three elements and convert it to a string.
```
let arr12 = [1,2,3];
let tost = arr12.toString();
document.write(typeof(tost)) // checking type 
```
 Question 13 Create an array with four elements and reverse the order of the elements.
 ```
 let arr13 = [ "one" , "two" ,"three" , "four"];
 document.write(arr13.reverse())
```
Question 14 Create an array with five elements and find the index of a specific value.
 ```
 let arr14 = [ "one" ,"two" ,"three", "four","five"];
 document.write(arr14.indexOf("two"))
 ```
 Question 15 Create an array with six elements and slice the array to create a new array with the first three elements.
               ```
               let arr15 = ["one" ,"two" ,"three", "four","five", "six"];
                let newarr = arr15.slice(0,3);
                document.write(newarr)
                ```
 Question 16 Create an array with six elements and use the map method to double each element.
``` 
let arr16 = [1,2,3,4,5,6];
let newarr = arr16.map(doubles);
function doubles(no){
    return no*2;
}
document.write(newarr)
```
 Question 17 Create an array with four elements and use the while loop to calculate the sum of all elements.
```
let arr17 = [1,2,3,4];
let sum =0;

for(var i=0; i<arr17.length; i++){
    sum+=arr17[i]
}
document.write(sum)
```

 Question 18 Create an array with five elements and use the filter method to return only the even numbers.
```
let arr18 = [ 2,3,41,5,6];

let even = arr18.filter(checkeven)
function checkeven(arr18){
    return arr18%2==0;
}
 document.write(even)
```

 Question 19 Create an array with three elements and use the join method to concatenate the elements with a dash (-) separator.
```
let arr19 = ["Wecode" ,"Academy", "Jaipur"];
 document.write(arr19.join("-"))
 ```
 Question 20 Create two arrays with three elements each and use the concat method to combine them into a new array.
```
let arrr1 =[ 1,2,3];
let arrr2 = [4,5,6];
let arr20 = [];
document.write(arr20.concat(arrr1,arrr2))
```
