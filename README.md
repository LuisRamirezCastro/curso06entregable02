Proyecto 2

Descripción: Crear un script de pruebas de prueba utilizando Jmeter que permita ejecutar
pruebas de carga a un sistema dado.

Evaluación: 30%

Detalles:

Las pruebas se ejecutarán contra https://www.google.com
Componentes Requeridos:
- Http Request Defaults (para utilizar requests parameters)
- Ultimate Thread Group (para generar la carga)
- Random CSV Data Set Config (leer el CSV)
- Constant timer (Para hacer una pausa entre requests)
- Assertions (validar respuestas)

Instrucciones:

1. Utilizando Jmeter.
2. Realizar un test suite que:
a. Lea un csv `id,searchTerm` (fuente de datos)
b. Ejecute un request a:
i. www.google.com/about
ii. www.google.com/search?q={searchTerm}
iii. www.google.com/search?q=asdlkasjdlasjdlkasjdlkasdas

3. Verificar:

a. Validaciones correspondientes cuando el request es exitoso.
b. Validaciones correspondientes cuando la búsqueda no contiene resultado.

Método de evaluación: Ejecutar las pruebas y verificar las validaciones y el uso de los
componentes..

Entregable:

- Crear un repositorio para el curso:
- Crear una carpeta que se llame: /load_test/
- Agregar el script del proyecto dentro de la carpeta.