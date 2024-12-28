# Cajero.py

# 💻 Proyecto Final - Segundo Semestre

Este proyecto representa un gran paso en mi carrera como **Ingeniero/a en Sistemas**. Fue desarrollado como el proyecto final de mi segundo semestre y simboliza mi avance en la programación, aplicando únicamente los conocimientos adquiridos hasta ese momento.

---

## 📝 Descripción

El programa es un **simulador de cajero automático** llamado "Desfacol". Este permite a los usuarios realizar diversas operaciones bancarias de manera interactiva, como:

- 📥 **Consignar dinero**  
- 💸 **Retirar dinero**  
- 📊 **Consultar saldo**  
- 🚪 **Salir del sistema**

El código es sencillo, pero fue un gran logro personal por ser mi primer proyecto completo.  

---

## 📂 Estructura del Código

El programa está organizado en funciones para facilitar su comprensión y mantenimiento:  

- `inicio()` y `inicio2()`: Administran la interacción inicial del usuario.  
- `menu()`: Presenta las opciones disponibles.  
- `consignar()`, `retirar()`, `consulta()`: Implementan las funcionalidades del cajero automático.  
- `salir()`: Finaliza la ejecución del programa.  
- `ejecutar()`: Controla el flujo según la opción seleccionada por el usuario.  

---

## 🎯 Características

- **Control de autenticación**: Verifica el número de cédula y contraseña para acceder al sistema.  
- **Límites operativos**: Evita que los usuarios excedan los máximos permitidos en consignaciones y retiros.  
- **Bloqueo por intentos fallidos**: Garantiza la seguridad al restringir el acceso tras varios intentos fallidos.  

---

## 🚀 Ejecución

Para ejecutar este programa, sigue estos pasos:  

1. Asegúrate de tener **Python 3.x** instalado en tu equipo.  
2. Descarga el archivo `cajero.py`.  
3. Abre tu terminal o entorno de desarrollo favorito.  
4. Ejecuta el programa con el siguiente comando:  
   ```bash
   python cajero.py
