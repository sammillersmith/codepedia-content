---
Title: 'Data Types'
Description: 'Java’s most basic data types are known as primitive data types and are in the system by default.'
Subjects:
  - 'Computer Science'
Tags:
  - 'Data Types'
  - 'Integers'
  - 'Strings'
  - 'Booleans'
CatalogContent:
  - 'learn-java'
  - 'paths/computer-science'
---

In Java, each variable has a property known as its data type which determines what kind of data can be stored in that variable. Data types are divided into two categories, [primitive data types](#primitive-data-types) and [reference data types](#reference-data-types). Java is a [statically-typed](#static-typing) language.

## Primitive Data Types

Java’s most basic data types are known as primitive data types and are in the system by default.

The available types are as follows:

- `int`
- `char`
- `boolean`
- `byte`
- `long`
- `short`
- `double`
- `float`

`null` is another, but it can only ever store the value null.

```java
int age = 28;
char grade = 'A';
boolean late = true;
byte b = 20;
long num1 = 1234567;
short no = 10;
float k = (float)12.5;
double pi = 3.14;
```

## Reference Data Types

Reference data types, also known as object data types, are data types which are defined by the user and are references to a specific object.

Reference data types include:

- Annotations - allow metadata to be associated with elements of a program
- [Arrays](https://www.codecademy.com/resources/docs/java/arrays) - store elements of the same type
- [Classes](https://www.codecademy.com/resources/docs/java/classes) - provide a template for object creation
- [Enumeration](https://www.codecademy.com/resources/docs/java/enums) - stores a fixed set of constants
- [Interfaces](https://www.codecademy.com/resources/docs/java/interfaces) - store a template for a class

## Static Typing

In Java, the type of variable is checked at compile time. This is known as static typing. It has the advantage of catching the errors at compile time rather than at execution time.

Variables must be declared with the appropriate data type or the program will not compile.

```java
int i = 10;           // Type is int
char ch = 'a';        // Type is char

j = 20;               // Won't compile, no type is given
char name = "Sonny";  // Won't compile, wrong data type
```
