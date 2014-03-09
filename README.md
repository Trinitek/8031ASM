8031ASM
=======

"Assembler for the TK8031 processor"

Written by Blake Burgess || March 2014

// WHAT IT CURRENTLY SUPPORTS //

Supports all of the standard instructions for the TK3081 processor, which is emulated and used in the TK-X03 computer. It supports the DB keyword, which allows raw data to be specified, and it supports comments as marked by a semicolon.


// WHAT IT DOES NOT SUPPORT //

Goto or data labels, macros, the ORG keyword, and number prefixes or postfixes are not supported. Only hexadecimal numbers are allowed.
