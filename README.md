# intro_computer
You are connected to the intro-computer.
This is a processor, from which the heart is laid open and made visible during
the run. In executing your program it is possible to follow the flow of data
between memory and registers.
The computer always works in one of the following states :
        1.: console mode
        2.: run or execute mode
In console mode, it is possible to load the computer memory with your program
and data. When the loading process is ready, you can execute your program.
It is possible to make changes in the way your program will be executed.
The main memory of consists of 157 words. Only 21 words are shown during the
execution of your program. You can say where to start with these 21 visible words.
it is also possible to choose how the execution of your program can be delayed.
Thereby is N: no delay, A: delay with a number of stops of 20 msec, and U: the
computer will halt until you have understood what was happening.
Then you can push the space-bar and the next action will take place.
This is possible between the instructions and between the micro-steps.
Memory organisation: 12 bit words.
                                              1XXX = ADD  6XXX = STRI 
                                              2XXX = ISZ  7001 = IAC  7440 = SIZ
            Instruction-set of computer : >>> 3XXX = STR  7040 = CMA  7500 = SIM
	                                            4XXX = ADDI 7200 = CLA  7510 = SIP
	                                            5XXX = JMP  7402 = HLT

Also is the documentation and description of the 'intro computer'. a program originally
writte by Mr. Jan Posthuma and translated into English by Mr. Dick Biesboer, both
workng for the Education department of DEC Utrecht, the Netherlands.

There are 2 versions of the program.
  - cpu52.mac is the original one which has been re-typed from a paper listing and
    uses the VT52 mode of a VT-100/
  - cpu101,mac is my version, which ahs been adapted to make use of native VT-100 mode,
    as well as some changed graphics, flow lines and re-organised code.
    
 When using SIMH, use an xterm to conect to it.
   for a VT52 emulation, use 'xterm -ti vt52 -tn vt52'
   for a vt100 emulation, use 'xterm -ti vt100 -tn vt100'
