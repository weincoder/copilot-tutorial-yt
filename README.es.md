<div align="center">

# 🤖 Tutorial de GitHub Copilot

### Aprende a utilizar Instrucciones Personalizadas con GitHub Copilot

[![GitHub Stars](https://img.shields.io/github/stars/weincoder/copilot-tutorial-yt?style=social)](https://github.com/weincoder/copilot-tutorial-yt/stargazers)
[![Licencia](https://img.shields.io/badge/licencia-MIT-blue.svg)](LICENSE)
[![Documentación](https://img.shields.io/badge/docs-docusaurus-green.svg)](docs/)

[English](README.md) | [Español](#español)

</div>

---

## 📖 Acerca de Este Proyecto

¡Bienvenido al **Tutorial de GitHub Copilot**! Este proyecto demuestra cómo usar efectivamente las **Instrucciones Personalizadas** con GitHub Copilot para mejorar la calidad del código, mantener la consistencia y acelerar los flujos de trabajo de desarrollo.

### ✨ Características

- 📚 **Documentación Completa**: Construida con Docusaurus para una excelente experiencia de lectura
- 🎯 **Instrucciones Personalizadas**: Aprende a crear y usar instrucciones personalizadas para GitHub Copilot
- 🌐 **Soporte Bilingüe**: Documentación completa en inglés y español
- 📝 **Estándares de Código**: Configuración de VSCode preconfigurada con Conventional Commits
- 🚀 **Mejores Prácticas**: Guías para documentación, estilo de código y estructura de proyecto

### 🏗️ Estructura del Proyecto

```
copilot-tutorial-yt/
├── docs/                      # Sitio de documentación Docusaurus
├── .github/
│   └── instructions/          # Instrucciones personalizadas para GitHub Copilot
│       ├── copilot-instructions.md
│       └── documentation-guidelines.md
├── .vscode/                   # Configuración de VSCode
│   ├── settings.json         # Configuración del editor con estándares de commits
│   ├── extensions.json       # Extensiones recomendadas
│   └── launch.json           # Configuraciones de depuración
├── README.md                  # Versión en inglés
└── README.es.md              # Este archivo (Español)
```

### 🚀 Comenzando

#### Prerequisitos

- Node.js (v18 o superior)
- npm o yarn
- VSCode (recomendado)
- Extensión de GitHub Copilot

#### Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/weincoder/copilot-tutorial-yt.git
   cd copilot-tutorial-yt
   ```

2. **Instalar dependencias de documentación**
   ```bash
   cd docs
   npm install
   ```

3. **Iniciar el sitio de documentación**
   ```bash
   npm start
   ```
   
   La documentación se abrirá en `http://localhost:3000`

### 📚 Documentación

Visita nuestro [sitio de documentación](docs/) para aprender:

- Cómo configurar las Instrucciones Personalizadas de GitHub Copilot
- Mejores prácticas para desarrollo asistido por IA
- Estándares y guías de calidad de código
- Flujos de trabajo de contribución

### 🎯 Instrucciones Personalizadas

Este proyecto incluye instrucciones personalizadas que ayudan a GitHub Copilot a entender:

- **Estándares de Documentación**: Cómo escribir y estructurar documentación
- **Convenciones de Commits**: Siguiendo la especificación de Conventional Commits
- **Estilo de Código**: Mejores prácticas de TypeScript/JavaScript
- **Estructura del Proyecto**: Manteniendo una organización consistente de archivos

### 🛠️ Configuración de VSCode

La carpeta `.vscode` incluye:

- **settings.json**: Configuración de Conventional Commits y preferencias del editor
- **extensions.json**: Extensiones recomendadas para la mejor experiencia
- **launch.json**: Configuraciones de depuración para el sitio de documentación

#### Extensiones Recomendadas

Al abrir el proyecto en VSCode, se te sugerirá instalar las siguientes extensiones:

- **Prettier**: Formateo automático de código
- **ESLint**: Linting de código JavaScript/TypeScript
- **Conventional Commits**: Ayuda para escribir commits siguiendo el estándar
- **GitHub Copilot**: Asistente de IA para programación
- **Markdown All in One**: Herramientas para trabajar con Markdown
- **Code Spell Checker**: Corrector ortográfico para código (inglés y español)

### 🤝 Contribuyendo

¡Damos la bienvenida a las contribuciones! Por favor lee nuestras [guías de documentación](.github/instructions/documentation-guidelines.md) antes de enviar pull requests.

#### Formato de Mensajes de Commit

Usamos [Conventional Commits](https://www.conventionalcommits.org/es/):

```
<tipo>(<alcance>): <asunto>

<cuerpo>

<pie>
```

**Tipos de Commits:**
- `feat`: Nueva funcionalidad
- `fix`: Corrección de errores
- `docs`: Cambios en documentación
- `style`: Cambios de formato de código
- `refactor`: Refactorización de código
- `test`: Agregar o actualizar tests
- `chore`: Tareas de mantenimiento

**Ejemplos:**
```
feat(docs): agregar tutorial para instrucciones personalizadas

Se implementó un tutorial completo que explica cómo configurar
y usar instrucciones personalizadas con GitHub Copilot.

Closes #123
```

```
fix(config): corregir ruta de configuración de VSCode

La ruta relativa en launch.json no funcionaba correctamente.
Se actualizó para usar la ruta absoluta correcta.
```

```
docs(readme): actualizar instrucciones de instalación

Se agregaron detalles sobre prerequisitos y pasos adicionales
para usuarios de macOS.
```

### 📖 Recursos de Aprendizaje

Este proyecto es parte de una serie de tutoriales sobre GitHub Copilot. Aquí encontrarás:

1. **Configuración Inicial**: Cómo configurar tu entorno de desarrollo
2. **Instrucciones Personalizadas**: Crear y usar custom instructions
3. **Mejores Prácticas**: Consejos para aprovechar al máximo GitHub Copilot
4. **Casos de Uso**: Ejemplos reales de uso efectivo
5. **Trucos y Tips**: Técnicas avanzadas para usuarios experimentados

### 🎥 Video Tutoriales

Visita el canal de YouTube de WeinCoder para ver los tutoriales en video:
- Introducción a GitHub Copilot
- Configuración de Custom Instructions
- Workflow de desarrollo con Copilot
- Y mucho más...

### 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

### 👨‍💻 Autor

**WeinCoder**

- YouTube: [@weincoder](https://youtube.com/@weincoder)
- GitHub: [@weincoder](https://github.com/weincoder)
- Twitter: [@weincoder](https://twitter.com/weincoder)

### 🌟 Muestra Tu Apoyo

Si encuentras útil este proyecto, ¡ayúdanos a crecer!

- ⭐ Dale una estrella al repositorio
- 🔔 Suscríbete al canal de YouTube
- 📢 Comparte con otros desarrolladores
- 💬 Deja tus comentarios y sugerencias

### 📞 Conecta y Aprende

¿Tienes preguntas o sugerencias? ¡Nos encantaría saber de ti!

- 🐛 Reporta bugs: [Issues](https://github.com/weincoder/copilot-tutorial-yt/issues)
- 💡 Propón ideas: [Discussions](https://github.com/weincoder/copilot-tutorial-yt/discussions)
- 📺 Ve tutoriales: [YouTube](https://youtube.com/@weincoder)
- 💬 Únete a la comunidad: [Discord](#) (próximamente)

### 🙏 Agradecimientos

Gracias a todos los que han contribuido y apoyado este proyecto:

- A la comunidad de GitHub Copilot
- A los colaboradores del proyecto
- A los seguidores del canal de YouTube
- A todos los que comparten y difunden el contenido

### 📊 Estado del Proyecto

Este proyecto está en desarrollo activo. Estamos constantemente agregando:

- ✅ Nuevos tutoriales y guías
- ✅ Ejemplos de código
- ✅ Mejoras en la documentación
- ✅ Soporte para más idiomas
- 🔄 Integraciones con otras herramientas
- 🔄 Contenido de video adicional

### 🗺️ Roadmap

**Fase 1: Fundamentos** ✅
- [x] Estructura inicial del proyecto
- [x] Documentación básica
- [x] Configuración de VSCode
- [x] Instrucciones personalizadas

**Fase 2: Contenido** 🔄
- [ ] Tutoriales detallados
- [ ] Videos complementarios
- [ ] Ejemplos prácticos
- [ ] Casos de uso reales

**Fase 3: Comunidad** 📅
- [ ] Discord server
- [ ] Contribuciones de la comunidad
- [ ] Workshops en vivo
- [ ] Recursos adicionales

---

<div align="center">

Hecho con ❤️ por WeinCoder | Construido con GitHub Copilot

**[⬆ Volver arriba](#-tutorial-de-github-copilot)**

</div>
