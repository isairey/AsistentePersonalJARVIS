<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/4712/4712109.png" />

# 🤖 Jarvis

### Asistente Personal Multiplataforma para Linux, macOS y Windows 🚀

<p align="center">
  <b>Jarvis</b> es un asistente personal de línea de comandos que ayuda a los usuarios a realizar tareas cotidianas como consultar el clima, gestionar archivos, obtener información del sistema, jugar, traducir textos y mucho más.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Jarvis-Personal_Assistant-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-Automation-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-Compatible-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Open_Source-MIT-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-funcionalidades">Funciones</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-plugins">Plugins</a>
</p>

</div>

---

![Jarvis](http://i.imgur.com/xZ8x9ES.jpg)

---

# 🌌 Acerca del proyecto

**Jarvis** es un asistente personal basado en terminal diseñado para simplificar tareas diarias mediante comandos sencillos.

Permite realizar acciones como:

* 🌤️ Consultar el clima
* 🎮 Jugar desde la terminal
* 📂 Gestionar archivos
* 🖼️ Procesar imágenes
* 📄 Convertir documentos
* 📈 Consultar criptomonedas y acciones
* 🌍 Traducir idiomas
* 💻 Obtener información del sistema
* 🤖 Automatizar tareas

---

# ✨ Funcionalidades

## 🎯 Entretenimiento

* Actividades para combatir el aburrimiento
* Recomendaciones de películas
* Recomendaciones musicales
* Ideas para dibujar
* Descubrimiento de contenido

---

## ⚽ Deportes

* Resultados deportivos
* Clasificaciones
* Información de equipos
* Estadísticas de jugadores

---

## 🎮 Juegos Integrados

* Blackjack
* Hangman
* Tic Tac Toe
* Connect Four
* Rock Paper Scissors
* Wordle
* Roulette

---

## 🏋️ Salud y Fitness

* Cálculo de IMC
* Cálculo metabólico
* Seguimiento de calorías
* Rutinas de ejercicio
* Información nutricional

---

## 🍹 Recetas

* Cócteles
* Bebidas
* Recetas rápidas
* Información nutricional

---

## 🎲 Generadores Aleatorios

* Contraseñas seguras
* Números aleatorios
* Listas aleatorias

---

## 📏 Conversión de Unidades

* Temperatura
* Longitud
* Masa
* Tiempo
* Velocidad
* Monedas
* Binario y hexadecimal

---

## 📸 Multimedia

* Captura de pantalla
* Uso de cámara
* Conversión de imágenes
* Compresión de imágenes

---

## 📄 Herramientas PDF

* Imagen a PDF
* PDF a imágenes
* Página web a PDF

---

## 😂 Humor y Curiosidades

* Chistes diarios
* Datos curiosos
* Cat Facts
* Dad Jokes

---

## 🧮 Matemáticas

* Calculadora
* Resolución de ecuaciones
* Álgebra
* Matrices
* Factorización

---

## 🌍 Traducción

* Traducción entre idiomas
* Conversión de texto

---

## ☀️ Clima

* Pronósticos meteorológicos
* Estado actual del clima
* Información local

---

## 📈 Finanzas

* Seguimiento de acciones
* Información de criptomonedas
* Mercado financiero

---

# 👨‍💻 Arquitectura

## 🖥️ Núcleo del asistente

Sistema basado en plugins que permite extender fácilmente sus funcionalidades.

### Características

* Modular
* Extensible
* Multiplataforma
* Ligero

---

## 🔌 Sistema de Plugins

Permite agregar nuevos comandos fácilmente.

### Funcionalidades

* Plugins personalizados
* Comandos dinámicos
* Integración sencilla
* Desarrollo modular

---

# 🛠️ Tecnologías utilizadas

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=python" />
</p>

* Python
* CLI Applications
* Automatización
* APIs externas

---

## 🖥️ Sistemas Operativos

<p>
  <img src="https://skillicons.dev/icons?i=linux,apple,windows" />
</p>

* Linux
* macOS
* Windows

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,docker" />
</p>

* Git
* GitHub
* VS Code
* Docker

---

# 📂 Estructura del proyecto

```bash
AsistentePersonalJARVIS/
│
├── custom/
├── plugins/
├── doc/
├── tests/
├── installer
├── jarvis
├── requirements.txt
├── test.sh
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

* Python 3+
* Git
* Pip

---

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/AsistentePersonalJARVIS.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd AsistentePersonalJARVIS
```

---

## 3️⃣ Ejecutar instalador

```bash
python installer
```

o

```bash
python3 installer
```

---

# 🚀 Ejecutar Jarvis

Desde cualquier ubicación:

```bash
jarvis
```

o dentro del proyecto:

```bash
./jarvis
```

---

# 🔌 Plugins

Jarvis permite crear nuevas funcionalidades mediante plugins.

## Ejemplo

Crear:

```bash
custom/hello_world.py
```

Código:

```python
from plugin import plugin

@plugin("helloworld")
def helloworld(jarvis, s):
    jarvis.say(s)
```

Uso:

```bash
helloworld Hola Jarvis
```

Resultado:

```bash
Hola Jarvis
```

---

# 🧪 Testing

Ejecutar pruebas:

```bash
./test.sh
```

---

# 🐳 Docker

Construir imagen:

```bash
make build_docker
```

Ejecutar contenedor:

```bash
make run_docker
```

---

# 📊 Funcionalidades destacadas

## 💻 Información del sistema

* RAM
* Sistema operativo
* Dirección IP
* DNS
* Batería
* Velocidad de red

---

## 📂 Gestión de archivos

* Organización automática
* Gestión de carpetas
* Clasificación de documentos

---

## 📸 Procesamiento multimedia

* Conversión de imágenes
* Capturas de pantalla
* Manipulación básica

---

## 🌐 Utilidades web

* Consulta de clima
* Información financiera
* Traducción
* Búsquedas rápidas

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

* Más plugins
* Mejor integración por voz
* Automatización avanzada
* Compatibilidad con IA moderna
* Mejoras de rendimiento

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes - FullStack Developer

Desarrollador y mantenedor del proyecto Jarvis.

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella
🍴 Haz fork
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto distribuido bajo licencia MIT.

---

<div align="center">

### 🤖 Jarvis — tu asistente personal multiplataforma desde la terminal 🚀

</div>
