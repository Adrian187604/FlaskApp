# FlaskApp
 Desarrollo de una aplicación Flask compatible con firebase para el funcionamiento de un dispensador de alimentos y agua para mascotas.

# Para realizar pruebas

 Registrar Usuario en BD

    - [http://127.0.0.1:5000/](http://127.0.0.1:5000/refresh)register
    - Body:

{
"username": "Pedro123",
"password": "Hola123456"
}

Crear Token (Inicio de sesión)

    - [http://127.0.0.1:5000/](http://127.0.0.1:5000/refresh)login
    - Body:

{
"username": "Pedro123",
"password": "Hola123456"
}

Refresh token

    - http://127.0.0.1:5000/refresh

    - Headers:
    
    Authorization: Bearer {refresh token}
    

Rutas protegidas (User)

    - [http://127.0.0.1:5000/](http://127.0.0.1:5000/refresh)user
    - Authorization: Bearer {access token}