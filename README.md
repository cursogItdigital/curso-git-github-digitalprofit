# Curso Git y GitHub – DigitalProfit

Repositorio de práctica del curso de **Git y GitHub**. Sirve como espacio para aprender y ejercitar el flujo de trabajo colaborativo en equipo: ramas, commits, pull requests y revisión de código.

## Objetivos

- Entender los conceptos básicos de Git (commit, branch, merge, remote).
- Practicar el trabajo colaborativo en GitHub.
- Aplicar un flujo basado en ramas y Pull Requests.

## Estructura de ramas

| Rama      | Propósito                                              |
|-----------|--------------------------------------------------------|
| `main`    | Código estable. Solo se modifica mediante Pull Request. |
| `develop` | Integración del trabajo en curso. Solo vía Pull Request.|
| `feature/*` | Ramas de trabajo individuales para cada tarea.       |

## Cómo clonar el repositorio

```bash
git clone https://github.com/cursogItdigital/curso-git-github-digitalprofit.git
cd curso-git-github-digitalprofit
```

## Flujo de trabajo para colaboradores

1. Actualizar la rama base:
   ```bash
   git checkout develop
   git pull origin develop
   ```
2. Crear una rama para tu tarea:
   ```bash
   git checkout -b feature/nombre-de-la-tarea
   ```
3. Hacer cambios y confirmarlos:
   ```bash
   git add .
   git commit -m "Descripción clara del cambio"
   ```
4. Subir la rama:
   ```bash
   git push -u origin feature/nombre-de-la-tarea
   ```
5. Abrir un **Pull Request** en GitHub hacia `develop` y esperar la revisión y aprobación.

> No se permite hacer push directo a `main` ni a `develop`.

## Colaboradores

- [@programadordigit1](https://github.com/programadordigit1)
- [@programadordigit2](https://github.com/programadordigit2)

## Organización

Mantenido por [cursogItdigital](https://github.com/cursogItdigital).
