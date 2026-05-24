# Arquitectura Modular con SASS y Metodología BEM

# 📝Descripción
Este proyecto consiste en el desarrollo y despliegue de una píldora formativa diseñada para exponer el potencial de SASS (Syntactically Awesome Style Sheets) en el ecosistema Frontend moderno. A través de un enfoque práctico y minimalista, se demuestra cómo un preprocesador puede transformar el flujo de diseño web tradicional —muchas veces propenso al desorden y a la redundancia— en un sistema de código escalable, mantenible y altamente eficiente.

El núcleo práctico del proyecto se centra en la refactorización y estilado en vivo (Live Coding) de una tarjeta de producto corporativa (Product Card), aislando por completo los estilos de los componentes e integrando un control de versiones basado en ramas funcionales de Git.

# 🔍Análisis
## El Problema del CSS Tradicional
A medida que las aplicaciones web crecen, el CSS plano (Vanilla CSS) tiende a sufrir del síndrome de código espagueti. Los selectores se vuelven excesivamente largos, los colores y espaciados se duplican cientos de veces, y la falta de un sistema de modularización nativo obliga a los desarrolladores a lidiar con colisiones de estilos y problemas críticos de especificidad.

## La Solución Mediante SASS y BEM
Para mitigar este problema, el proyecto analiza y aplica de forma conjunta dos herramientas de la industria:

- `SASS (Sintaxis SCSS)`: Aporta capacidades lógicas al diseño web mediante el uso de Design Tokens (variables globales), modularización real mediante archivos parciales (_variables.scss, _card.scss) y Nesting (anidamiento), lo que permite estructurar las reglas de CSS de la misma forma en que se organiza el árbol de nodos HTML.

- `Metodología BEM (Block, Element, Modifier)`: Una convención de nomenclatura estándar que encapsula los estilos. Al nombrar las clases como .c-card (Bloque), .c-card__title (Elemento) y .c-card__button--accent (Modificador), se garantiza que la especificidad se mantenga en el nivel más bajo posible y que los componentes sean 100% reutilizables e independientes del contexto.

# 🛠️Planificación

El desarrollo del proyecto se dividió en dos fases:

## Fase 1: Preparación del Entorno (En Casa)
- `Inicialización`: Creación del proyecto base con Vite y estructuración del repositorio Git (main y dev).

- `Maquetación Semántica`: Redacción del archivo index.html estructurado por completo bajo la metodología BEM.

- `Arquitectura SASS Base`: Creación del archivo centralizador style.scss y del módulo _variables.scss con todos los colores y tipografías corporativas ya establecidos. El archivo de estilos del componente (_card.scss) se deja completamente en blanco a propósito para trabajarlo en directo.

## Fase 2: Demostración Práctica (En Vivo / Live Coding)
- `Desarrollo en Vivo`: Programación desde cero de la lógica de estilos en _card.scss, explicando en tiempo real el uso del anidamiento, el selector de referencia & y la inyección de variables.

# 💻Tecnologías Utilizadas

- `SASS`: Como preprocesador principal para añadir modularidad, anidamiento y lógica de variables al diseño de la interfaz.

- `Vite`: Herramienta de construcción (build tool) de última generación que proporciona un servidor de desarrollo ultrarrápido y realiza la compilación automática de SASS a CSS en tiempo real mediante Hot Module Replacement (HMR).

- `HTML5`: Para la estructuración semántica y accesible de la tarjeta de producto.

- `Git & GitHub`: Como sistemas de control de versiones y almacenamiento del repositorio, aplicando un flujo de trabajo basado en Feature Branches.

# 🛠️ Recursos adicionales

- [Documentación oficial de SASS](https://sass-lang.com/documentation/)
- [Arquitectura del patrón 7-1](https://sass-guidelin.es/#the-7-1-pattern)

# 📅Planificación de Commits
- `"chore`: initial documentation setup and gitignore configuration
- `chore`: initialize vite vanilla environment with sass compiler
- 