# Gestión de Productos - Arquitectura en Tres Capas

## Estructura del Código

- `/data/products.js`: Capa de acceso a datos, gestiona la lista de productos en memoria.
- `/services/productService.js`: Capa de lógica de negocio, maneja validaciones y operaciones sobre los productos.
- `/routes/productRoutes.js`: Capa de presentación, expone la API para agregar y listar productos.
- `server.js`: Punto de entrada que inicializa el servidor Express.

## Ventajas respecto a la versión Monolítica
- **Código más organizado y modular**, facilitando mantenimiento y escalabilidad.
- **Separación de responsabilidades**, lo que permite modificar una capa sin afectar las otras.
- **Mejor reutilización del código**, ya que la lógica de negocio no está ligada a una única implementación.
