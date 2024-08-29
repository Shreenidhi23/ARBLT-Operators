# ARBLT-Operators
ARBLT Operators
/Relational Comparison
 public class Relational{
    public static void main(String args[]){
        int x = 79;
        int z = 89;
        System.out.println("x>z:" + (x>z) + ",x<z:" + (x<z)) ;  // [>,<] 
        System.out.println("x>=z:" +(x>=z) + ",x<=z:" + (x<z)); // [>=,<=]
       
        System.out.println("x == z: " + (x == z) + ", x != z: " + (x != z)); //[== , !]
}
}
o/p:PS C:\Users\ASUS\OneDrive\Documents\Desktop\Desktop> javac relational.java
PS C:\Users\ASUS\OneDrive\Documents\Desktop\Desktop> java Relational
x>z:false,x<z:true //op-1
x>=z:false,x<=z:true//0p-2
x == z: false, x != z: true//op-3
// AND Operator
public class OperatorExample{  
public static void main(String args[]){  
int a=10;  
int b=6;  
int c=21;  
System.out.println(a<b&&a++<c);//false && true = false  
System.out.println(a);//10 because second condition is not checked  
System.out.println(a<b&a++<c);//false && true = false  
System.out.println(a);//11 because second condition is checked  
}}  
Output:
o/p:PS C:\Users\ASUS\OneDrive\Documents\Desktop\Desktop> javac and.java
PS C:\Users\ASUS\OneDrive\Documents\Desktop\Desktop> java Operator
false
10
false
11
//Ternary Operator
public class Ternary{  
public static void main(String args[]){  
int a=2;  
int b=5;  
int c=(a<b)?a:b;  
System.out.println(min);  
}}  
O/P : 2
//Assignment Operator
public class Assignment {
    public static void main(String args[]) {
        int a = 89;  
        int b = 44;
        a += 89;    
        b -= 44;    
        System.out.println(a);  // Prints the updated value of 'a'
        System.out.println(b);  // Prints the updated value of 'b'
    }
}
Output:
178
0
// Bitwise Operator
public class OperatorExample{  
public static void main(String args[]){  
int a=5;  
int b=6;  
int c=11;  
System.out.println(a>b||a<c);
System.out.println(a>b|a<c); 
System.out.println(a>b||a++<c);
System.out.println(a); 
System.out.println(a>b|a++<c);
System.out.println(a);
}}  
o/p: true
true
true
6
true
7
