# Creación de un Repositorio Local con Git

Un repositorio local es un proyecto controlado por Git dentro de mi computadora. Permite registrar cambios y mantener historial de versiones.

## Pasos para crear un repositorio local

### 1. Crear carpeta del proyecto

```bash
mkdir mi-proyecto
cd mi-proyecto
### 2. Inicializar Git
git init


Este comando crea la carpeta oculta .git que contiene toda la información de control de versiones.

3. Crear archivos del proyecto
touch README.md

4. Ver estado del repositorio
git status


Muestra archivos nuevos o modificados.

5. Agregar archivos al área de preparación
git add .

6. Crear commit
git commit -m "Commit inicial"
