## Respuestas a los ejercicios

1. Preprocesa, compila al assembler, compila el assembler a un .o, linkea con librerias para generar el ejecutable

2. Agrega el archivo calculator.pp.c

3. En el assembler
	Ln 23 `call add_numbers`
	Ln 29 `call printf`

4. `T add_numbers`
`T main`
`U printf`

add_numbers es ....
main es ....
printf es ....

5. `T add_numbers`
`T main`
`U printf@@GLIBC_2.2.5`

Al generar el ejecutable linkea con una librería dinámica para ubicar el printf
