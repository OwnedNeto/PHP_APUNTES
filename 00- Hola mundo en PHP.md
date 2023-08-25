## "hola mundo"

## Iniciar servicio apache
Para poder crear un doc PHP es necesario iniciar los servicios de apache  que en esta caso usaremos xampp.

![[Pasted image 20230824073356.png]]

## Creación de carpeta
Ahora bien en nuestra ruta de donde se instalo xampp buscaremos la carpeta htdocs ya hi crearemos nuestra carpeta para poder hacer nuestro proyectos de PHP.
![[Pasted image 20230824073455.png]]


## Abrir carpeta.
Abriremos nuestra carpeta que creamos con visual studio code y comenzaremos a trabajar.
![[Pasted image 20230824073330.png]]


## Variables y su uso 

-Variable con asignación para php.
![[Pasted image 20230824073823.png]]
Las variables de PHP se declaran con signos de peso "$"
![[Pasted image 20230824074245.png]]

## Algunas reglas para nombrar variables en PHP son las siguientes

1. Usar únicamente caracteres latino (0-9, a-z, A-Z) y guion bajo.
2. No utilizar caracteres especiales.
3. Si se puede utilizar guion bajo al comienzo del nombre de una variable.
4. Nombrar las variables con significado semántico.
5. Tener en cuenta que se distinguen entre nombres con mayúsculas y minúsculas.
6. Evitar palabras reservadas.

La definición de constantes se hace con la función define() como primer parámetro el nombre de la constante y como segundo parámetro el valor de dicha constante.

Para imprimir variables y constantes usamos la concatenación.

![[Pasted image 20230824075634.png]]

## Operaciones Aritméticas 

Las operaciones aritméticas en PHP no son diferentes a otros lenguajes, y se muestran de la siguiente manera: 

![[Pasted image 20230824215831.png]]



## Operaciones Lógicas


| Nombre | Símbolo  |
| ------ | -------- |
| And    | && o And |
| Or     | Or I     |
| Not    | !        |

![[Pasted image 20230824234139.png]]
## Operadores de comparación

| Ejemplo        | Nombre            |
| -------------- | ----------------- |
| $a == $b       | igual             |
| $a=== $b       | idéntico          |
| $a != $b       | Diferente         |
| $a !== $b      | No idéntico       |
| $a <> $b       | Diferente         |
| $a < $b        | Menor que         |
| $a > $b        | Mayor que         |
| $a <= $b       | Menor o igual que |
| $a >= $b       | Mayor o igual que |
| $a <=> $b      | Nave espacial     |
| $a ?? $b ?? $c | Fusión de null    |
|                |                   ||                   |




## if else
Para usar
![[Pasted image 20230824085346.png]]

## Swicht
Es una estructura de control que nos ayudara ah evaluar opciones ya destinadas y que solo el usuario podrá obtener algo preciso sobre eso y si no encuentra algún caso lo mandara al default
	
![[Pasted image 20230824233823.png]]


## While

Una caracteristica de while esque primero evalua y luego ejecuta
![[Pasted image 20230824091023.png]]
## Do while
Do while noes permite ejecutar un bloque de codigo siempre que se cumpla una condicion, una caracteristica de Do while esque primero ejecuta y despues evalua.
![[Pasted image 20230824091430.png]]

## Arreglos

Los Arreglos pueden combinar tipo de datos sin ningun problema.

![[Pasted image 20230824092127.png]]

# Objetos

Los objetos en PHP únicamente existen cuando son instancias de una clase.
## Arreglos asociativos
Clave-valor es como se definen esto arreglos.
![[Pasted image 20230824093415.png]]

## For
 es una estrucuta que nos permite iterar mientras una condicion se cimple, se utiliza de la sig manera:
 ![[Pasted image 20230824094319.png]]
## Foreach

