* Overview

![[photos/System-level-regs-data-structures-ia32e.png]]

## 2.4 memory-management register
* System-level
	* the way to load (from memory to register) & store (from register to memory)
	* W2LS
GDT -> GDTR (W2LS: the LGDT & SGDT  instructions)
IDT -> IDTR (W2LS: the LIDT & SIDT  instructions)

* Task-level
TSS -> TR  (W2LS: the LTR & STR  instructions)
LDT -> LDTR (W2LS: the LLDT & SLDT  instructions)

![[photos/Pasted image 20230430221143.png]]

## 2.5 Control register
Control registers (CR0, CR1, CR2, CR3, and CR4) determine operating mode of the processor and the characteristics of the currently executing task.

* W2LS: In protected mode, the MOV instructions allow the control registers to be read or loaded  
(at privilege level 0 only).

![[photos/Pasted image 20230430223622.png]]

## 2.8 Summary of system-level instructions
![[photos/Pasted image 20230430224850.png]]

![[photos/Pasted image 20230430224944.png]]


