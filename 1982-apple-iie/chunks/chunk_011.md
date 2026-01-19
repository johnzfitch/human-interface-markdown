<!-- Chunk 11 | Source: 1982 Apple IIe Design Guidelines.pdf | Est. Tokens: 390 -->
Any peripheral card that is to work on the Apple IIe should have firmware that takes into account the protocols of BASIC, Pascal 1.0, and Pascal 1.1. Pascal 1.1 protocols were purposely made flexible enough to meet the requirements of future versions of Pascal, extending the useful life of peripheral card firmware.  
These protocols are not unique to the Apple IIe, but rather are published here to make it easier for peripheral firmware designers to find all requirements in one place.  
#### BASIC Protocol  
The BASIC protocol is very simple; it requires that three entry points be found at fixed locations for a card in slot s:  
| Address | Contains                           |
|---------|------------------------------------|
| \$Cs00  | initialization routine entry point |
| \$Cs05  | input routine entry point          |
| \$Cs07  | output routine entry point         |
|         |                                    |  
#### Pascal 1.0 Protocol  
There are also three entry points for firmware cards under the Pascal 1.0 protocol:  
| Address    | Contains                           |
|------------|------------------------------------|
| \$ C 8 O O | initialization routine entry point |
| \$C84D     | read routine entry point           |
| \$ C 9 A A | write routine entry point          |
|            |                                    |  
New peripheral cards can be "accepted" into the Pascal 1.0 system by using these entry points, as well as having the values \$38 at location \$0.505 and \$18 at \$0.507 (see Device ID discussion below).