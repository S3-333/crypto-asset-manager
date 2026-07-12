# crypto-asset-manager — Fase I

## 🇪🇸 Versión española

La primera iteración del proyecto implementa un gestor de activos digitales con operaciones básicas de alta, baja, modificación e informes. Esta fase define la base funcional del sistema, con validaciones simples y una estructura de consola orientada a la interacción directa del usuario.

### Qué resuelve esta fase

El sistema permite registrar activos, mantener una lista de referencia y visualizar un informe ordenado por nivel de confianza. La lógica está diseñada para ser clara y fácil de seguir, con una separación inicial entre la interacción del usuario y la lógica interna del programa.

### Funcionalidades principales

- Alta de activos con validación de campos.
- Baja por identificador con control de unidades en tesorería.
- Modificación de propiedades registradas.
- Informe general ordenado por puntaje de confianza.
- Validación de entradas para evitar estados inconsistentes.

### Estructura del proyecto

- `main.py` — punto de entrada del programa.
- `funciones.py` — lógica del sistema, dividida en front, back, validaciones y menú.
- `tabla_original.py` — datos semilla para iniciar el sistema.

### Requisitos

- Python 3.x
- Sin dependencias externas

### Ejecución

Desde la carpeta correspondiente:

```bash
python main.py
```

### Contexto académico

Esta fase fue desarrollada en un contexto académico como una primera entrega funcional del proyecto. El README se presenta aquí como una referencia técnica de la arquitectura inicial y la evolución del diseño.

---

<details>
<summary>🇬🇧 Read in English</summary>

# crypto-asset-manager — Phase I

## 🇬🇧 English version

The first iteration of the project implements a digital asset manager with basic create, delete, update, and reporting operations. This phase defines the core functionality of the system, with simple validation rules and a console-driven structure focused on direct user interaction.

### What this phase solves

The system allows users to register assets, maintain a reference list, and generate a report ordered by confidence score. The logic is intentionally straightforward and easy to follow, with an early separation between user interaction and the internal program logic.

### Main features

- Asset creation with field validation.
- Deletion by identifier with treasury-balance constraints.
- Modification of stored properties.
- General report sorted by confidence score.
- Input validation to prevent inconsistent states.

### Project structure

- `main.py` — application entry point.
- `funciones.py` — core logic, divided into front-end, back-end, validation, and menu sections.
- `tabla_original.py` — seed data used to initialize the system.

### Requirements

- Python 3.x
- No external dependencies

### Run the project

From the relevant folder, execute:

```bash
python main.py
```

### Academic context

This phase was developed in an academic setting as the first functional delivery of the project. The README is presented here as a technical reference for the initial architecture and design progression.

</details>

