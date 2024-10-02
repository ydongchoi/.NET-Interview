# .NET-Interview

## .NET
### 1. What is .NET?
   
The .NET Framework is a comprehensive software development platform developed by Microsoft. It includes a runtime environment called the Common Language Runtime (CLR) and a rich set of class libraries. It supports multiple programming languages such as C#, VB.NET, and F#, and offers features like memory management, security, and exception handling.

The .NET Framework is primarily used to create applications for Windows, but with the introduction of .NET Core and .NET 5, it can also be used to develop cross-platform applications as well.

### 2. The Structure of .NET Framework.

![image](https://github.com/user-attachments/assets/7e2c218c-1bb6-4235-ad01-a4bda248505f)


### 3. What is Command Language Runtime(CLR)?

The Common Language Runtime (CLR) is the **execution environment** provided by the **.NET Framework**. It manages the **execution** of .NET applications, providing services like **memory management**, **code verification**, **security**, **garbage collection**, and **exception handling**.

One of the key features of the CLR is the **Just-In-Time (JIT) compiler**. When a .NET application is executed, the CLR uses the JIT compiler to **convert the Intermediate Language (IL) code—a low-level**, platform-agnostic programming language—into native machine code specific to the system the application is running on. This process happens at runtime, hence the term "Just-In-Time". This allows .NET applications to be **platform-independent** until they are executed, providing a significant advantage in terms of portability and performance.

### 4. What is ASP .NET?

ASP.NET (Active Server Pages . NET) is a progressive new programming **framework** that empowers the rapid improvement of powerful **web applications and administrations**. It is a part of the Microsoft .NET Platform, it gives the simplest and most versatile approach to **creating, deploying and running web applications** that can focus on any browser or device.ASP.NET is built on the CLR(Common Language Runtime) which allows the programmers to execute its code using any .NET language(C#, VB, etc.). It is specially designed to work with HTTP and for web developers to create dynamic web pages, web applications, websites, and web services as it provides a good integration of HTML, CSS, and JavaScript.

.NET Framework is used to create a variety of applications and services like Console, Web, and Windows, etc. But ASP.NET is only used to create web applications and web services. That’s why we termed ASP.NET as a subset of the .NET Framework.

### 5. What is ASP .NET Features?
There are a lot of reasons which make ASP.NET popular among developers. Some reasons are listed below:

**Extending .NET Framework**: ASP.NET is a subset of the .NET Framework as it extends the .NET Framework with some libraries and tools to develop web apps. The thing that it adds to the .NET Framework is Libraries for common web patterns like MVC, Editor Extensions, the base framework to process the web requests, and web-page templating syntax like Razor, etc.

**Performance**: It is faster than the other web frameworks available in the market.

**Backend Code**: With the help of ASP.NET you can write the backend code for data access and any logic in C#.

**Dynamic Pages**: In ASP.NET, Razor provides the syntax for developing dynamic web pages with the help of C# and HTML. ASP.NET can be integrated with JavaScript and it also includes the frameworks like React and Angular for the SPA(Single Page Application.)

**Supporting different OS**: You can develop and execute ASP.NET apps on Windows, Linux, Docker, and macOS. The Visual Studio provides the tools to build .NET apps with different OS.

### 6. What is ASP.NET MVC framework?
ASP.MVC is a **web application framework** that is lightweight and has high testable features. ASP.NET supports 3 different types of components namely Model, View, and Controller.

**Model Layer**: The Model component corresponds to all or any of **the data-related logic** that the user works with. This will represent either the **info that’s being transferred between the View and Controller components** or the other **business logic-related data**. For instance, a Customer object will retrieve the customer information from the database, manipulate it, and update its data back to the database or use it to render data.

**View Layer**: The View component is employed for all the **UI logic** of the appliance. For instance, the Customer view will include all the UI components like text boxes, dropdowns, etc. that the ultimate user interacts with.

**Controller**: Controllers act as an **interface between Model and consider components** to process all the business logic and incoming requests, manipulate data using the Model component, and interact with the Views to render the ultimate output. For instance, the Customer controller will handle all the interactions and inputs from the Customer View and update the database using the Customer Model. An equivalent controller is going to be wont to view the Customer data.

### 7. Which would be the right framework to be used ASP.NET MVC or ASP.NET Web API?
**ASP.Net MVC** is used to make **web applications** that return the **view and data** but  **Asp.Net Web API** is used to make all  **HTTP services** in a simple and basic way that returns only **information**, not view.

Web API helps to build REST-ful services over the .NET Framework, and it additionally supports content negotiation, self-facilitating which are not in MVC.
Web API additionally deals with returning information specifically design like JSON, XML, or some other dependent on the Accept header in the solicitation, and you don’t stress over that. MVC just returns information in JSON design utilizing Json Result.


### Reference
https://github.com/StefanTheCode/dotnet_interview_questions

https://www.turing.com/interview-questions/dot-net#basic-net-interview-questions-and-answers

https://www.geeksforgeeks.org/asp-net-interview-questions/

## C#
