# MDISEC Toplulugu - OSCEx04 - Ders Icerik Paylasim reposu
String encoder
Kodu indirdikten sonra asagidaki gibi derleyip calistirin.
nasm -f elf stringencoder.asm -o output.o
ld -m elf_i386 output.o -o binary
