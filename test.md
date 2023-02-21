# String Array Exercise 

1. Count number of words in a Text after splitting it by any word 
    Hello Wecode Acacdemy 
    space se split, 3 words
    ```
    let str = "Hello Wecode Acaemy";
    let words = str.split(" ")
    document.write(words.length)
    ```
2. Convert odd position word to lowercase and even position word to uppercase
    Hello WeCode Academy 
    hello WECODE academy
    ```
    let str = "hello wecode academy";
    let newstr = str.split(" ")
    console.log(newstr.length);
    for(var i=0 ; i< newstr.length; i++){

    if(i%2==0){
        document.write(newstr[i].toLowerCase()+" ")
    }else if(i%2!=0){
        document.write(newstr[i].toUpperCase()+" ")
    }
   }
    ```
3. Capitalize each word of the string 
    hello wecode academy jhotwara jaipur 
    Hello Wecode Academy Jhotwara Jaipur 
    ```
    let str = "hello wecode academy jhotwara jaipur";
    let words = str.split(" ");

   for(var i =0 ; i<words.length; i++){
    words[i] = words[i][0].toUpperCase() + words[i].substring(1)
   }

   document.write(words.join(" "))
   ```

4. Convert an string into 2 halfs and change the position of the other half 
   My name is wecode academy 
   wecode academy My name is 
   ```
    let str = "My name is wecode academy";
    let strlen= str.split(" ");

    document.write(strlen.slice(3,5) + strlen.slice(0,3))
    ```
    
5. Take a string and now ask for a character from the user. Now find total count of that character in the string 
    My name is wecode academy;
    a 
    3
    -----////-----
6. Reverse a string 
     ```
    let str = "My name is wecode academy";
    let spl = str.split(" ");
    document.write(spl.reverse());
    ```
7. Check string is palindrom or not 
     ```
    let str = "madam";
    let string = str.split('');
    let rev = string.reverse();
    let joins = rev.join('')

    if(str===joins){
    document.write( str," is palindrome")
    }else{
    document.write(str," is not a palindrome")
    }
    ```
8. Remove space from the string and show the output 
  My name is wecode 
  Mynameiswecode
  ```
    let str = "My name is wecode";
    let spl = str.split(" ")
    document.write(spl.join(""))
  ```
9. Check a word count in the string 
    My code is wecode and wecode Jhotwara, Jaipur. 
    code 
    3
    ```
    let str = "My code is wecode and wecode Jhotwara Jaipur";
    let word = str.replace(/code/g, "code");
    let find = word.match(/code/g);
     document.write(find.length);
    ```
10. Replace a word in string 
    My code is wecode and wecode Jhotwara, Jaipur. 
    code rodd
    My rodd is werodd and werodd Jhotwara, Jaipur
    
    ```
     let str = "My code is wecode and wecode Jhotwara Jaipur";
     let rep = str.replace(/code/g, "rodd");
     document.write(rep)
    ```
