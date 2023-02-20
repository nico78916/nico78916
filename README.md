Parmis le PHP,C,C++,HTML,CSS,JAVA,JavaScript,TypeScript,Ocaml,Assembly,LUA,Python,BrainFuck je n'ai pas vraiment trouvé de pire ou de meilleur language

Affichage de hello world dans tout les languages pour les curieux qui ne connaissent pas certain d'entre eux:

PHP :
```php
echo "Hello, World!\n";
```

Python :
```py
print("Hello, World!")
```
C :
```c
printf("Hello, World!\n");
```
C++ :
```c++
std::cout << "Hello World!";
```
HTML :
```html
<h1>Hello, World!</h1>
```
JAVA :
```java
System.out.println("Hello, World!");
```
JavaScript/TypeScript:
```js
console.log("Hello, World!");
```
Ocaml:
```ocaml
print_string "Hello, World!\n"
```
LUA:
```lua
print("Hello, World!")
```
BrainFuck : (ils font ch*er ceux là)
```
>++++++++[<+++++++++>-]<.>++++[<+++++++>-]<+.+++++++..+++.>>++++++[<+++++++>-]<+
+.------------.>++++++[<+++++++++>-]<+.<.+++.------.--------.>>>++++[<++++++++>-
]<+.
```
Assembly :
```assembly
global _start

section .data
  msg: db "Hello, world!", 10
  msglen: equ $ - msg

section .text

_start:
  mov rax, 1        ; 
  mov rdi, 1        ;  
  mov rsi, msg      ;   
  mov rdx, msglen   ;  
  syscall           ; 

  mov rax, 60       ;
  mov rdi, 0        ;  
  syscall           ;
```

Output : Hello, World!
