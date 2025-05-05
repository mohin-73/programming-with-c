<h1 align="center" style="color:gold">Programming With C </h1>

<h1 style="color:greenyellow">Introduction</h1>

<h2 style="color:orange">What is Programming?</h2>

<p style="font-size:17px">
Programming is the process of designing and creating instructions that a computer can follow to perform specific tasks. These instructions are written in programming languages such as C, C++, Python, Java, and JavaScript. Programming enables the development of software applications, websites, games, and systems that power modern technology. It involves logic, problem-solving, and creativity.
</p>

<h2 style="color:gold">History of &nbsp;C</h2>

<p style="font-size:17px">
The C programming language was developed in the early 1970s by Dennis Ritchie at Bell Labs. It was created as an evolution of the B language, which itself was influenced by BCPL (Basic Combined Programming Language). C was initially designed to write the Unix operating system, which helped establish its reputation for efficiency and portability.
</p>

<p style="font-size:17px">
Released in 1972, C became widely adopted due to its balance of low-level memory access and high-level programming features. It allowed developers to write system-level code, such as operating systems, compilers, and embedded software, with greater control over hardware resources.
</p>

<p style="font-size:17px">
The language was standardized in 1989 by ANSI (as ANSI C, also known as C89) and later by ISO in 1990. Subsequent updates (like C99, C11, and C18) introduced new features while maintaining backward compatibility, making C one of the most enduring and influential programming languages in computer science history.
</p>

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
- This is a preprocessor directive that includes the standard input-output library, which provides the printf function.

```C
int main(void)
```
- This is the main function, the entry point of every C program. void means it doesn't take any parameters.

```C
printf("Hello, World!");
```
- This line calls the printf function to display the text Hello, World! on the console.

```C
return 0;
```
- This returns 0 to the operating system, indicating that the program executed successfully.

<h2 style="color:orange">Application of C </h2>

<p style="font-size:17px">
C programming is widely used in system-level programming due to its efficiency, speed, and low-level memory access. It is commonly used for developing operating systems (like UNIX and Linux), embedded systems, device drivers, and compilers. C is also used in game development, database systems, and real-time systems. Its portability and structured programming features make it a preferred choice for developing firmware and applications that require high performance and close hardware interaction.
</p>

- <p style="font-size:16px">Operating Systems – Used in the development of systems like UNIX, Linux, and Windows.</p>

- <p style="font-size:16px">Embedded Systems – Common in programming microcontrollers and embedded devices.</p>

- <p style="font-size:16px">Device Drivers – Writing drivers to control hardware devices.</p>

- <p style="font-size:16px">Compilers – Many compilers (e.g., GCC) are written in C.</p>

- <p style="font-size:16px">Game Development – Used for high-performance game engines.</p>

- <p style="font-size:16px">Database Systems – Core parts of systems like MySQL are written in C.</p>

- <p style="font-size:16px">Real-Time Systems – Ideal for time-sensitive applications.</p>

- <p style="font-size:16px">System Programming – For low-level tasks like memory and process management.</p>

- <p style="font-size:16px">Network Programming – Building socket-level network applications.</p>

- <p style="font-size:16px">IoT Applications – Used for lightweight IoT firmware and control systems.</p>
