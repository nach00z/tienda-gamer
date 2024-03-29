# Tienda Ecommerce Gamer 
# Proyecto Final del Curso Desarrollo Front-end React de Coderhouse

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Proyecto Ecommerce sobre tarjetas gráficas de Amd y Nvidia. El mismo se inicia directamente en la tienda, donde podemos ver un catálogo de productos disponibles con un boton para acceder a los detalles del producto. Tambien encontramos un sencillo Login - Logout para el usuario que esta navegando.

En el apartado Detalles se podra elegir la cantidad de productos a comprar segun el stock disponible y agregar al carrito. En el carrito se tendrá la posiblidad de consultar más productos, remover una placa de video en particular o vaciar el carrito en su totalidad.

Cuando el cliente se decida con la compra podrá ver el total a pagar y deberá ingresar sus datos para confirmar la orden; la cual, al ejecurtase, irá automaticamente a la base de datos y devolvera instantáneamente el número de compra del Producto (id de la orden).

Por otra parte tenemos una página con una breve historia de las marcas, desarrollada muy básicamente.

## Dependencias Utilizadas

-Bootstrap React: Card - Cart - Button - Nav - Navbar

-Firebase

-React-router-dom

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
