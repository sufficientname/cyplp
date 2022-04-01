
```
Defina y compare diferentes aspectos de la sintaxis que Ud. considere. Ejemplifique.
```

# Identificadores

## Python

```python
# valido
foo = 1
Foo = 1
_foo = 1

# invalido
1foo = 1
```

En python los nombres de los identificadores pueden utilizar las letras minúsculas ( `a..z` ), mayúsculas ( `A..Z` ), los números ( `1..9` ) y el guion bajo ( `_` ).

Sin embargo no pueden comenzar con un número.


## Javascript

```javascript
// valido
let foo = 1
let Foo = 1
let _foo = 1
let $foo = 1

// invalido
let 1foo = 1
```

En en javascript los nombres de los identificaroes tambien pueden utilizar las letras minúsculas ( `a..z` ), mayúsculas ( `A..Z` ), los números ( `1..9` ), el guion bajo ( `_` ) y adicionalmente pueden utilizar el signo peso o signo dólar ( `$` ).

Tampoco pueden comenzar con un número.

# Operadores

Comparación entre los dos lenguajes de los principales operadores.

## Operadores de comparación

| operador      | python   | javascript   |
|---------------|----------|--------------|
| igualdad      | `==`     | `==` , `===` |
| desigualdad   | `!=`     | `!=` , `!==` |
| mayor         | `>`      | `>`          |
| menor         | `<`      | `<`          |
| mayor o igual | `>=`     | `>=`         |
| menor o igual | `<=`     | `<=`         |

Se puede ver que ambos lenguajes utilizan los mismos operadores de comparación. Sin embargo javascript cuenta con dos operadores adicionales para la igualdad y desigualdad. El operador `===` compara que dos elementos tengan el mismo valor y el mismo tipo. El operador `!==` compara que dos elementos tengan diferente valor o diferente tipo.

## Operadores aritméticos

| operador       | python    | javascript   |
|----------------|-----------|--------------|
| suma           | `+`       | `+`          |
| resta          | `-`       | `-`          |
| multiplicación | `*`       | `*`          |
| división       | `/`, `//` | `/`          |
| módulo         | `%`       | `%`          |
| potenciación   | `**`      | `**`         |
| incremento     | `n/a`     | `++`         |
| drecremento    | `n/a`     | `--`         |

En cuanto a los operadores aritméticos, ambos lenguajes utilizan los mismos símbolos. Sin embargo
python cuenta con un operador adicional para la división, el operador `//`, éste se utiliza para realizar una división entera (ej: `3 // 2 = 1`). Mientras que javascript cuenta con dos operadores adicionales para incrementar ( `++` ) o decrementar ( `--` ) en `1` el valor de una variable numérica.

## Operadores lógicos

| operador      | python   | javascript   |
|---------------|----------|--------------|
| and           | `and`    | `&&`         |
| or            | `or`     | `\|\|`       |
| not           | `not`    | `!`          |

Por el lado de los operadores lógicos, vemos que ambos lenguajes utilizan diferentes símbolos para las tres operaciones.


# Comentarios

## Python

```python
# Esto es un comentario
print("Hello, World!")  # Esto tambien es un comentario
```
Para escribir un comentario en python se debe colocar un numeral ( `#` ) todo el texto a continuación de éste hasta el salto de linea es un comentario.


## Javascript

```javascript
// Esto es un comentario de una linea

/*
Esto es un comentario de 
mas de una linea
*/
console.log("Hello, World!")  // Esto es otro comentario
```
Existen dos formas de escribir comentarios en javascript.

Los comentarios de una sola linea, comienzan con dos barras ( `//` ) todo el texto a continuación de éstas hasta el salto de linea es un comentario.

Los comentarios de mas de una linea, comienzan con una barra seguida de un asterisco ( `/*` ) y finalizan con un asterisco seguido por una barra ( `*/` ).


# Palabras clave y palabras reservadas

## Python
```
False       class       finally     is
None        continue    for         lambda
True        def         from        nonlocal
and         del         global      not
as          elif        if          or
assert      else        import      pass
break       except      in          raise
return      try         while       with
yield
```

Python cuenta con 33 palabras reservadas.


## Javascript
```
abstract    arguments 	await  	    boolean
break 	    byte 	    case    	catch
char    	class   	const   	continue
debugger 	default 	delete   	do
double  	else 	    enum    	eval
export  	extends  	false   	final
finally 	float 	    for 	    function
goto 	    if 	        implements 	import 
in      	instanceof  int 	    interface
let     	long    	native 	    new
null    	package 	private 	protected
public  	return 	    short    	synchronized
super    	switch  	static   	this
throw   	throws 	    transient 	true
try 	    typeof  	var     	void
volatile 	while   	with    	yield
```

Javascript en comparación cuenta con prácticamente el doble de palabras clave. Exactamente 64. Aunque no todas tienen una función, y solo se encuentran reservadas porque así lo requiere el estándar ECMAScript.