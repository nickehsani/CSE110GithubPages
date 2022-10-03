#### Link back to the [repo](https://github.com/nickehsani/CSE110GithubPages)
# **Nick Ehsani**

![This is me!](https://cdn.discordapp.com/attachments/555853001563176990/1023420219835830302/CE05A8A1-E7AB-4413-AD1B-7A90FA8031ED.jpg)

## Directory
- [**Nick Ehsani**](#nick-ehsani)
  - [Directory](#directory)
    - [About me](#about-me)
    - [Programming Languages](#programming-languages)
    - [Coursework](#coursework)
    - [Goals](#goals)
    - [Contact me!](#contact-me)

### About me
Hi! My name is **Nick Ehsani**. I am a 4th year student at [UC San Diego](https://ucsd.edu/) majoring in *Computer Engineering in the Electrical and Computer Engineering Department*. Some of my hobbies include cooking, hiking, SpikeBall, One Piece, and brewing tea (matcha, yerba mate, earl grey, etc). Si vous parlez français, je ne parle pas couramment et j'ai un accent, mais je peux quand même communiquer! I am half Persian so if you know any good Persian restaurants let me know! 

### Programming Languages
Languages I've worked with in order of **most experience** to *least experience*. The `hello world` program is provided for each.
1. **Python**
```print("Hello World")```
2. **C++**
```
#include <iostream>
int main() {
    cout << "Hello World" << endl;
}
```
3. **Java**
```
import java.util.*
public static void main(String args[]) {
    System.out.println("Hello World");
}
```
4. **C**
```
#include <stdio.h>
int main() {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   return 0;
}
```
5. **ARM Assembly**
```
.text            
.global _start
_start:
    mov r0, #1
    ldr r1, =message
    ldr r2, =len
    mov r7, #4
    swi 0

    mov r7, #1
    swi 0

.data
message:
    .asciz "hello world\n"
len = .-message   
```
6. **Verilog**
```
module HELLO_WORLD();
  initial begin
    $display("Hello World");
    $finish;
  end
endmodule
```
I talk more about my preferred programming languages in my [README](README.md).

### Coursework
**FALL QUARTER 2022**
- CSE 110 - Software Engineering
> Introduction to software development and engineering methods, including specification, design, implementation, testing, and process. An emphasis on team development, agile methods, and use of tools such as IDE’s, version control, and test harnesses.
- CSE 101 - Design and Analysis of Algorithms
> Design and analysis of efficient algorithms with emphasis of nonnumerical algorithms such as sorting, searching, pattern matching, and graph and network algorithms. Measuring complexity of algorithms, time and storage. NP-complete problems.
- CSE 140 - Components and Design Techniques for Digital Systems
> Design of Boolean logic and finite state machines; two-level, multilevel combinational logic design, combinational modules and modular networks, Mealy and Moore machines, analysis and synthesis of canonical forms, sequential modules.
- CSE 140L - Digital Systems Laboratory
> Implementation with computer-aided design tools for combinational logic minimization and state machine synthesis. Hardware construction of a small digital system.

### Goals
- [x] Do more leetcode
- [ ] Interview practice
- [ ] Secure an internship
- [ ] Work on side projects
- [ ] Go to the San Diego Zoo
### Contact me!
[Instagram](https://www.instagram.com/niick_e/)\
Email: niehsani@ucsd.edu\
Phone: (863) 430-4811
