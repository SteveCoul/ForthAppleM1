# ForthAppleM1
Forth for Apple M1 Macs

Built from a cross compiler that I'm still working on for release later.

A mostly ANS 64 bit ITC forth that works on Apple Silicon M1 Macs.

ALSO platform DEFINITIONS

will show the primitive cooperative task scheduler

VARIABLE fred
: task BEGIN 1 fred +! [schedule] AGAIN ;
' task +task DROP



I throw this out as an early release, because I can't find a Forth for M1 Macs which I have fallen in love with.
