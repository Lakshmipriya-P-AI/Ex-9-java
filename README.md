# EXP-9 -> ADD,RETRIEVE AND REMOVE THE ELEMENT FROM THE ARRAYLIST.
## AIM:
To write the java program to add, retrieve and remove the element from the ArrayList.

## SOFTWARE REQUIRED :
IntelliJ IDEA COMMUNITY EDITION

## ALGORITHM:
Create the class and declare the main method so that the JVM will identify the main program to run.
Declare a variable to accept the arraylist input.
To accept the inputs from user import Scanner and get the input and store them.
To add elements to ARRAYLIST use add() to add elements to the list.
.Print the output after accepting all the inputs.
The program will be executed after the compilation and results are printed.

## PROGRAM:
```
import java.util.ArrayList;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        ArrayList<Integer> arr1=new ArrayList<Integer>();
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the size of array: ");
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            arr1.add(sc.nextInt());
        }
        System.out.println("Array: ");
        System.out.println(arr1);
        System.out.println("Retrieving an element: "+ arr1.get(1));
        System.out.println("Removing an element: "+arr1.remove(2));
        System.out.println("After removing: "+arr1);
    }
}
```
## OUTPUT:
![image](https://github.com/Lakshmipriya-P-AI/Ex-9-java/assets/93427923/83cf4321-d7ab-453b-96a3-32160a598b22)

## RESULT:
Thus the program compile successfully.
