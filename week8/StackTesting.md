## Stack Testing

Create JUnit tests for the Stack interface.

1. Create an IDE project and add `Stack.java` to the `ku/util` package to your project "src" tree.
2. In the source tree, create a dummy stack with do-nothing methods. Eclipse can quickly do this for you.  
    * Real stacks have a capacity set via the constructor. So you may add a `DummyStack(int capacity)` constructor to match this.
3. Create a separate source tree named "test" for test code. 
    * Using a separate source tree for test code is a best practice.
4. In `test/ku/util` create a StackTest class that tests the Stack methods using JUnit.  For now use your dummy stack as target object.
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
