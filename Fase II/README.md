# crypto-asset-manager — Fase II

## 🇪🇸 Versión española

La segunda iteración del proyecto refuerza la solución inicial con una separación clara entre catálogo y cartera, mejor validación de reglas de negocio y una navegación más robusta. Esta fase representa la evolución del sistema hacia una estructura más consistente para la gestión y análisis de activos.

### Qué mejora esta fase

La aplicación ya no trata todo como una misma entidad. En esta versión, el usuario puede gestionar un universo de referencia de activos y, por separado, controlar la cartera en posesión. Esto permite modelar mejor el flujo de negocio y reducir inconsistencias entre las dos capas del sistema.

### Funcionalidades principales

- Separación entre catálogo y cartera.
- Registro, eliminación y modificación independientes por módulo.
- Validación de compra/venta y control de unidades disponibles.
- Propagación de cambios del catálogo hacia la cartera.
- Informes de volumen superior al promedio.
- Menús dedicados por responsabilidad.

### Estructura del proyecto

- `main.py` — punto de entrada de la aplicación.
- `funciones.py` — lógica de navegación, validación, búsqueda, reportes y menús.
- `tablas.py` — datos precargados para catálogo y cartera.

### Requisitos

- Python 3.x
- Sin dependencias externas

### Ejecución

Desde la carpeta correspondiente:

```bash
python main.py
```

### Contexto académico

La Fase II fue desarrollada en el mismo marco académico, pero incorpora una reingeniería funcional y una mejora en la organización del código. Se presenta como una versión más madura del sistema con mayor claridad en el diseño de la lógica de negocio.

---

<details>
<summary>🇬🇧 Read in English</summary>

# crypto-asset-manager — Phase II

## 🇬🇧 English version

The second iteration of the project strengthens the initial solution with a clear separation between catalog and portfolio, deeper business-rule validation, and a more robust navigation model. This phase represents the system’s evolution toward a more consistent structure for asset management and analysis.

### What improves in this phase

The application no longer treats all data as a single entity. In this version, the user can manage a reference universe of assets and, separately, control the holdings in a portfolio. This provides a better model for the business flow and helps reduce inconsistencies between the two layers of the system.

### Main features

- Separation between catalog and portfolio.
- Independent add, remove, and update flows per module.
- Validation of buy/sell operations and treasury-balance control.
- Propagation of catalog updates into the portfolio.
- Average-volume reporting.
- Dedicated navigation menus by responsibility.

### Project structure

- `main.py` — application entry point.
- `funciones.py` — navigation, validation, search, reporting, and menu logic.
- `tablas.py` — preloaded dataset for both catalog and portfolio.

### Requirements

- Python 3.x
- No external dependencies

### Run the project

From the corresponding folder, execute:

```bash
python main.py
```

### Academic context

Phase II was developed in the same academic context, but it incorporates functional reengineering and a stronger code organization. It is presented here as a more mature version of the system, with clearer business-logic design and improved software structure.

</details>
