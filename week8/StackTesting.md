## Stack Testing

Create JUnit tests for the Stack interface.

1. Create an IDE project and add `Stack.java` to the `ku/util` package to your project "src" tree.
2. In the source tree, create a dummy stack with do-nothing methods. Eclipse can quickly do this for you.  
3. Create a separate source tree named "test" for test code. 
    * Using a separate source tree for test code is a best practice.
4. In `test/ku/util` create a `StackTest` Unit Test class that tests the Stack methods using JUnit.  
    * Eclipse: right-click and choose New -> Unit Test.
    * Use your dummy stack as the "Class Under Test" so Eclipse New Unit Test wizard can help generate method code.
    * Use your dummy stack as target of unit tests.
    * Most of your tests will fail. This is usual.
5. Download and add `StackFactory.jar` to your project.
    * To add a JAR file, use Project -> Properties -> Build Path and select the "Library" tab.
    * Click "Add JAR" to add JAR fil.
6. In StackTest, create a real stack using:
```
    Stack stack = StackFactory.makeStack( capacity );
```
If you need a type-specific stack, use a cast:
```
    Stack<String> stack = (Stack<String>)StackFactory.makeStack( capacity );
```
7. `StackFactory` may contain produce than one kind of Stack. 
Don't be too confident if your tests pass easily.
