Proyecto Final Logica
# 📚 MEDIAVERSO

**MEDIAVERSO** es una aplicación web construida con **Java** y **Vaadin Flow**, que permite gestionar una lista multimedia con funcionalidades como agregar, visualizar, filtrar, eliminar y mostrar estadísticas de contenido (videos, imágenes, libros, etc.).

---

## 🛠 Requisitos Previos

- **Java JDK 17** o superior  
- **Maven 3.8+**  
- IDE recomendado: **IntelliJ IDEA** o **Eclipse**  
- Navegador moderno (Chrome, Firefox, Edge)

---

## 📦 Estructura del Proyecto
src/main/java//resource/static/images/banner.png,logo.png

---

## 🧩 Funcionalidades

| Característica      | Descripción |
|---------------------|-------------|
| ➕ Agregar           | Añade un nuevo ítem con título, género, descripción, URL, calificación y estado de préstamo. |
| 👁 Vista previa      | Abre un **Dialog** con información y previsualización del recurso (imagen o video). |
| 🗑 Eliminar          | Elimina el ítem seleccionado de la lista. |
| 📊 Estadísticas      | Muestra el ítem mejor calificado. |
| 🎯 Filtro por género | Muestra solo los ítems de un género específico. |
| 🔍 Búsqueda          | (en progreso o por implementar, si no está activa aún) |

---

## 🖼️ URLs Soportadas

| Tipo         | Formato |
|--------------|---------|
| Imágenes     | `.jpg`, `.png`, `.gif` |
| YouTube      | `https://www.youtube.com/watch?v=ID`, `https://youtu.be/ID` |
| Otros tipos  | Se mostrará como "formato no compatible para vista previa" |

---

## ✅ Buenas Prácticas

- Valida todos los campos antes de agregar un nuevo ítem.
- Usa `@Route("principal")` correctamente para mapear la vista.
- Usa una arquitectura clara y separa componentes si el proyecto crece.
- Si cargas imágenes desde recursos estáticos, asegúrate que estén dentro de `resources/static`.

---

## 📂 Pendiente / Mejoras Futuras

- Implementar persistencia con base de datos.
- Agregar búsqueda por título.
- Incorporar estilos CSS personalizados externos.
- Validación más robusta de URLs.
- Autenticación de usuarios (opcional).

---

## 👨‍💻 Autor

Desarrollado por **[Juan Pablo Rivera Ramirez]**
