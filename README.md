# Basicos - Club de Algoritmia ESCOM
![Algoritmia ESCOM](https://pbs.twimg.com/profile_images/1278839932589617155/80Aaj47m_400x400.jpg)

## Clase de Sets

### ¿Qué es un *SET*?

### Matemáticas

> Es una colección o clase de objetos bien definidos. Estos objetos se llaman elementos o miembros del conjunto.
> Los conjuntos se denotan por letras mayúsculas y los elementos con letras minúsculas.


![Conjuntos](https://www.conoce3000.com/html/espaniol/Libros/Matematica01/imagenes/UnionConjuntos03.jpg)

### Programación -> Estructura de datos

> Un conjunto es una estructura de datos que puede almacenar cualquier número de valores **únicos** en el orden que desee. Los conjuntos son diferentes de los arreglos en el sentido de que solo permiten valores únicos no repetidos dentro de ellos.

### Tipos de Sets

* `set<datatype> name`
    * Propiedades:
        1. Ordenado: Por defecto es en orden *ascendente*
        2. Valores: Todos los valores son *únicos* (no se repiten)
        3. Valores inmutables: No se puede *modificar* una vez adentro del set
        4. Usamos **iteradores** para acceder.
        5. Son implementados en *red-black trees*

    ![Red Black tree](https://camo.githubusercontent.com/a71d526a5cab7a42a8292610a52d28e893ef550a078fad1e945a43d1b44c8461/68747470733a2f2f63646e2e7261776769742e636f6d2f6d61656c76616c6169732f636f6d706f7274656d656e742d61726272652d726f7567652d6e6f69722d617665632d646f742f61356166666234322f6578656d706c655f616e696d6174696f6e2e676966)

* `unordered_set<datatype> name`
    * Propiedades:
        1. No ordenado
        2. Valores: Todos los valores son *únicos* (no se repiten)
        3. Valores inmutables: No se puede *modificar* una vez adentro del set
        4. Usamos **iteradores** para acceder.
        5. Son implementados en *hash tables*

    ![Hash table](https://d18l82el6cdm1i.cloudfront.net/uploads/34EvJ7agjl-hash_table.gif)


#### Los que ya no son únicos🙄

* `multiset<datatype> name`
    * Propiedades: Mismas que un `set` excepto la segunda. Podemos almacenar un valor `n` veces.

* `unordered_multiset<datatype> name`
    * Propiedades: Mismas que un `unordered_set` excepto la segunda. Podemos almacenar un valor `n` veces.


## Funciones/Métodos

### Iteradores

* `begin()`: Retorna un 