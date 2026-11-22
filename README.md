# Presentación Software (Etapa 2) — HTML y CSS Flexbox Externo

Etapa final de una demostración académica en tres fases sobre buenas prácticas de maquetación web para **Ingeniería en Telecomunicaciones (Team 7)**. A diferencia de la versión anterior con estilos internos, esta etapa aplica la **separación de responsabilidades** extrayendo todas las reglas visuales a una hoja de estilos externa (`styles.css`).

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Hoja%20Externa%20%2B%20Flexbox-1572B6?style=flat-square&logo=css3&logoColor=white)
![Etapa](https://img.shields.io/badge/Serie-Etapa%202%20de%203-059669?style=flat-square)
![GitHub Pages](https://img.shields.io/badge/Demo-GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

- **Demo en vivo:** [juancan00.github.io/PresentacionSoftware2](https://juancan00.github.io/PresentacionSoftware2/)

---

## Serie progresiva del proyecto

| Etapa | Repositorio | Enfoque demostrado | Demo |
| :---: | :--- | :--- | :---: |
| **0** | [PresentacionSoftware0](https://github.com/JuanCan00/PresentacionSoftware0) | Estructura HTML pura (bloque `<style>` vacío) | [Ver demo](https://juancan00.github.io/PresentacionSoftware0/) |
| **1** | [PresentacionSoftware](https://github.com/JuanCan00/PresentacionSoftware) | CSS embebido en `<style>` con diseño oscuro y Flexbox | [Ver demo](https://juancan00.github.io/PresentacionSoftware/) |
| **2 (actual)** | **`PresentacionSoftware2`** | Separación de responsabilidades: `index.html` + `styles.css` externo | [Ver demo](https://juancan00.github.io/PresentacionSoftware2/) |

---

## Conceptos aplicados

- Enlace de hoja de estilos externa mediante `<link rel="stylesheet" href="styles.css">`, facilitando el mantenimiento y la reutilización de estilos.
- Maquetación responsiva con **CSS Flexbox** (`display: flex`, `justify-content: center`, `flex-wrap: wrap`, `gap: 24px`).
- Tarjetas interactivas de las tres áreas principales: **Networks**, **Wireless Communication** y **Signal Processing**.

---

## Estructura del proyecto

```text
PresentacionSoftware2/
├── index.html          # Estructura semántica HTML5
├── styles.css          # Hoja de estilos externa (tema oscuro, Flexbox y hover)
└── README.md
```

---

## Cómo visualizar

Abre `index.html` en cualquier navegador web (manteniendo `styles.css` en el mismo directorio) o accede al enlace de GitHub Pages indicado arriba.

---

## Autor

**Juan Pablo Cano** · [@JuanCan00](https://github.com/JuanCan00)  
Ingeniería en Telecomunicaciones — Universidad Militar Nueva Granada
