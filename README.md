# Try with Resource



**Objective**

By the end of this project, you will be able to handle exceptions using the `try-with-resource` statement.

**Concepts**

| Concept   |      Resources      |
|----------|:-------------:|
|Explanation of try with resource| [try-with-resource document](https://docs.oracle.com/javase/tutorial/essential/exceptions/tryResourceClose.html#:~:text=The%20try%20%2Dwith%2Dresources%20statement%20is%20a%20try%20statement%20that,the%20end%20of%20the%20statement.)|
|Java try with resource | [try with resource overview](https://textbooks.cs.ksu.edu/cc210/10-exceptions/06-java/06-resources/index.print.html#:~:text=That%20Scanner%20object%20is%20the,the%20Try%20with%20Resources%20statement.)|
|Try with resources using the Scanner|[try with resource using scanner object(Tutorial)](https://www.youtube.com/watch?v=paLsAtlA5wo)|


**Problem**

Use the `try-with-resource` concept to read input from the user.

**Implementation**

* Create inside the try block, a `Scanner` object to read input `name` from `System.in`.
* Display a greeting message with the entered name using System.out.println().


  > The Scanner resource is automatically closed at the end of the try block.
  

```Java

public class Main {
    public static void main(String[] args) {
          /* try (Scanner object)) { 
                your code here  } */
    }
}

```
