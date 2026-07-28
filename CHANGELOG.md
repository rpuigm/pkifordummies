# Changelog

Todos los cambios notables de este proyecto serán documentados en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/),
y este proyecto adhiere a [Semantic Versioning](https://semver.org/lang/es/).

## [0.1.0] - 2026-07-28

### Added
- Estructura inicial del proyecto PKI for Dummies
- Configuración de Maven (pom.xml) con Java 21
- Carpetas del proyecto: `src/`, `docs/`, `.github/workflows/`
- Archivo `.editorconfig` para consistencia de editor (indentación, EOL, charset UTF-8)
- Archivo `.gitattributes` para normalización de líneas de Git
- Instalación de GitHub CLI (Copilot CLI) en devcontainer
- Extensiones VS Code para Java y Git incluidas en devcontainer

### Changed
- Actualización de `.devcontainer/devcontainer.json`:
  - Agregado: Instalación de GitHub CLI
  - Removido: `opencode-ai` (npm install -g opencode-ai)
  - Removido: Node.js y configuración de NodeSource

### Removed
- Dependencia de Node.js del devcontainer (proyecto es Java/Maven)
- Herramienta `opencode-ai`

### Fixed
- Configuración limpia del devcontainer enfocada en herramientas necesarias

## Notas Iniciales
- Proyecto base configurado
- Listo para desarrollo con devcontainer
- Maven configurado como herramienta de build
- Copilot CLI disponible para asistencia en terminal
