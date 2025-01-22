# LiterAlura: Catálogo de Libros 📚  

Este proyecto fue desarrollado utilizando **Java 17** y **Spring Boot**, aplicando los conocimientos adquiridos en el curso **Java y Spring Framework G7 - ONE**. Cumple con los requerimientos especificados en el reto **LiterAlura**, con el objetivo de crear un Catálogo de Libros interactivo y funcional.  

---

## 🌟 Descripción del Proyecto  

**LiterAlura** es una aplicación de consola que permite a los usuarios interactuar con un catálogo de libros. La información se obtiene desde una API externa de libros, manipulando datos en formato JSON para almacenarlos en una base de datos. Los usuarios pueden realizar búsquedas, filtrar resultados y consultar estadísticas relacionadas con los libros y autores disponibles.  

---

## 🛠️ Funcionalidades  

Al iniciar, la aplicación muestra un mensaje de bienvenida y un menú interactivo con las siguientes opciones:  

### 1. **Buscar libro por título**  
- Permite al usuario introducir el título de un libro para buscarlo en la base de datos.  
- Muestra información detallada del libro, incluyendo:  
  - **Título completo**  
  - **Autor**  
  - **Idioma**  
  - **Número de descargas**  

### 2. **Listar libros registrados**  
- Presenta una lista de todos los libros registrados en la base de datos, ordenados alfabéticamente.  
- Muestra:  
  - **Título completo del libro**  
  - **Autor**  
  - **Idioma**  
  - **Número de descargas**  

### 3. **Listar autores registrados**  
- Proporciona una lista de los autores disponibles en la base de datos, ordenados alfabéticamente.  
- Muestra:  
  - **Nombre completo del autor**  
  - **Fecha de nacimiento**  
  - **Fecha de defunción (si aplica)**  
  - **Libros disponibles en la base de datos**  

### 4. **Listar autores vivos desde un año específico**  
- Al ingresar un año, se genera una lista de autores vivos a partir de esa fecha.  
- Incluye:  
  - **Nombre completo del autor**  
  - **Fecha de nacimiento**  
  - **Fecha de defunción (si aplica)**  

### 5. **Listar libros por idioma**  
- Permite filtrar libros según su idioma. Idiomas disponibles:  
  - **EN** - Inglés  
  - **ES** - Español  
  - **FR** - Francés  
  - **PT** - Portugués  
- Muestra información como:  
  - **Título completo del libro**  
  - **Autor**  
  - **Fecha de nacimiento y defunción del autor (si aplica)**  

### 6. **Top 10 libros más descargados**  
- Presenta una lista con los 10 libros más populares de la base de datos.  
- Incluye:  
  - **Número de descargas**  
  - **Título del libro**  
  - **Autor**  
  - **Idioma**  

### 7. **Listar libros registrados por autor**  
- Solicita al usuario seleccionar un autor de la lista disponible.  
- Muestra los libros registrados de dicho autor con:  
  - **Título completo**  
  - **Idioma**  
  - **Número de descargas**  

### 8. **Estadísticas**  
- Ofrece un resumen estadístico con:  
  - **Promedio de descargas por libro**  
  - **Mayor cantidad de descargas**  
  - **Menor cantidad de descargas**  

### 0. **Salir**  
- Finaliza la aplicación con un mensaje de despedida personalizado.  

## 📜 Requisitos  

- **Java 17**  
- **Spring Boot**  
- Conexión a internet para acceder a la API de libros. 
