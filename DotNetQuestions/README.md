# 📘 .Net Questions

### 🔹 Multiple-Choice Questions

For the correct answers, refer to the [.Net Answers](./DotNet_Answers.md) file.

#### 1. Which component in ASP.NET MVC is responsible for handling user input, interacting with the model, and selecting a view for response?
- A. Model
- B. Controller
- C. View
- D. ActionResult

#### 2. In the MVVM pattern, which interface is most commonly implemented by the ViewModel to notify the View about property changes?
- A. INotifyCollectionChanged
- B. INotifyPropertyChanged
- C. IDataErrorInfo
- D. INotifyErrorInfo

#### 3. What is the primary purpose of LINQ in C#?
- A. To enable asynchronous programming
- B. To perform queries over various data sources using a unified syntax
- C. To compile code at runtime
- D. To create user interfaces

#### 4. Which of the following code snippets correctly retrieves all even numbers from a list of integers using LINQ?
```csharp
List<int> numbers = new List<int> { 1, 2, 3, 4, 5, 6 };
var evens = from n in numbers
            where n % 2 == 0
            select n;
```
- A. The code will not compile
- B. It correctly retrieves the even numbers
- C. It retrieves odd numbers instead
- D. It throws a runtime exception


#### 5. In Entity Framework, which method is used to persist changes made to the context back to the database?
- A. Commit()
- B. SubmitChanges()
- C. SaveChanges()
- D. UpdateDatabase()

#### 6. Which attribute in ASP.NET MVC indicates that a controller action should only respond to HTTP GET requests?
- A. [HttpPost]
- B. [HttpPut]
- C. [HttpGet]
- D. [ActionOnly]

#### 7. Which design pattern is characterized by having a single instance of a class and providing a global access point to it?
- A. Factory Pattern
- B. Observer Pattern
- C. Singleton Pattern
- D. Decorator Pattern

#### 8. Consider the following code snippet. What is the output?
```csharp
public class Test {
    public static void Main() {
        int a = 5;
        int b = a++;
        int c = ++a;
        Console.WriteLine($"{a} {b} {c}");
    }
}
```
- A. 7 5 7
- B. 6 5 6
- C. 7 6 7
- D. 6 6 7

