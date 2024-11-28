

```markdown
# Aplicación de Restaurante con Ionic 8 y MongoDB

Esta es una aplicación de restaurante desarrollada con Ionic 8 y que utiliza MongoDB como base de datos. Permite gestionar menús, órdenes de clientes y reservas.

## Características

- Crear, leer, actualizar y eliminar menús
- Gestionar órdenes de clientes
- Reservas de mesas
- Autenticación de usuarios
- Panel de administración

## Tecnologías Utilizadas

- [Ionic 8](https://ionicframework.com/)
- [MongoDB](https://www.mongodb.com/)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu_usuario/tu_repositorio.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd tu_repositorio
    ```
3. Instala las dependencias del backend:
    ```bash
    cd backend
    npm install
    ```
4. Configura las variables de entorno en un archivo `.env` en el directorio `backend`:
    ```env
    MONGO_URI=tu_uri_de_mongodb
    JWT_SECRET=tu_secreto_jwt
    ```
5. Inicia el servidor del backend:
    ```bash
    npm start
    ```
6. Instala las dependencias del frontend:
    ```bash
    cd ../frontend
    npm install
    ```
7. Inicia la aplicación de Ionic:
    ```bash
    ionic serve
    ```

## Uso

1. Accede a la aplicación en el navegador a través de `http://localhost:8100`.
2. Regístrate o inicia sesión con una cuenta de administrador.
3. Gestiona los menús, órdenes y reservas desde el panel de administración.

## Contribuir

1. Haz un fork del proyecto.
2. Crea una nueva rama con tu funcionalidad: `git checkout -b mi-nueva-funcionalidad`
3. Realiza tus cambios y haz commits descriptivos.
4. Envía tus cambios: `git push origin mi-nueva-funcionalidad`
5. Abre una solicitud de pull en GitHub.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

Espero que te sea útil. ¿Algo más en lo que pueda ayudarte? 😄
```
