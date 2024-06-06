# Coder House - Backend - Ecommerce

## Documentación de la aplicación
### Introducción
Esta aplicación es un backend para una tienda en línea. Permite a los usuarios registrarse, iniciar sesión, ver productos, agregar productos a un carrito y realizar pedidos.

## Scripts

1. Ejecuta el script de inicio: `npm start` 
    - Este comando inicia la aplicación en entorno de producción
2. Ejecuta el script de desarrollo: `npm run dev`
    - Este comando inicia la aplicación en entorno de desarrollo
3. Ejecuta el script de test: `npm run test`
    - Este comando inicia la los test integrales para para carritos , productos y sessiones
4. Accede a la aplicacion localmente en: `http://localhost:8080`.




### Views
#### Home
En la vista de inicio presentacion de la aplicacion y botones para acceder a las vistas.

#### /login
En la vista de login se muestra un formulario para iniciar sesión, si el usuario no está registrado, puede acceder al registro desde la vista de login ("Not a Member Yet? Create an Account").
Tambien si no recuerda su contraseña puede recuperarla desde la vista de login ("Forgot your password?").

#### /register
En la vista de registro se muestra un formulario para crear una cuenta, si el usuario ya está registrado, puede acceder al login desde la vista de registro ("Already a Member? Login").

#### /resetPassword
En la vista de recuperacion de contraseña se muestra un formulario para recuperar la contraseña, si el usuario ya está registrado, recibirá a su cuenta de correo un link para recuperar la contraseña.

##### /products
En la vista de productos se muestra un listado de todos los productos disponibles.

##### /carts/:id
En la vista de carrito se muestra el listado de productos agregados al carrito, se puede eliminar un producto del carrito, cambiar la cantidad de cada producto, vaciar el carrito o realizar un pedido.

#### /profile
En la vista de perfil se muestra la informacion del usuario logueado, se puede subir la documentacion requerida como personal id, prueba de domicilio o estado de cuenta para pasar el rol del usuario a Premium.

#### /chat
En la vista de chat se muestra un chat en tiempo real para que los usuarios puedan comunicarse entre si.

#### /realtimeproducts
En la vista de realtimeproducts se muestra un listado de productos existentes y permite crear nuevos, editar o eliminarlos si el administrador o usuario premium lo desea. Cada usuario solo puede eliminar o editar los sus propios productos, no puede editar o eliminar productos de otro Owner. El administrador puede editar o eliminar todos los productos. 

#### /useradminmanager
En la vista de useradminmanager se muestra un listado de usuarios existentes y permite eliminarlos si el administrador lo desea o cambiar el rol directamente desde la vista.


## Tecnologías utilizadas
- Node.js
- Express.js
- Socket.IO
- MongoDB
- Mongoose
- Bcrypt
- Passport.js
- GitHub OAuth
- JWT
- Nodemailer
- Handlebars
- Winston
- Dotenv
- Swagger
- Nodemon
- Supertest
- Faker
- Chai
- Mocha
- Multer
- Bootstrap


