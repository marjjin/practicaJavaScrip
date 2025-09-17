# practicaJavaScrip

#Ejercicio 1

Implementá una función procesarNumeros(array, transformarCb, filtrarCb) que reciba el arreglo [2, 5, 7, 10, 12], primero aplique un callback que multiplique cada número por 3 (obteniendo [6, 15, 21, 30, 36]) y luego aplique un segundo callback que filtre solo los números mayores a 20, devolviendo como resultado final [21, 30, 36].

#Ejercicio 2

Implementá una función buscarUsuario(arr, criterioCb) que reciba el arreglo

[{ id: 1, nombre: "Ana", edad: 22 }, { id: 2, nombre: "Luis", edad: 30 }, { id: 3, nombre: "María", edad: 19 }, { id: 4, nombre: "Pedro", edad: 25 }]


y utilice un callback para encontrar el primer usuario cuya edad sea mayor o igual a 25, devolviendo como resultado final { id: 2, nombre: "Luis", edad: 30 }.


$Ejercicio 3

Implementá una función crearContador(inicio, paso) que use un closure para mantener un valor interno, de modo que al invocarla con const contador = crearContador(10, 5) la primera llamada a contador.next() retorne 15, la segunda 20, y luego de ejecutar contador.reset() la siguiente llamada a contador.next() retorne nuevamente 15.
