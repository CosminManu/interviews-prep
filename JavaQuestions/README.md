# 📘 Java Questions

### 🔹 Multiple-Choice Questions

For the correct answers, refer to the [Java Answers](./Java_Answers.md) file.

#### 1. What will happen if you try to compile and run the following code?
```java
String s = null;
System.out.println(s.length());
```
- A. It will print "0"
- B. It will print "null"
- C. It will throw a NullPointerException
- D. It will compile successfully but throw a runtime error  


#### 2. What will be the output of the following code?
```java
String s1 = new String("abc");
String s2 = "abc";
System.out.println(s1 == s2);
```
- A. true
- B. false
- C. Compilation error
- D. Runtime error  


#### 3. What will happen if a class does not explicitly define any constructor?
- A. The class will not compile
- B. The compiler automatically provides a default constructor
- C. The class will throw a runtime exception
- D. The class will have a constructor with no parameters, but it won't be accessible  


#### 4. Which of the following annotations is used to define a Spring bean?
- A. `@Component`
- B. `@Bean`
- C. `@Service`
- D. All of the above  


#### 5. Which of the following is true about the try-with-resources statement in Java?
- A. It can only be used with `InputStream`.
- B. It automatically closes resources that implement the `AutoCloseable` interface.
- C. It requires a `finally` block to close resources.
- D. It can only handle checked exceptions.  


#### 6. What is the default behavior of the `@Transactional` annotation regarding rollback on checked exceptions?
- A. It rolls back the transaction for both checked and unchecked exceptions.
- B. It rolls back the transaction only for unchecked exceptions.
- C. It does not roll back the transaction for any exceptions.
- D. It rolls back the transaction only for specific checked exceptions.  

#### 7. Which of the following statements can complete the statement to successfully compile the code:
`Set<? extends RuntimeException> mySet = ____________;`
- A. `HashSet<? extends RuntimeException>()`
- B. `HashSet<Exception>()`
- C. `TreeSet<Exception>()`
- D. `TreeSet<NullPointerException>()`


#### 8. Which of the following statements is true about the Java `HashMap`?
- A. It is synchronized and thread-safe.
- B. It allows null keys and null values.
- C. It maintains the order of elements based on their insertion.
- D. It does not allow duplicate keys but allows duplicate values.  


#### 9. Which of the following is a characteristic of an immutable class?
- A. All fields are public.
- B. The class can be subclassed.
- C. All fields are private and final.
- D. It has setter methods for its fields.


#### 10. What will happen if you try to compile and run the following code?
```java
String s = null;
System.out.println(s.length());
```
- A. It will print "0"
- B. It will print "null"
- C. It will throw a NullPointerException
- D. It will compile successfully but throw a runtime error


#### 11. What is the output of the following code snippet?
```java
System.out.println(1 + 2 + "3" + 4 + 5);
```
- A. "3345"
- B. "12345"
- C. "33 45"
- D. "6 345"  


#### 12. Which keyword is used to prevent a class from being subclassed in Java?
- A. `final`
- B. `static`
- C. `abstract`
- D. `private`  


#### 13. Which of the following is not a valid access modifier in Java?
- A. public
- B. protected
- C. package
- D. private


#### 14. Which method must be implemented by all threads in Java if they extend the `Thread` class?
- A. `run()`
- B. `start()`
- C. `main()`
- D. `execute()`  


#### 15. Which of the following is true about the Java `finally` block?
- A. It executes only if an exception is thrown.
- B. It always executes, regardless of whether an exception is thrown.
- C. It executes only if no exception is thrown.
- D. It is optional and rarely used.


#### 16. Which of the following is the correct way to declare an array of integers in Java?
- A. `int[] arr;`
- B. `int arr[];`
- C. Both A and B
- D. None of the above  


#### 17. What is the purpose of the `super` keyword in Java?
- A. To refer to the immediate parent class instance
- B. To call a static method
- C. To define a class as a subclass
- D. To allocate memory  


#### 18. Which of the following correctly declares an abstract method in an abstract class?
- A. `abstract void method();`
- B. `void method() = 0;`
- C. `virtual void method();`
- D. `public abstract method();`  


#### 19. Which of the following statements correctly describes exception handling in Java?
- A. Exceptions can only be handled using try-catch blocks
- B. Exceptions can be propagated using the throws keyword
- C. Exceptions cannot be caught once thrown
- D. Exceptions are always runtime exceptions

#### 20. Which of these is not a feature of the Java programming language?
- A. Object-oriented
- B. Platform-independent
- C. Supports multiple inheritance via classes
- D. Automatic garbage collection  


#### 21. Which method in the Object class is used to obtain a string representation of an object?
- A. `toString()`
- B. `getString()`
- C. `valueOf()`
- D. `format()`


#### 22. Which keyword is used to inherit a class in Java?
- A. implements
- B. extends
- C. inherits
- D. super



#### 23. What is the correct way to start the main method in Java?
- A. `public static void main(String[] args)`
- B. `public static void Main(String args[])`
- C. `public void main(String[] args)`
- D. `static void main(String[] args)`  


#### 24. What does JVM stand for in Java?
- A. Java Variable Machine
- B. Java Virtual Machine
- C. Java Visual Machine
- D. Java Verified Machine

#### 25. Which of the following statements about Java is true?
- A. Java supports operator overloading.
- B. Java supports multiple inheritance of classes.
- C. Java supports multithreading.
- D. Java supports pointers.


#### 26. Which exception is thrown when an array is accessed with an illegal index?
- A. `ArrayIndexOutOfBoundsException`
- B. `NullPointerException`
- C. `IllegalArgumentException`
- D. `ArrayStoreException`  


#### 27. What is autoboxing in Java?
- A. Automatic conversion of primitive types to their corresponding object wrapper classes
- B. Automatic conversion of objects to primitive types
- C. Automatic garbage collection
- D. Automatic memory allocation  


#### 28. Which of the following correctly demonstrates the use of a generic method in Java?
- A. `public <T> void print(T t) { System.out.println(t); }`
- B. `public void print(T t) { System.out.println(t); }`
- C. `public T print(T t) { System.out.println(t); }`
- D. `public void <T> print(T t) { System.out.println(t); }`  


#### 29. Which statement about Java interfaces is correct?
- A. An interface can contain instance fields.
- B. An interface can contain static methods with implementations.
- C. An interface can have constructors.
- D. An interface cannot extend another interface.  

#### 30. What is the default value of a boolean instance variable in Java?
- A. true
- B. false
- C. null
- D. 0


#### 31. Which of the following is the correct way to declare a constant in Java?
- A. `final int CONSTANT = 10;`
- B. `const int CONSTANT = 10;`
- C. `int CONSTANT = 10;`
- D. `static final int CONSTANT = 10;`


