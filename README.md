# formacion-esoliupo

Un repositorio de prueba para enseñar el uso de Git y GitHub en la formación de ESOLIUPO.

Formación impartida por Alejandro Martín.

## La presentación

La presentación está en [`presentacion/index.html`](presentacion/index.html). Ábrela en el navegador y muévete con las flechas del teclado (con `Ctrl + P` se exporta a PDF).

Si GitHub Pages está activado (*Settings → Pages → Source: GitHub Actions*), se publica sola en cada push a `main` gracias a [`.github/workflows/pages.yml`](.github/workflows/pages.yml).

| Módulo | Tema |
| ------ | ---- |
| 00 | Comandos básicos de terminal |
| 01 | Qué es Git y sus 4 zonas |
| 02 | Configuración, staging y commits |
| 03 | Ver y deshacer cambios (`diff`, `restore`, `revert`, `reset`, `reflog`) |
| 04 | `.gitignore` |
| 05 | Ramas, merge y conflictos |
| 06 | `stash`, `tag`, `rebase` y `cherry-pick` |
| 07 | GitHub, README y licencias |
| 08 | Remotos: `clone`, `push`, `pull`, `fetch` |
| 09 | Issues, Pull Requests y forks |
| 10 | GitHub Actions y GitHub Pages |
| 11 | Interfaces gráficas y buenas prácticas |

## El historial también es material del curso

Cada commit añade un módulo y su mensaje explica lo que se enseña en él. Para leerlo:

```bash
git log --reverse
git log --oneline --graph
```

El PDF original de la formación ya no está en la carpeta, pero sigue en el historial. Recuperarlo es parte del ejercicio final.

## Participantes

Añade tu nombre mediante una Pull Request (ejercicio del módulo 11):

- Alejandro Martín (formador)
