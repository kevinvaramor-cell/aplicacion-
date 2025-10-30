# 🐾 MascotasApp

Aplicación Android desarrollada como parte del proyecto **“Integrando Material Design con identidad personalizada”**.  
Esta app muestra una lista de mascotas con opción para calificarlas con un “hueso” y acceder a una pantalla de favoritos.

---

## 🚀 Características principales

### 🐶 Parte 1 – Lista de Mascotas
- RecyclerView con una lista de mascotas.
- Cada mascota puede recibir “likes” presionando el ícono de hueso.
- El hueso cambia de color (blanco → amarillo) y se incrementa el contador.
- Uso de **Material Design**, `CardView` y `RecyclerView`.

### 🌟 Parte 2 – Mascotas Favoritas
- Action View con ícono de **estrella** en la barra superior.
- Navega hacia un nuevo Activity que muestra 5 mascotas favoritas *dummy*.
- Toolbar con botón de regreso al Activity principal.

---

## 🏗️ Estructura del proyecto

```
MainActivity.kt        → Lista de todas las mascotas
MascotaAdapter.kt       → Controla la vista de cada ítem del RecyclerView
Mascota.kt              → Clase de datos Mascota(nombre, foto, rating)
FavoritasActivity.kt    → Muestra 5 mascotas favoritas “hardcodeadas”
item_mascota.xml        → Diseño individual de cada mascota
activity_main.xml       → Pantalla principal con RecyclerView
activity_favoritas.xml  → Pantalla de favoritos
menu_main.xml           → Menú superior con Action View estrella
```

---

## 🧱 Tecnologías utilizadas

- Kotlin
- RecyclerView
- Toolbar y ActionView
- Material Design
- Android Studio Giraffe+
- Min SDK: 23 (Android 6.0)
- Target SDK: 34

---

## 🖼️ Capturas de pantalla

| Pantalla Principal | Favoritos |
|--------------------|------------|
| ![Main](screenshots/main.png) | ![Favs](screenshots/favoritas.png) |

---

## 🔗 Enlace del recurso del ícono

El ícono de estrella fue tomado de:  
👉 [http://ic8.link/10206](http://ic8.link/10206)

---

## 👨‍💻 Autor

**Tu Nombre**  
Proyecto académico - Módulo 2  
📆 Octubre 2025  

---

## 🧩 Evaluación esperada

✅ Proyecto ejecuta correctamente  
✅ RecyclerView funcional  
✅ DataSet y Adapter  
✅ ViewHolder correctamente implementado  
✅ Ítem con rating dinámico  
✅ Action View de estrella funcional  
✅ RecyclerView con 5 items dummy  
✅ Retorno al Activity principal  
