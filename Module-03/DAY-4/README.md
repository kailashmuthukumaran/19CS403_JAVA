# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: kailash
RegisterNumber:  212222040068
*/
```

## Sourcecode.java:
```
import java.util.StringTokenizer;
public class Demo{
public static void main(String args[]){
StringTokenizer st = new StringTokenizer("My name is Java Programming"," ");
while (st.hasMoreTokens()) {
System.out.println(st.nextToken());
}
}
}
```






## OUTPUT:
<img width="643" height="226" alt="568463759-2d83eb2d-eb4d-4b48-a2c5-adffd3046504" src="https://github.com/user-attachments/assets/a8b94d18-eeb4-4fe2-baff-2e628a1cd9e7" />



## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.
