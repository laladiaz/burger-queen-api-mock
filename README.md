## Información de como lo usamos para el proyecto Suchito:

Se subió a render.com y de ahi nos dió una URL para consumir el mock en nuestra aplicación. 

https://burger-queen-api-mock.onrender.com


# Burger Queen API Mock

Usando las librerías [json-server](https://github.com/typicode/json-server) 
y [json-server-auth](https://github.com/jeremyben/json-server-auth) 
se crea un mock para 
[Burger Queen API](https://app.swaggerhub.com/apis/ssinuco/BurgerQueenAPI/2.0.0)

## Ejecución

1. Clona el repositorio
2. Instala las dependencias
    ```bash
    npm install
    ```
3. Ejecuta el mock
    ```bash
    npm start
    ```
4. Ahora puedes acceder a los endpoints del API descritos en la 
[documentación](https://app.swaggerhub.com/apis/ssinuco/BurgerQueenAPI/2.0.0) 
usando como URL base [http://localhost:8080/](http://localhost:8080/).

    Tal como indica la documentación, los endpoints están protegidos 
    por token de autenticación.

    En el archivo [requests.http](./requests.http) encuentras 
    algunas peticiones de prueba que puedes ejecutar directamente 
    en VSCode usando la extensión 
    [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client).

## Información

El mock _out-of-the-box_ provee información de 2 usuarias administradoras _anita.borg@systers.xyz_ y _grace.hopper@systers.xyz_. La contraseña de ambos usuarios es _123456_

También provee información de 2 órdenes y 2 productos.
