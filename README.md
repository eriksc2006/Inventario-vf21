# 📦 Inventario VF21

Sistema de inventario en Excel con macros VBA para gestión de consumibles, herramientas eléctricas y compradores desde múltiples sedes.

---

## 🗂️ Estructura del archivo

El archivo `Inventario-VF21.xltm` contiene las siguientes hojas:

| Hoja | Descripción |
|------|-------------|
| `Sede_principal` | Hoja principal con tablas de consumibles, herramientas y compradores |
| `Movimientos` | Registro automático de todos los movimientos realizados |
| `poblado` | Inventario de la sede Poblado |
| `Medellin` | Inventario de la sede Medellín |

---

## 🔘 Botones disponibles

### Consumibles
- **Realizar un movimiento de los consumibles** → `Functions.openSystem`
- **Insertar un nuevo consumible** → `openinserCon`

### Herramientas Eléctricas
- **Realizar un movimiento de las herramientas** → `Function_Her.openSystem`
- **Insertar una nueva herramienta** → `openinserHer`

### General
- **Crear nueva sede** → `openformnewsheet`
- **Realizar un movimiento entre sedes** → `openmovsed`

### Compradores
- **Insertar un nuevo comprador** → `openinserCom` *(pendiente de implementar en VBA)*

---

## ⚙️ Requisitos

- Microsoft Excel con soporte para macros (`.xltm` / `.xlsm`)
- Habilitar macros al abrir el archivo

---

## 🚀 Cómo usar

1. Descarga el archivo `Inventario-VF21.xltm`
2. Ábrelo en Excel y **habilita las macros** cuando se solicite
3. Trabaja desde la hoja `Sede_principal` usando los botones del panel

---

## ⚠️ Pendiente

- Crear la macro `openinserCom` y el UserForm correspondiente para insertar nuevos compradores (tabla en columna `S` de `Sede_principal`)

---

## 📁 Estructura del repositorio

```
inventario-vf21/
│
├── Inventario-VF21.xltm   # Archivo principal con macros
└── README.md              # Este archivo
```
