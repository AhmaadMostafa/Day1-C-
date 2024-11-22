# .NET Versions

.NET is a development framework created by Microsoft for building a wide range of applications. Over the years, it has evolved with various versions, each introducing new features and improvements.

---

## Key Milestones

### **1. .NET Framework (2002–2019)**  
Primarily for Windows, it supported desktop and web applications.  

- **Latest Stable Version:** 4.8 (2019)  
- **Focus:**  
  - ASP.NET  
  - WPF (Windows Presentation Foundation)  
  - WinForms  
  - Web Services  

---

### **2. .NET Core (2016–2020)**  
A cross-platform, open-source framework designed to run on Windows, macOS, and Linux.  

- **Introduced:** Lightweight modular architecture  
- **Final Version:** .NET Core 3.1 (LTS)  

---

### **3. .NET 5+ (2020–Present)**  
A unified platform that merges .NET Framework and .NET Core into a single cross-platform runtime.  

- **Current Version:** .NET 8 (2023)  
- **Features:**  
  - Performance improvements  
  - New APIs  
  - C# advancements  
  - Cross-platform development  

---

## Namespace in .NET

A namespace is a way to organize classes and other types, helping to avoid naming conflicts and group related functionalities.

### **Key Features**
- **Syntax:**
  ```csharp
  namespace MyNamespace
  {
      // types go here
  }
  ```
- **Purpose:**  
  - Organize code logically  
  - Prevent naming collisions between classes  

### **Common .NET Namespaces**
- **System:** Core types like `String`, `Array`, and `Console`.  
- **System.Collections.Generic:** Collection types such as `List<T>` and `Dictionary<TKey, TValue>`.  
- **System.Linq:** Language Integrated Query (LINQ) features.  
- **System.Threading:** Multithreading and asynchronous operations.  

### **Custom Namespace Example**
```csharp
namespace MyProject
{
    public class Program
    {
        public static int Add(int a, int b) => a + b;
    }
}
```

---

## .NET Core

.NET Core is an important milestone in .NET's evolution, emphasizing performance, modularity, and cross-platform support.

### **Key Characteristics**
- **Cross-Platform:** Runs applications on Windows, macOS, and Linux.  
- **Lightweight & Modular:** Developers include only the required components.  
- **High Performance:** Suitable for scalable and high-performance applications.  
- **Unified Development:** Single codebase for web, cloud, IoT, and desktop apps.  

### **Use Cases**
- Cross-platform tools and libraries  
- High-performance server applications  

---
