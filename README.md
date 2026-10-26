# RushTix

Plataforma de boletos para eventos de último minuto, pensada para la juventud salvadoreña.

> **Precio final desde el primer vistazo.**

Proyecto de la materia **Programación Orientada al Usuario (POU)** — Universidad Centroamericana José Simeón Cañas (UCA), ciclo 02/2026. Este repositorio contiene la **primera parte del sitio web**, codificada a partir del diseño en Figma.

## Páginas

| Archivo | Descripción |
|---|---|
| `index.html` | Página de inicio: listado de eventos con buscador y filtros. |
| `login.html` | Página de inicio de sesión. |

## Estructura

```
rushtix/
├── index.html          # Inicio (eventos)
├── login.html          # Iniciar sesión
└── css/
    ├── inicio.css      # Estilos del inicio
    └── login.css       # Estilos del login
```

## Cómo verlo

- **Rápido:** abrí `index.html` en el navegador.
- **Con servidor local** (para que el CSS cargue por ruta relativa):

```bash
python -m http.server 8765
```

Luego abrí `http://127.0.0.1:8765/index.html`.

## Tecnologías

HTML5 y CSS3 puro, sin frameworks. Tema oscuro. Tipografías: Anton (títulos), IBM Plex Sans (texto), IBM Plex Mono (precios).

## Diseño

Mockups en Figma (abre sin iniciar sesión):
<https://www.figma.com/design/GkhkrZUbTN4slR7PCa7cpj/RushTix-%E2%80%94-Primera-Entrega-POU>

## Equipo

- Xiomara Molina Amaya — `00XXXXXX` (Xio7w7)
- Daniel Eduardo García Hernández — `00253220` (SLK3)
