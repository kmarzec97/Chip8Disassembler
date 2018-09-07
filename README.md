# Chip8Disassembler
Disassembler for chip8 in python.
Manual for Chip8Disassembler!

NOP - does nothing

Display - clears the screen

RET - returns from subroutine

JMP #ADRESS - jumps to adress

CALL #ADRESS - calls subroutine at adress

JE Vx, #VAL - skips next instruction if Vx equals val

JNE Vx. #VAL - skips next instruction if Vx not equals val

JE Vx, Vy - skips next instruction if Vx equals Vy

MOV Vx, #VAL - sets Vx to val

ADD Vx, #VAL - adds val to Vx

MOV VX, Vy - sets Vx to Vy 

ORL Vx, Vy - OR operation on Vx and Vy, result saves to Vx

ANL Vx, Vy - AND operation on Vx and Vy, result saves to Vx

XLR Vx, Vy - XOR operation on Vx and Vy, result saves to Vx

ADD Vx, Vy - adds Vy to Vx

SUB Vx, Vy - substraction Vx = Vx - Vy


RR Vx - rotates Vx to right with carry bit

SUBO Vx, Vy - substraction Vx = Vy - Vx

RL Vx - rotates Vx to left with carry bit

JNE Vx, Vy - skips next instruction if Vx not equals Vy

MOV I, #VAL - sets I to val

JMPV0 #VAL - jumps to V0 + val

RND Vx, #VAL - generates random number  in range 0 to val and stores in Vx

DRAW Vx, Vy, #VAL - draws sprite at coordinates(Vx, Vy) that has a width of 8 pixels and a height of val pixels

JKE Vx - skips next instruction if specified key (Vx) is pressed

JKNE Vx - skips next instruction if specified key (Vx) is not pressed

MOV Vx, DELAY - sets Vx value to DELAY

MOV Vx, KEY - sets Vx value to pressed key

DELAY Vx - sets delay value to Vx

SOUND Vx - sets sound value to Vx

ADD I, Vx - adds Vx to I

SETSPRITE I, Vx - sets I to location of the sprite for the character in Vx

BCD Vx - binary coded decimal representation of Vx stored at I+0 I+1 I+2

REGD Vx - stores V0 to Vx in memory starting at I

REGL Vx - fills V0 to Vx in memory starting at I
