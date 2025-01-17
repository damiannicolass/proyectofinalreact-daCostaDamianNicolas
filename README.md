# Tienda Bezier

# Ecommerce con React y Firebase

Este es un proyecto de ecommerce creado con React y Firebase, que permite a los usuarios navegar por una lista de productos, ver los detalles de cada uno, agregar productos al carrito, y realizar una compra con un checkout completo.

## Tecnologías utilizadas

- **React**: Biblioteca para construir la interfaz de usuario.
- **Firebase**: Utilizado para manejar la base de datos (Firestore).
- **Bootstrap**: Para el diseño y estilos.
- **Vite**: Como herramienta de construcción rápida de proyectos de React.
- **React Router**: Para la navegación entre componentes.

## Estructura de Componentes

El proyecto está organizado en los siguientes componentes:

### 1. **NavBar**

Barra de navegación que permite acceder a diferentes categorías y a la vista del carrito.

### 2. **CartWidget**

Ícono de carrito que muestra la cantidad de productos añadidos y permite acceder al detalle del carrito.

### 3. **ItemListContainer**

Componente principal que contiene la lista de productos.

### 4. **ItemList**

Muestra los productos individuales en forma de tarjeta.

### 5. **ItemDetailContainer**

Este componente se encarga de obtener la información de un solo producto desde Firebase para mostrar sus detalles completos.

### 6. **ItemDetail**

Muestra el detalle de un producto específico. Incluye la descripción, imagen, precio, y un botón para agregarlo al carrito.

### 7. **Checkout**

Vista donde el usuario revisa el resumen del pedido, introduce sus datos de contacto y confirma la compra. Los datos son enviados a Firebase para registrar el pedido.
