# 🎃 Túnel del Terror — Ruleta TRUCO / TRATO (JavaFX)

Mini aplicación creada en **JavaFX + Scene Builder** como práctica evaluable del Módulo 5.  
Simula la entrada a un túnel del terror y una ruleta aleatoria que reparte **TRUCOS** o **TRATOS** con humor y ambientación de Halloween. 👻

---

## 🧩 Funcionalidades principales

### 🕸️ Pantalla 1 — *Entrada al Túnel*
- Recoge **Nombre**, **Apellidos** y **Curso** (DAM1/DAM2/DAW1/DAW2/SMR1/SMR2).  
- Validación: no deja continuar si faltan campos.  
- Diseño Halloween 🎃 con tipografía y fondo personalizados.  
- Botón: **“Entrar si te atreves…”**

### 🧛 Pantalla 2 — *Ruleta TRUCO / TRATO*
- Animación fluida con `RotateTransition`.  
- Botón **GIRAR** que se desactiva durante la animación.  
- Resultado 50/50: **TRUCO** o **TRATO**, con mensajes graciosos.  
- Muestra el **nombre y curso** en la parte superior.  
- Estilo visual coherente: fondo morado, tonos oscuros y estética de terror.

---

## ⚙️ Tecnologías utilizadas
- 🧠 **JavaFX 21**
- 🪄 **Scene Builder**
- ⚙️ **Maven** (gestor de dependencias)
- 🎨 **CSS personalizado** (`halloween.css`)
- 💾 **DTO simple** para el paso de datos (`UserData`)

---

## 🧙‍♀️ Ejecución del proyecto

### 🔧 Requisitos:
- **Java 21 o superior**
- **Maven 3.9+**
- Compatible con IDEs como IntelliJ, Eclipse o NetBeans.

---
🧾 Conclusión

Este proyecto ha sido una forma divertida de practicar JavaFX y Scene Builder, mezclando programación con creatividad.
El resultado es una pequeña app de Halloween con buen diseño, animaciones suaves y un toque de humor 👻.
Además de aprender a validar datos, pasar información entre pantallas y aplicar estilos con CSS, fue una buena forma de hacer algo distinto y entretenido.🎃

### 🚀 Comando para ejecutar:
```bash
mvn clean javafx:run


