# crypto-asset-manager

## 🇺🇸 English (default)

A Python-based console application for managing a digital asset catalog and a separate investment portfolio. The project demonstrates how a small business domain can be modeled with clear validation rules, modular logic, and a progressive refactor strategy.

### Overview

crypto-asset-manager helps maintain a reliable reference universe of financial assets while tracking portfolio holdings independently. The system separates two core concepts:

- Catalog: the available asset universe.
- Portfolio: the assets currently held and their treasury units.

This separation creates a clearer business model and a more consistent state-management flow for CRUD operations, reports, and validation.

### Problem Solved

The application addresses a common operational challenge in asset management tools: keeping reference data and portfolio data aligned without allowing invalid state transitions. In practice, that means:

- an asset cannot be registered in the portfolio unless it already exists in the catalog;
- catalog updates can propagate to related portfolio records;
- purchase and sale operations are validated against the real available balance;
- user input is checked continuously to avoid broken flows and inconsistent data.

### Features

- Independent management of catalog and portfolio records.
- Add, remove, and update assets in both data domains.
- Business-rule validation for duplicates, balances, and valid state changes.
- General reporting and average-volume analysis.
- Color-coded console feedback for clearer interaction.

### Technical Highlights

- Modular structure with a clear separation between UI flow, business logic, and validation.
- Progressive refactoring from a simple CRUD-style implementation toward a more domain-aware design.
- Reusable search helpers and defensive validation routines.
- Standard-library-only implementation, with no external dependencies.

### Project Structure

- `main.py` — application entry point.
- `funciones.py` — core logic for interaction, validation, search, and menu orchestration.
- `tablas.py` / `tabla_original.py` — seed data used to initialize the system state.

### Evolution: Phase I to Phase II

The repository contains two implementation phases that show a progressive improvement in software quality.

- Phase I introduced a functional console application with basic CRUD behavior and simple validation.
- Phase II added a catalog/portfolio separation, stronger business rules, safer state transitions, and a cleaner modular design.

### Requirements

- Python 3.x
- No external dependencies

### Run the Project

From the corresponding phase folder, run:

```bash
python main.py
```

### Academic Context

This project was originally developed as an academic programming assignment. It is presented here as a portfolio-ready Python software project, highlighting the engineering decisions, architecture, and validation logic applied during its development.

---

<details>
<summary>🇪🇸 Leer en español</summary>

# crypto-asset-manager

## 🇪🇸 Versión en español

Una aplicación de consola desarrollada en Python para gestionar un catálogo de activos digitales y una cartera de inversión independiente. El proyecto demuestra cómo modelar un dominio de negocio con validaciones sólidas, lógica modular y una evolución progresiva hacia una solución más robusta y mantenible.

### Visión general

crypto-asset-manager ayuda a mantener un universo de referencia de activos financieros mientras se sigue el estado real de la cartera de forma independiente. El sistema separa dos conceptos centrales:

- Catálogo: el universo de activos disponibles.
- Cartera: los activos en posesión y sus unidades en tesorería.

Esta separación genera un modelo de negocio más claro y un flujo de gestión de estado más consistente para operaciones CRUD, reportes y validaciones.

### Problema que resuelve

La aplicación aborda un desafío frecuente en herramientas de gestión de activos: mantener sincronizados los datos de referencia con la cartera sin permitir transiciones inválidas entre ambos estados. En la práctica, eso implica que:

- un activo no puede registrarse en cartera si no existe previamente en el catálogo;
- los cambios del catálogo pueden propagarse a los registros relacionados de la cartera;
- las operaciones de compra y venta se validan contra el saldo real disponible;
- la entrada del usuario se verifica continuamente para evitar flujos rotos y datos inconsistentes.

### Funcionalidades

- Administración independiente de registros de catálogo y cartera.
- Alta, baja y actualización de activos en ambos dominios.
- Validación de reglas de negocio para duplicados, balances y cambios válidos de estado.
- Reportes generales y análisis de volumen superior al promedio.
- Mensajes por consola con color para una interacción más clara.

### Aspectos técnicos

- Estructura modular con separación clara entre flujo de interfaz, lógica de negocio y validaciones.
- Refactor progresivo desde una implementación simple tipo CRUD hacia un diseño más orientado al dominio.
- Helpers reutilizables para búsqueda y validación defensiva.
- Implementación basada solo en la biblioteca estándar de Python, sin dependencias externas.

### Estructura del proyecto

- `main.py` — punto de entrada de la aplicación.
- `funciones.py` — lógica principal para interacción, validación, búsquedas y menús.
- `tablas.py` / `tabla_original.py` — datos semilla para inicializar el estado del sistema.

### Evolución: Fase I a Fase II

El repositorio contiene dos fases de implementación que muestran una mejora progresiva en la calidad del software.

- La Fase I introdujo una aplicación funcional de consola con operaciones CRUD básicas y validación simple.
- La Fase II incorporó separación entre catálogo y cartera, reglas de negocio más fuertes, transiciones de estado más seguras y un diseño modular más limpio.

### Requisitos

- Python 3.x
- Sin dependencias externas

### Ejecución

Desde la carpeta de la fase correspondiente, ejecuta:

```bash
python main.py
```

### Contexto académico

Este proyecto fue desarrollado originalmente como trabajo práctico de programación en un contexto académico. Se presenta aquí como un proyecto Python listo para portfolio, destacando las decisiones de ingeniería, la arquitectura y la lógica de validación aplicada durante su desarrollo.

</details>