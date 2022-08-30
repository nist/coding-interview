# Shell

**1. What differ between bash and cshell ?**
The syntax of the scripting language differ.
The cshell use a syntax like the C programming language.
**2. How to know the full current path ?**
`pwd`
For *p*rint *w*orking *d*irectory
**3. Where is the history of commands ?**
On bash, `~/.bash_history`
**4. What does the command `su` ?**
*S*ubstitute *u*ser
Allow to log with the specified user.
If no user is specified, log with root.
The password will be asked.
**5. What is ssh ?**
*s*ecure *sh*ell
A way to log to a server using encrypted connection.
**6. How to secure ssh ?**
Generate an encrypted token and put the public key of the client on the server. 
**7. How to know how long a program run ?**
Before the program : `time`
**8. How to list current running programs ?**
`ps`
**9. What is a zombie process ?**
A dead process which was destroyed correctly.
**10. Which command allow to copy a file from one machine to another securely ?**
`scp`