﻿# EjercicioSistemas2.1
1.Programa que multiplique los numeros de las posciones 2A y 2B de memoria.
(se hace con sumas ya que no sabe multiplicar)

lda #$2
ldx #$3
sta $2a
stx $2b
add $2a
dcx
jc $08

----

lda #$3
ldx #$2
sta $2a
stx $2b
add $2a
dcx
jnz $08
sub $2a
sta $2c

//Si a es 0 el resultado es 0, si es x la que es 0, entra en bucle.

2.Elevar la base que esta en una posicion de memoria a un exponente que esta en otra posicion de memoria.

3.¿Cual es la secuencia as larga de numeros ordenados entre las posicios 3a y 4f?
