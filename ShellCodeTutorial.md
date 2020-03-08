
Followings are the major memory segments and registers which plays important roll in ShellCodding. 

  The stack segment (For function calls (dynamic)).
  
  The heap segment (For dynamicly allocating memory).
  
  The data segment (Variables).
  
  The bss segment (Variables).
  
  The text segment (Set of instructions (The actual code)).
  
  
  The EAX register
  
  The EBX register
  
  The ECX register
  
  The EDX register
  
  The ESP register
  
  
  Important Assembly Insrtuctions.
  
  MOV (assign, for example MOV EAX, 32 (EAX = 32)).
  XOR (Exclusive OR, for example XOR EAX, EAX)
  PUSH (Push something on the stack, example: PUSH EAX).
  POP (Load what was on the stack in a register/variable, example: POP EBX).
  CALL (Call a function, for example: CALL FuncPrint).
  INT (Interrupt, kernel command, for example INT 0x80 which is used in calling syscalls).
  
  what is "SYSCALL"
   
   The system call is the fundamental interface between an application and the Linux kernel.{instratuctions that kernol can recognize}
   important they dont use stack.
   
   
  
  
  
  
