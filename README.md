# DSP-lab-9-F
mmregs

.text

START:

STM #0140H,ST0

STM #40H,PMST

STM #0A000H,AR0

ST #1H,*AR0

LD *AR0+,T

ST #2H,*AR0

MPY *AR0+,A

STL A,*AR0

HLT: B HLT

.END
