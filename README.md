# Prueba - Cafetería Nanacao

En esta prueba validaremos nuestros conocimientos de testing unitario a una API REST con JEST y el paquete supertest. Para lograrlo, necesitarás aplicar los matchers del framework y estudiar con cuidado la composición del servidor de apoyo disponible entre los archivos de esta unidad.

Lee todo el documento antes de comenzar el desarrollo individual, para asegurarte de tener el máximo de puntaje y enfocar bien los esfuerzos.

## Descripción

La Cafetería Nanacao está abriendo una nueva sucursal en el centro de la ciudad después de tener un gran éxito en su local principal.

Su dueña, Julieta Nanacao, ha solicitado luego de varios fallos repentinos en su sistema de administración, que se desarrollen tests para comprobar que todas las funcionalidades funcionen correctamente.

En este desafío deberás crear tests para probar las diferentes rutas existentes en la API REST de apoyo

## Requerimientos

1. Testea que la ruta __GET /cafes__ devuelve un status code __200__ y el __tipo de dato__ recibido es un arreglo con por lo menos __1__ objeto. __(3 Puntos)__

2. Comprueba que se obtiene un código __404__ al intentar eliminar un café con un __id__ que no existe. __(2 Puntos)__

3. Prueba que la ruta __POST /cafes__ agrega un nuevo café y devuelve un código __201__. __(2 Puntos)__

4. Prueba que la ruta __PUT /cafes__ devuelve un status code __400__ si intentas actualizar un café enviando un __id__ en los parámetros que sea diferente al id dentro del payload. __(3 Puntos)__

😊¡Mucho éxito!

Consideraciones y recomendaciones |
--- |
Consulta la [documentación oficial de JEST](https://jestjs.io/docs/expect) para conocer todos los matchers que ofrece. </br></br> Lee detalladamente el código del servidor para comprender cómo funciona cada ruta. |