# 🏥 MiSalud UMSS – Sistema de Reservas de Fichas Médicas

Este es un sistema de escritorio desarrollado en **Python** con interfaz gráfica basada en `customtkinter`, orientado a permitir a estudiantes y usuarios de la Universidad Mayor de San Simón (UMSS) **reservar, visualizar y cancelar fichas médicas**, así como generar comprobantes de reserva.

---
### Pantalla de Login
![Login](PycharmProjects/MiSaludUmss-SISINFO1/imagenes/Login.png)
### Pantalla de Menu
![Menu](PycharmProjects/MiSaludUmss-SISINFO1/imagenes/Menu.png)
### Pantalla de Historial
![Historial](PycharmProjects/MiSaludUmss-SISINFO1/imagenes/Historial.png)
### Pantalla de Cancelar
![Cancelar](PycharmProjects/MiSaludUmss-SISINFO1/imagenes/Cancelar.png)

## 📂 Estructura del proyecto


---

## ⚙️ Funcionalidades principales

### ✅ Registro e inicio de sesión
- Registro de nuevos usuarios.
- Validación de credenciales al iniciar sesión.
- Datos almacenados en `datos/usuarios.txt`.

### 📅 Reservar ficha médica
- Selección de fecha, hora y médico.
- Registro de ficha en `datos/fichas.txt`.

### 🧾 Ver fichas reservadas y generar comprobante
- Visualización de fichas propias.
- Posibilidad de generar comprobante `.txt`.

### ❌ Cancelar una ficha
- Cancelación de fichas mediante fecha específica.
- Actualización automática del archivo.

---

## 🖼️ Interfaz gráfica (GUI)

Utiliza `customtkinter` para una experiencia moderna y amigable:

- `LoginWindow`: Login y registro de usuario.
- `MenuPrincipal`: Opciones para reservar, ver o cancelar.
- `ReservaWindow`: Ingreso de datos para la ficha médica.
- `FichasWindow`: Visualización de fichas y generación de comprobante.
- `CancelarWindow`: Cancelación de fichas por fecha.

---

## 💾 Archivos utilizados

- `usuarios.txt`: contiene usuarios registrados.
- `fichas.txt`: contiene fichas reservadas por todos los usuarios.
- `comprobante_*.txt`: comprobante generado por reserva.

---

## ▶️ Cómo ejecutar el proyecto

```bash
python 3.12
pip install customtkinter
python fuente/MiSaludUmss.py
