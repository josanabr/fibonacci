# Demo Fibonacci

En este repositorio tenemos un demo de la implementación del algoritmo de fibonacci en C.

A continuación indicaremos como se compila el programa de este repositorio.

## Compilando el código

Para compilar este código se espera que usted tenga instalado el programa `gcc`.
Por favor, ejecute el comando de la siguiente manera:

```
gcc
```

Lo que debería ver en pantalla es algo como esto, si tienes un Mac:

```
clang: error: no input files
```

Ahora procedemos a compilar el código:

```
gcc fibo.c -o fibo -lm
```

El resultado de ejecutar este código es un archivo llamado `fibo`. 
Ejécutelo:

```
./fibo
```

Y debería obtener esto:

```
1.732051
```
