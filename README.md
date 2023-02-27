# Reto_4
# Números primos 


    [variables]
    n : entero
    i : entero
    inicio
    ingresa n
    si n=1
	escribir("n  es primo ")
	fin
    no i := 2
    Mientras (i < n) hacer
    Si modulo(n,i) == 0 entonces
    escribir("n no es primo ")
	fin
    sino
    i := i + 1
	si (i=n) 
	Si modulo(n,i) == 0 entonces
    escribir("n  es primo ")
    fin
[![image.png](https://i.postimg.cc/w3YdRQY0/image.png)](https://postimg.cc/p5CSg8TF)
# Hallar raices 
    Variables
    r : entero
    z : flotante
    a : entero
    b : entero
    c : entero
    d : entero
    e : entero
    f : entero
    g : entero
    inicio
    ingresa r
    r >=0
    a =1
    Mientas (a)(a) < r
    a = a+1
    Si (a)(a) = r
    z = a 
    imprimir z
    Si (a)(a) > r
    a = a-1
    b = r-(a)(a)
    b = (b)(100)
    c = 1
    Mientras (c)(c) < b
    c = c+1
    Si (c)(c) = b
    z = a,b
    imprimir z
    Si (c)(c) > b
    c = c-1
    d = b-(c)(c)
    d = (d)(100)
    e = 1
    Mientras (e)(e) > d
    e = e+1
    Si (e)(e) = d
    z = a,bd
    imprimir z
    Si (e)(e) > d
    e = e-1
    f = d-(e)(e)
    f = (f)(100)
    g = 1
    Mientras (g)(g) < f
    g = g+1
    Si (g)(g)=f
    z = a,bdf
    imprimir z
    Si (g)(g) > f
    g = g-1
    z = a,bdf
    imprimir z
    fin
[![A.png](https://i.postimg.cc/kMVm8brF/A.png)](https://postimg.cc/mhGJWhgt)
