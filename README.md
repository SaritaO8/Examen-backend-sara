# Examen-Intro-Backend-Sara

# 📚 Tienda Librería

Este proyecto representa un **modelo inicial (conceptual y lógico)** para un sistema de gestión de una **librería**, basado en un **diagrama Entidad-Relación** y una **estructura tabular en hojas de cálculo**.
## 🎯 Objetivo del proyecto

Modelar la información básica necesaria para administrar:

* Libros 📖
* Autores ✍️
* Categorías 🗂️
* Clientes 👤
* Ventas 💰

Todo con el fin de entender cómo se relacionan las entidades y cómo podrían implementarse en una base de datos.

---

## 🧩 Diagrama Entidad–Relación (DER)

El sistema está compuesto por las siguientes entidades principales:

### 📘 Libros

Atributos:

* ISBN
* Título
* Autor
* Editorial
* Precio
* Stock
* Categoría

Relaciones:

* Un **libro pertenece a una categoría**
* Un **libro tiene uno o más autores**
* Los **libros son vendidos a clientes**

---

### 🗂️ Categorías

Ejemplos:

* Infantil
* Romance
* Ciencia Ficción

Relación:

* Una categoría puede tener **muchos libros**

---

### ✍️ Autores

Ejemplos:

* Antoine de Saint-Exupéry
* Jane Austen
* George Orwell

Relación:

* Un autor puede escribir **uno o varios libros**

---

### 👤 Clientes

Atributos:

* ID_Cliente
* Nombre
* Correo electrónico
* Dirección
* Teléfono

Relación:

* Un cliente puede comprar **uno o varios libros**

---

## 📊 Modelo en hoja de cálculo

El proyecto incluye una representación tabular con información como:

### 📄 Tabla Libros

* ISBN
* Título
* Autor
* Fecha de publicación
* Editorial
* Categoría
* Precio
* Stock

### 📄 Tabla Clientes

* ID_Cliente
* Nombre_cliente
* Correo_cliente
* Dirección_cliente

## 🚧 Limitaciones actuales

* ❌ No todas las claves primarias y foráneas están definidas
* ❌ No existe una tabla formal de ventas
* ❌ Hay datos repetidos (no normalizado)
* ❌ Falta manejo de múltiples autores por libro

---

## 🚀 Posibles mejoras futuras

* Normalización hasta 3FN
* Creación de tablas intermedias (Libro_Autor, Ventas)
* Modelo fisico

<img width="1085" height="483" alt="image" src="https://github.com/user-attachments/assets/f5f7768d-7d22-451f-8ccf-eadb17aa8111" />
<img width="1917" height="810" alt="image" src="https://github.com/user-attachments/assets/8e82eca5-c249-4d2d-9614-e7d31fd890ff" />

