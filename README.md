# Head First Java Notes

## Table of Contents
- Chapter 2: A Trip to Objectville
- Chapter 3: Know Your Variables
- Chapter 4: How Objects Behave

---

## Chapter 2: A Trip to Objectville

### Key Concepts:
- **Classes and Objects**: A class is a blueprint for creating objects, and objects are instances of a class.
- **Methods**: Define behaviors for objects.
  - Example:
    ```java
    class Dog {
        void bark() {
            System.out.println("Woof!");
        }
    }
    ```
- **Encapsulation**: Keep instance variables hidden from outside and provide public getter/setter methods.
- **Instance Variables and Methods**: Defined in a class, they represent the data and behaviors of an object.
  
### Important Points:
- **Object State and Behavior**: An object’s state is stored in instance variables, and its behavior is defined through methods.
- **Garbage Collection**: Java automatically cleans up objects that are no longer referenced.

---

## Chapter 3: Know Your Variables

### Key Concepts:
- **Primitives vs. Object References**: 
  - Primitive types (e.g., `int`, `char`, `float`) hold values.
  - Object reference variables store addresses to objects in memory.
  
- **Variable Declaration and Initialization**:
  - Declaration:
    ```java
    int x;
    ```
  - Initialization:
    ```java
    x = 42;
    ```

- **Scope of Variables**: Determines where a variable can be accessed. Includes local, instance, and class-level scope.
- **Array Basics**:
  - Declaring arrays:
    ```java
    int[] numbers = new int[10];
    ```

### Important Points:
- **Casting**: Convert from one type to another (e.g., `int` to `double`).
- **Default Values**: Uninitialized primitive types and object references in classes get default values.

---

## Chapter 4: How Objects Behave

### Key Concepts:
- **Object Interaction**: Objects can interact with each other by calling each other’s methods.
- **Instance vs. Class Variables and Methods**:
  - Instance variables belong to an instance (object) of a class.
  - Class variables (declared with `static`) belong to the class itself.

- **Return Values from Methods**:
  - Example:
    ```java
    public int addNumbers(int a, int b) {
        return a + b;
    }
    ```

- **Constructors**: Special methods that initialize new objects.
  - Example:
    ```java
    public class Dog {
        String name;
        
        public Dog(String name) {
            this.name = name;
        }
    }
    ```

### Additional Information:
- **Overloading Methods**: Multiple methods can have the same name but different parameter lists.
- **Passing Parameters**: Java is strictly pass-by-value. For object references, the value of the reference is passed, not the actual object.
- **Immutable Objects**: Some objects, like `String`, cannot be changed after they are created.

---

