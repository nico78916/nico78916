Parmis le C,C++,HTML,CSS,JAVA,JavaScript,TypeScript,Ocaml,Assembly,LUA,Python,BrainFuck je n'ai pas vraiment trouvé de pire ou de meilleur language

Affichage de hello world dans tout les languages :

Python :
print("Hello, World!")
C :
printf("Hello, World!\n");
C++ :
out << "Hello, World!\n" << std
HTML :
<h1>Hello, World!</h1>
JAVA :
System.out.println("Hello, World!");
JavaScript/TypeScript:
console.log("Hello, World!");
Ocaml:
print_string "Hello, World!\n"
LUA:
print("Hello, World!")
BrainFuck : (ils font ch*er ceux là)
>++++++++[<+++++++++>-]<.>++++[<+++++++>-]<+.+++++++..+++.>>++++++[<+++++++>-]<+
+.------------.>++++++[<+++++++++>-]<+.<.+++.------.--------.>>>++++[<++++++++>-
]<+.
Assembly :

global _start

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

section .rodata
  msg: db "Hello, world!", 10
  msglen: equ $ - msg


Output : Hello, World!
