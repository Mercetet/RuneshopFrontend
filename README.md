# RuneshopFrontend
Frontend de una aplicación de ecommerce completa desarrollada con **React**, **Vite** y **TypeScript**.  
Incluye autenticación JWT, subida de imágenes a Cloudinary, integración con MercadoPago y un panel de administración de productos.

---

## Tecnologías

-  React + Vite
-  TypeScript
-  Axios (con interceptor para JWT)
-  Autenticación con JSON Web Tokens (JWT)
-  Cloudinary (gestión de imágenes)
-  MercadoPago (pago con checkout)
-  React Router DOM
-  LocalStorage (persistencia de sesión)

---

## Características

### Autenticación
- Registro e inicio de sesión con token JWT
- Persistencia de sesión en `localStorage`
- Rutas protegidas para usuarios autenticados

### Productos y Categorías
- Vista pública con listado de productos
- Filtro por categoría y ordenamiento por precio
- Detalle de producto con imagen, descripción y precio

### Cloudinary
- Subida de imágenes al crear o editar productos
- Previsualización instantánea

### Integración con MercadoPago
- Checkout completo con productos seleccionados
- Redirección automática y manejo del estado del pago

### Panel Admin
- ABM de productos
- Estado de activación, edición y eliminación
- Visualización de imágenes y datos cargados

---

## Instalación

Este frontend depende de una API RESTful para usuarios, productos, órdenes y pagos.
🔗 Repositorio del backend: [runeshop-backend](https://github.com/Vale-source/Runeshop/tree/backend)

Importante: Para que la aplicación funcione correctamente, también debés levantar el proyecto del backend (Runeshop) disponible en el enlace anterior.

### 1. Clonar el repositorio y correr el repositorio

```bash
git clone https://github.com/RodrigoRomero26/ecommerce-frontend.git
cd ecommerce-frontend
npm install
npm run dev
````

---

## Integrantes
. Mercedes Tetilla
. Rodrigo Romero
. Valentin Curiel
