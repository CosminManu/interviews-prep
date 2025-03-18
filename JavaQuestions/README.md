# 📘 Java Questions

### 🔹 Multiple-Choice Questions

For the correct answers, refer to the [Java Answers](./JavaQuestions/Java_Answers.md) file.

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


#### 7. Which of the following statements is true about the Java `HashMap`?
- A. It is synchronized and thread-safe.
- B. It allows null keys and null values.
- C. It maintains the order of elements based on their insertion.
- D. It does not allow duplicate keys but allows duplicate values.  


#### 8. What is the output of the following code snippet?
```java
System.out.println(1 + 2 + "3" + 4 + 5);
```
- A. "3345"
- B. "12345"
- C. "33 45"
- D. "6 345"  


#### 9. Which keyword is used to prevent a class from being subclassed in Java?
- A. `final`
- B. `static`
- C. `abstract`
- D. `private`  


#### 10. Which method must be implemented by all threads in Java if they extend the `Thread` class?
- A. `run()`
- B. `start()`
- C. `main()`
- D. `execute()`  


#### 11. Which of the following is the correct way to declare an array of integers in Java?
- A. `int[] arr;`
- B. `int arr[];`
- C. Both A and B
- D. None of the above  


#### 12. What is the purpose of the `super` keyword in Java?
- A. To refer to the immediate parent class instance
- B. To call a static method
- C. To define a class as a subclass
- D. To allocate memory  


#### 13. Which of the following correctly declares an abstract method in an abstract class?
- A. `abstract void method();`
- B. `void method() = 0;`
- C. `virtual void method();`
- D. `public abstract method();`  


#### 14. Which of these is not a feature of the Java programming language?
- A. Object-oriented
- B. Platform-independent
- C. Supports multiple inheritance via classes
- D. Automatic garbage collection  


#### 15. What is the correct way to start the main method in Java?
- A. `public static void main(String[] args)`
- B. `public static void Main(String args[])`
- C. `public void main(String[] args)`
- D. `static void main(String[] args)`  


#### 16. Which exception is thrown when an array is accessed with an illegal index?
- A. `ArrayIndexOutOfBoundsException`
- B. `NullPointerException`
- C. `IllegalArgumentException`
- D. `ArrayStoreException`  


#### 17. What is autoboxing in Java?
- A. Automatic conversion of primitive types to their corresponding object wrapper classes
- B. Automatic conversion of objects to primitive types
- C. Automatic garbage collection
- D. Automatic memory allocation  


#### 18. Which of the following correctly demonstrates the use of a generic method in Java?
- A. `public <T> void print(T t) { System.out.println(t); }`
- B. `public void print(T t) { System.out.println(t); }`
- C. `public T print(T t) { System.out.println(t); }`
- D. `public void <T> print(T t) { System.out.println(t); }`  


#### 19. What does JVM stand for in Java?
- A. Java Variable Machine
- B. Java Virtual Machine
- C. Java Visual Machine
- D. Java Verified Machine  


#### 20. Which statement about Java interfaces is correct?
- A. An interface can contain instance fields.
- B. An interface can contain static methods with implementations.
- C. An interface can have constructors.
- D. An interface cannot extend another interface.  

