# ENC28J60-libs
*The ENC28J60 arduino library refactored*

Here are the main changes i've made on this library were:
 - Changing "char \*" parameters to "const char\*" parameters on ETHER28J60.h;
 - Fixed "EtherShield.h not found" error on case-sensitive systems by properly renaming the include line on etherShield.h;
 - Changed all prog_char variables to simple char ones (fixes some compiling errors);
 
Now the print() method of the ENC29J60 object can be called passing a simple string as a parameter in your arduino code, istead a char*[] variable.
