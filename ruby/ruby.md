# Ruby

**1. What is Ruby ?**
A general purpose object oriented programming language.
**2. How it differ from other scripting languages such as Perl, PHP, Python ?**
Everything in it is an object.
**3. How the version 1.9 change from the previous versions ?**
Until the version 1.9, Ruby was interpreted. 
The version 1.9 introduce an internal compiler : the ruby script is transformed in a more compact form which is executed by a virtual machine.
**4. What is MRI ?**
*M*atz *R*uby *I*mplementation.
The original ruby implementation in C. 
**5. What is YARV ?**
YARV is the language in which a ruby script is transformed to be executed by the virtual machine. 
**6. What is JRuby ?**
A ruby implementation in Java. 
It runs in a JVM.
**7. How to get documentation about an object ?**
`ri [object name]`
**8. What is monkey patch ?**
A way to change an object by redefining it.
**9. What is metaprogramming ?**
Programming tools to generate program.
**10. What is the value of `i` at the end of this statement ?
`i = 10
+ (3 * 5)`**
`15`
Since the operator `+` is on the following line, the number `10` is ignored.