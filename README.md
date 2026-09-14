# Cockforces

Bóveda de Obsidian para apuntes universitarios y programación competitiva.

## Estructura

- `.obsidian/`: configuración compartida de la bóveda raíz.
- `CockForces/University/`: apuntes y material de la universidad por semestre.
- `CockForces/CockForces/`: notas de programación competitiva, CSES, USACO y concursos.
- `CockForces/Images/`: adjuntos usados por las notas de programación.
- `Excalidraw/`: dibujos exportados de Excalidraw.
- Archivos de imagen en la raíz: adjuntos históricos referenciados por notas existentes.

## Uso

Abre esta carpeta completa como bóveda en Obsidian. No abras `CockForces/` como
una bóveda separada: conserva una configuración antigua y las rutas actuales de
las notas dependen de la bóveda raíz.

Los estados locales de Obsidian, como `workspace.json`, quedan fuera de Git.
La configuración compartible, temas, plugins y contenido de la bóveda sí se
mantienen versionados cuando no son archivos locales.

## Flujo de Git

```text
git status
git add .
git commit -m "Describe el cambio"
git log --oneline
```

Antes del primer commit, revisa `git status --short` para confirmar que solo se
incluye contenido que quieras versionar.
