<h1 align="center" style="color:gold">Programming With C </h1>

<h1 style="color:greenyellow">Introduction</h1>

<h2 style="color:orange">What is Programming?</h2>

<p style="font-size:16px">
Programming is the process of designing and creating instructions that a computer can follow to perform specific tasks. These instructions are written in programming languages such as C, C++, Python, Java, and JavaScript. Programming enables the development of software applications, websites, games, and systems that power modern technology. It involves logic, problem-solving, and creativity.
</p>

<h2 style="color:yellow">What is C?</h2>
<p style="font-size:16px">C is a general-purpose, procedural programming language. 
It is one of the oldest, fastest and finest programming languages.</p>

<h2 style="color:gold">History of C</h2>

<p style="font-size:16px">
The C programming language was developed in the early 1970s by Dennis Ritchie at Bell Labs. It was created as an evolution of the B language, which itself was influenced by BCPL (Basic Combined Programming Language). C was initially designed to write the Unix operating system, which helped establish its reputation for efficiency and portability.
</p>

<p style="font-size:16px">
Released in 1972, C became widely adopted due to its balance of low-level memory access and high-level programming features. It allowed developers to write system-level code, such as operating systems, compilers, and embedded software, with greater control over hardware resources.
</p>

<p style="font-size:16px">
The language was standardized in 1989 by ANSI (as ANSI C, also known as C89) and later by ISO in 1990. Subsequent updates (like C99, C11, and C18) introduced new features while maintaining backward compatibility, making C one of the most enduring and influential programming languages in computer science history.
</p>


<h2 style="color:orange">Application of C</h2>

<p style="font-size:16px">
C programming is widely used in system-level programming due to its efficiency, speed, and low-level memory access. It is commonly used for developing operating systems (like UNIX and Linux), embedded systems, device drivers, and compilers. C is also used in game development, database systems, and real-time systems. Its portability and structured programming features make it a preferred choice for developing firmware and applications that require high performance and close hardware interaction.
</p>

- <p style="font-size:16px">Operating Systems - Used in the development of systems like UNIX, Linux, and Windows.</p>

- <p style="font-size:16px">Embedded Systems - Common in programming microcontrollers and embedded devices.</p>

- <p style="font-size:16px">Device Drivers - Writing drivers to control hardware devices.</p>

- <p style="font-size:16px">Compilers - Many compilers (e.g., GCC) are written in C.</p>

- <p style="font-size:16px">Game Development - Used for high-performance game engines.</p>

- <p style="font-size:16px">Database Systems - Core parts of systems like MySQL are written in C.</p>

- <p style="font-size:16px">Real-Time Systems - Ideal for time-sensitive applications.</p>

- <p style="font-size:16px">System Programming - For low-level tasks like memory and process management.</p>

- <p style="font-size:16px">Network Programming - Building socket-level network applications.</p>

- <p style="font-size:16px">IoT Applications - Used for lightweight IoT firmware and control systems.</p>



<h2 style="color:greenyellow">First Program in C</h2>

```C
#include <stdio.h>

int main(void) {
    printf("Hello, World!");
    return 0;
}
```
### Output

```
Hello, World!
```

### Explanation

```C
#include <stdio.h>
```
<p style="font-size:16px">This is a <i><b>preprocessor directive</b></i> that includes the standard input-output library, which provides the <i><b>printf</b></i> function and some other functions too.
</p>

```C
int main(void)
```
<p style="font-size:16px">This is the <i><b>main</b></i> function, the entry point of every C program. <i><b>void</b></i> means it doesn't take any parameters.</p>

```C
printf("Hello, World!");
```
<p style="font-size:16px">This line calls the <i><b>printf</b></i> function to display the text <i><b>Hello, World!</b></i> on the console.</p>

```C
return 0;
```
<p style="font-size:16px">This line terminates the <i><b>main</b></i> function and returns the value <i><b>0</b></i> to the operating system. Returning 0 typically means that the program executed successfully.</p>


<h2 style="color:greenyellow">Boilerplate Code</h2>

```C
#include <stdio.h>

int main(void) {

    return 0;
}
```

<h1 align="center" style="color:gold">CHAPTER ONE</h1>
<h2 style="color:yellow">Variables in C</h2>

<p style="font-size:16px">
In C programming, variables are named storage locations in memory that hold data which can be modified during the execution of a program. They are used to store values such as numbers, characters, or more complex data types, so those values can be referenced and manipulated throughout the code.
</p>

### Example

```C
#include <stdio.h>

int main(void) {
    int a; // Variable declaration
    a = 7; // Variable Initialization
    printf("%d\n", a); // Print the value of 'a'
    return 0;
}
```

### Output

```
7
```

<h2 style="color:violet">Variable Declaration in C</h2>


**data_type variable_name;**

```C
int age;
```

<p style="font-size:16px">
In C, declaring a variable means telling the compiler:
</p>

- The name of the variable.

- The type of data it will hold (e.g., integer, character, etc.).
<p style="font-size:16px">
This allows the compiler to reserve memory for it and understand how it should be used.
</p>



<h2 style="color:gold">Rules for Naming Variables in C</h2>


<div style="font-size: 12px;">

| Rule                                      | Example         | Valid? | Explanation                                             |
|-------------------------------------------|------------------|--------|---------------------------------------------------------|
| Starts with a letter or underscore        | `int _value;`    | ✅     | Begins with an underscore, which is allowed             |
| Starts with a digit                       | `int 1value;`    | ❌     | Variable names cannot start with a number               |
| Contains letters, digits, and underscores | `int value_2;`   | ✅     | Letters, digits, and underscores are allowed            |
| Contains special character                | `int name@;`     | ❌     | Special characters like `@`, `$`, `#` are not allowed   |
| Uses a reserved keyword                   | `int return;`    | ❌     | `return` is a C keyword and cannot be used as a name    |
| Case-sensitive names                      | `int Name, name;`| ✅     | `Name` and `name` are two different variables           |
| Uses descriptive name                     | `int studentAge;`| ✅     | Best practice for readable and maintainable code        |

</div>
