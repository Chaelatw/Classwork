# Chapter 2

Two types of Variables: Primitive and Reference
Primitive
    -holds fundamental values (integers, booleans, and floating point numbers
Object references
    -holds references to objects

-Object state: instance variables
-local: variables declared withing a method
-arguments: valures sent to a method by calling the code
-return types: values sent back to the caller of the method

# Chapter 3

Variables must have a type (String, int, etc.) and must have a name.
        ex: String name;
A variable holds something like a cup.

# Chapter 4

Objects have state and behavior represented by instance variables and methods.
Methods use instance variable values.
You can pass values into a method (parameters).

You can return values in a method. However voids will not give anuthing back.
If you decalre a method to return a value, you must return a value of the declared type.
You can send multiple parameters. Separate them with commas.
Public/Private branches


Difference between instance and local variables:
Instance
    -variables are declared inside a class but not withing a method.
    ex: class Horse{
            private double height = 15.2:
            private String breed;
Local
    -variables are declared withing a method
    ex: class AddThing {
            int a;
            int b= 12;

            public int add()  {
                int total = a + b;
                return total;
            }
    }
    -MUST be intialized before use!
