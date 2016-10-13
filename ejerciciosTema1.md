## David Brao Serrano

# Ejercicios Tema 1

## Ejercicio 1. Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años.

La tienda que he consultado ha sido Pc Componentes: https://www.pccomponentes.com/hp-proliant-ml110-g9-e5-v4-8gb
Servidor: HP ProLiant ML110 G9 E5 v4/8GB
Precio:  999€ 

Precio del servidor = 999€ . 26% de 999€  = 259,74€

### Amortización a 4 años

259,74€ x 4 = 1038,96€

### Amortización a 7 años

259,74€ x 7 = 1818,18€

## Ejercicio 2. Usando las tablas de precios de servicios de alojamiento en Internet y de proveedores de servicios en la nube, Comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

## Ejercicio 3. 

### 1. ¿Qué tipo de virtualización usarías en cada caso? Comentar en el foro

-	Virtualización de aplicaciones: Cuando se quiere ejecutar una aplicación que es de un sistema operativo al que se tiene, se utiliza este tipo de virtualización.
- 	Virtualización plena: Para probar un sistema operativo completo se utiliza virtualización plena.

### 2. Crear un programa simple en cualquier lenguaje interpretado para Linux, empaquetarlo con CDE y probarlo en diferentes distribuciones.

Imprimir los numeros impares desde el 1 al 50, ambos inclusive
n = 1
h = ''
while n <= 50:
    if n%2 != 0:
        h += ' %i' % n
    n += 1
print h

Instalar el paquete **CDE** -> **sudo apt-get install cde**

Para empaquetar el programa y poder ejecutarlo, utilizamos la orden: cde python empieceMayus.py

## Ejercicio 4. Comprobar si el procesador o procesadores instalados tienen estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden?

El procesador de mi portátil es un Intel Core i5 4210U @ 2.40GHz

## Ejercicio 5. 

-	Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok.
-	Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.