---
layout: post
title: Clases prácticas
date: 2016-05-28 15:46
comments: true
external-url:
categories: álgebra I
---

# RELACIONES

### Ejercicio 1
Sea A un conjunto cuyos elementos son 1, 2 y 3. Sea R una relación definida como todos aquellos pares ordenados (A; B) pertenecientes al producto cartesiano entre el conjunto de partes de A tales que A está contenido en B.

Probar que esta releción es una relación de orden.

#### Reflexividad:
Para afirmar que esta relación es reflexiva debemos ver que cada uno de los elementos del conjunto de partes de A
está relacionado con sí mismo. Es decir, si tomo un elemento H del conjunto de partes de A, tengo que ver que H esté relacionado con H; y, en este caso, por definición de esta relación, tengo que ver que H esté contenido en H.

Por propiedad de conjuntos, se sabe que cualquiera sea el conjunto A, siempre se cumple que A está contenido en A.

Por lo tanto, es cierto decir que H está contenido en H. O sea, la relación tratada es reflexiva.

#### Antisimetría:
Esta relación es antisimétrica si al tomar dos elementos del conjunto de partes de A, llamados H y T, tales que a T está contenido en H y H está contenido en T se implica que T es igual a H.

Veamos si es así. Tomamos H y T, dos elemento del conjunto de partes de A. Si H está relacionado con T, se tiene que H está contenido en T. Por otra parte, si T está relacionado con H, se tiene que T está contenido en H. Ahora, observando y recordando que la defición de igualdad de conjuntos, podemos inferir que el conjunto H es el mismo conjunto T. Por lo tanto, esta relación es antisimétrica.

#### Transitividad:
Para ver que es transitiva, tomemos tres elementos del conjunto de partes de A llamados Q, W, y Z, tales que Q está relacionado con W y, a su vez, W está relacionado con Z. De esto último, podemos deducir que Q está contenido en W y que W está contenido en Z.

Observando y recordando que la inclusión es una operación de conjuntos que posee la propiedad de transitividad, podemos inferir que entonces T está contenido en el conjunto Z.

Por lo tanto, esta relación es transitiva.

Se ha probado que la relación mencionada es una relación de orden.

### Ejercicio 2
Sea A el conjunto de los números naturales. Sea R una relación en A definida como todos los pares ordenado (a, b) tales que a es mayor oo giual a b.
Probar que es una relación de orden.

### Ejercicio 3
Sea A el conjunto de los números naturales. Sea R una relación en el conjunto de partes de A definida como todos los pares ordenados (A; B) tales que el conjunto llamado K que tiene a los elementos 2, 7 y 9 está contenido en el complemento de la diferencia simétrica entre A y B. 
Probar que es una relación de equivalencia.

# FUNCIONES

### Definición
Una función de A en B es una relación R que está incluída en el producto cartesiano entre A y B tal
que para todo elemento del conjunto A existe un único elemento del conjunto B.

### Ejercicio 1
Sea R una relación definida por todos los pares ordenados (a, b), pertenecientes al producto cartesiano entre el conjunto de los números naturales, tales que a es igual al doble de b.
Decidir si R es una función.

#### Resolución
R no es una función porque existe al menos un elemento del conjunto de los números naturales, por ejemplo el 5, para el cuál no exite un b perteneciente a los naturales tal que 5 sea igual al doble de b. o sea, en otras palabras, no exite un b que al ser multiplicado por dos sea igual al 5. (5 no está relacionado con b perteneciente a los naturales)

### Ejercicio 2
Sea A el conjunto de todos los números naturales mayores o iguales a cero. Y sea B el conjunto del todos los números reales. Se define la relación R como el conjunto de todos los pares ordenados (a, b) pertencientes a AxB tales que a es igual al cuadrado de b.
Decidir si R es función. 

#### Resolución
Para todos los a pertenecientes a A, existe un único b real talque al cuadrado sea igual a "a"???
No, si tomamos un a igual a 1, vemos que existen dos números reales tales que sus cuadrados son iguales a 1. Dichos dos números reales son el 1 y el -1. Por lo tanto, esta relación no es una función.

### Ejercicio 3
Sea A y B dos conjuntos cuyos elementos son los números reales mayores o iguales a cero, se define la relación R como los pares ordenados pertenecientes a AxB tals que a es igual al cuadrado de b. 

#### Resolución

Veamos que esta relación sí es una función.

Cómo nos damos cuenta? 
Debemos ver si R cumple con la definición de función. Para ello debemos ver que como a es igual al cuadrado de b, entonces al aplicar la raíz cuadrada en ambas partes de la igualdad, tenemos que la raíz cuadrada de a es igual a la raíz cuadrada de b al cuadrado.

 Cuáles son los que tales que la raíz cuadrada de su cuadrado es igual a la raíz cuadrada de a?? 
En primer lugar debemos notar que b podría ser cualquier valor positivo o negativo, ya que si b es negatiivo o positivo su vuadrado será el mismo tenemos que tener cuidado. 

Debido a la última oración, es que se usa el módulo; es decir, que la raíz cuadrada de a es igual al módulo de b. Y si el módulo de b es igual a la raíz cuadrada de a, entonces tenemos dos posibles valores para b, raíz cuadrada negativa de a ó raíz cuadrada positiva de a. 

Como sabemos que a pertenece a un conjunto no negativo, entonces no hace falta ver el signo de las dos posibles de b, o sea, valores de la raíz cuadrada negativa de a y raíz cuadrada positiva de a . 

Entonces, recordando que b también es un cto. con valores no negativos. Por lo tanto, b es no negativo y de ésto se deduce que b es igual a la raíz cuadrada positiva de a.

### Definición
La imagen de una función f que va desde A hasta B es el conjunto de todos los b pertenecientes a tales que existe al menos un k perteneciente a A tal que b es igual a la imagen de a. 

##### Definición hecha por mi
La imagen de una función f que va desde A hasta B, una relación que está incluída en AxB, es el conjunto de todos los b pertenecientes a B que están relacionados con al menos un a perteneciente al conjunto A.


### Definición de función inyectiva
Es aquella función que cumple con la siguiente implicación: si la imagen de a es igual a la imagen de a', entonces a es igual a a'.

También se puede definir con una implición equivalente llamada contrarecíproca: si a es distinto a a', entonces la imagen de a es distinta a la imagen de a'.

### Definición de función subreyectiva
Es aquella función cuyo conjunto imagen es igual al codominio de la función en cuestión. 

### Definición de función biyectiva
Es aquella función que es inyectiva y sobreyectiva.

### Ejercicio 1
Decidir si las siguientes funciones son funciones inyectivas, sobreyectivas o biyectivas.

### a)
Si f es una función de reales en reales definida como f(x) igual al cuadrado de x.

No es inyectiva porque tanto 1 como -1 tienen la misma imagen.
No es sobreyectiva porque la imagen es un conjunto distinto al codominio. O sea, hay elmentos del codominio que no están en la imagen.
Como no es inyectiva y sobreyectiva, tampoco es biyectiva.

### b)
Si f es una función de números naturales en números naturales definida como f(x) igual al cuadrado de x.

Veamos si esta función es inyectiva. Recordemos que para ser inyectiva debe suceder que si dos elelmentos tienen la misma imagen, entonces estamos hablando del mismo elemento. Si tomo dos elementos, n y m, con la misma imagen, entonces f(n) es igual a f(m). Esto último es equivalente a decir que entonces el cuadrado de n es igual al cuadrado de m. entonces, al aplicar la función raíz cuadrada en ambas partes de la igualdad, tenemos que el módulo de m es igual al módulo de n; pero, como estamos tratando con números naturales, tenemos que n es igual a m. Por lo tanto, esta función es inyectiva.

Es sobreyectiva? para saberlo, debemos ver si se cumple la definición de sobreyectividad de una función. Recordemos que una función es sobreyectiva si y solo si el conjunto imagen es igual al conjunto del codominio. Entonces, el conjunto imagen es igual al conjunto de los números naturales?

Esta pregunta puede formularse de otra forma: para todo m perteneciente al conjunto de números naturales del dominio, existe al menos un n perteneciente al conjunto de los números naturales del dominio tal que la imagen de n es m?

Bueno, si tomamos al elemento 3 del codominio, veamos si existe al menos un n del dominio tal que la imagen de n es 3. Supongamos que sí existe tal n, entonces la imagen de ese n es 3. o sea, f(n) es igual  3; lo cual, según la definición de f, n al cuadrado es igual a 3. Y si estos dos valores son iguales entonces la raíz cuadrada de ambos también lo es. 

Como la raíz cuadrada de n al cuadrado es el módulo de n que, a su vez, es igual a n porque n es un número natural;  entonces n es igual a la raíz cuadrada de 3. Pero... n es un número natural y la raíz de 3 no lo es!! Entonces... bomba! albsurdo! O sea, es contradictorio decir que n es igual a la raíz de 3. 

Hemos entontrado un elemento del dominio que no pertenece al conjunto imagen, entonces estos conjuntos no son iguales, lo cuál indica que no se cumple la definición de función sobreyectiva, o sea, esta función no es sobreyectiva.


### c)
Si f es una función de números naturales a números naturales definida como n+1 para todo n impar, y n-1 para todo n par.

Queremos ver si es inyectiva, para ver si lo es debemos ver que la imagen de dos elementos implica que esos dos elementos son iguales.

Pero como la imagen de cualquier elemento del dominio, según la definición de f, depende de su paridad, entonces debemos considerar las combinaciones de pares de números que supondremos con igual imagen y ver si se deduce que se trata del mismo elemento.

Los casos serían los siguientes:

1) dos pares 
2) dos impares
3) el primer elemento elegido par y el otro impar 
4) el primer elemento impar y el otro par 

Si en cada caso mencionado se cumple la definición de función inyectiva, entonces podríamos concluír que la función es inyectiva. Repito, para tooodos los casos. Ya que si no se cumple para alguno, entonces quiere decir que aunque dos elementos tengan la misma imagen no implica que ambos elementos sean el mismo.

Caso 1. Si tomamos dos elementos pares del dominio, llamados m y n, y tenemos que la imagen de m es igual a la imagen de n entonces n-1 es igual a m-1 y si sumamos un uno a ambos números, es equivalente a decir que n es igual a m.

Caso 2. Si tomamos dos elementos impares del dominio, llamados l y k, y tenemos que la imagen de l es igual a la imagen de k; o sea, l+1 es igual a k+1 y si restamos uno a ambos números llegamos a que l es igual a k.

Caso 3. Tomo un elemento par y otro elemento impar del dominio a los cuales llamaré u y t respectivamente. Si u es par, entonces su imagen es u-1, y si t es impar, su imagen es t+1. Como suponemos que las imagenes de u y t son iguales, entonces u-1 es igual a t+1. De esta última igualdad, al sumar 1 a ambos números deducimos que u es igual t+2.

Si recordamos que t es impar entonces t es igual a 2k+1 con k natural. Y si le sumamos 2 a t, tenemos que  2k+1+2 es igual a 2k+2+1, un número impar. Pero dijimos que u es par, no impar. Entonces tenemos una contradicción que proviene de suponer que dos elementos con distinta paridad tienen igual imagen, lo cual es falso. 

Por lo tanto esta función no es inyectiva. Ya que, recordemos que la imagen de dos números distintos con distinta paridad) tienen distinta imagen. fin!!

Veamos si es sobreyectiva. 


Para ver si es sobreyectiva, debemos ver que para todo k perteneciente al codominio existe n perteneciente al dominio tal que f(n) es igual a k.

Pero como la imagen depende de la paridad de n, tendremos que analizar por casos.
Antes de hcer el analisis considero necesario observar la función para tomar nota de su comportamiento.

Durante la observación tratemos de conjeturar el conjunto imagen.
Veamos que, en principio, la imagen de un elemento del codominio depende de la paridad del elemento en cuestión.

Si n perteneciente a los naturales es par, entonces la imagen me dará un número impar.
Si n perteneciente a los naturales es impar, entonces la imagen me darpa un número par.

De esto podemos conjeturar que la imagen de todos lo números pares del dominio son los números impares del codominio y que la imagen de todos lo números impares del dominio son los números pares del codominio. Y como la unión de pares e impares pertenecientes al codominio es todo el codominio, o sea, es todo el conjunto de los número naturales (ya que la imagen de 1 es 2, la imagen de 2 es 1, la imagen de 3 es 4, la imagen de 4 es 3....podemos conjeturar que la imagen es el conjunto de todos los números naturales. 

Vamos a probarlo. Cómo hago? 
Teniendo en cuenta la definición de dunción sobreyectiva, basta ver que la imagen es igual al codominio. Y por definición de la imagen, es lo mismo a querer ver que para todo k perteneciente al codominio existe al menos un n perteneciente al dominio tal que la imagen de n es igual a k.

Si k pertenece al codominio, entonces k pertenece a la unión de los números pares e impares.

Como la imagen depende de la paridad de f, entonces según las observaciones realizadas anteriormente debo ver si efectivamente la imagen de los pares del dominio es el conjunto de los impares del codominio y, a su vez, la imagen de los impares del dominio es el conjunto de los pares de codominio.


En este paso, pienso que hay dos formas de probarlo. Enunciaré a ambas a continuación.

##### Forma I:
Ver si existe n par tal que la imagen de n es igual a k impar.
Si k es impar y n par, entonces la imagen de n es n-1, un número impar.
Si k es par y n impar, entonces la imagen de n es n+1, un número par.

y como la unión entre los números pares e impares es igual al codominio, entonces la función es sobreyectiva.

##### Forma II:
Ver si existe n del dominio tal que su imagen es k impar.
Según la conjetura realizada anteriormente, la imagen de k impar le corresponde a algún n par, quiero ver si existe tal n.
Entonces, si tomo n par, tomo n igual a k+1 (un número impar mas 1 es un número par), esto último es equivalente a decir que la imagen de k+1 es igual a k+1-1 (por def. de la función). Por último, lo anterior es equivalente a decir que la imagen de tal n es igal a k. 
Por lo tanto existe n del dominio tal que la imagen es k impar.

Ver si axiste n del dominio tal que su iamgen es k par.
También, según la conjetura realizada anteriormente, la imagen de k par le corresponde a algún n impar, quiero ver si existe tal n.
Entonces, si tomo n impar, tomo n igual k-1 

nota: me conviene que sea k-1 porque al aplicar def. de f tendriamos la imagen de n igual a k , como queremos. Si tomaramos k+1 , que también es impar, no tendríamos la imagen igualda a k+2 que sería cualquier k del codominio mas dos unidades. O sea, no representaria a todos los pares del codominio ya que k comienza a tomar valores naturales y el par mas pequeño sería 4 (por lo que habríamos omitido al 2, un elemento que debería estar porque es par y natural).

Terminando con lo anterior, al tomar n igual a k-1 y evaluarlo en f tenemos que su magen es k-1+1, o sea igual a k par como queríamos. 
Port lo tanto existen n pertenecientes al dominio tales que la imagen de estos me dan todos los números k apres de codominio.

Por último, repitiendo lo que escribí anteriormente, como la unión de los impares naturales y pares naturles es igual al conjunto del codominio, podemos afirmar que la función en cuestión es sobreyectiva. 


amo razonar!


