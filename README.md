# DLUnire Dark — Sublime Text

**Una suite de temas de interfaz y esquemas de color de alto contraste para Sublime Text.**

Official Sublime Text port of the **DLUnire Dark** theme suite from Visual Studio Code and Zed.

![DLUnire Dark](./images/dlunire-dark.webp)

---

## 🎨 1. Esquemas de Color incluidos (`.sublime-color-scheme`)

El paquete incluye **4 esquemas de color** con resaltado semántico consistente:

| Esquema de Color | Fondo | Resaltado Semántico | Descripción |
|---|---|---|---|
| **DLUnire Dark** | `#010305` | Clásico | Contraste puro ultra-oscuro con resaltado semántico estándar. |
| **DLUnire Dark Soft** | `#07090b` | Clásico | Fondo grafito atenuado para reducir la fatiga visual en jornadas largas. |
| **DLUnire Dark Cyber** | `#010305` | Cyberpunk Neón | Tokens diferenciados para clases (`#00FFAA`), interfaces (`#B983FF`), structs (`#FFD580`), enums (`#33EEFF`), tipos (`#1DE9B6`), funciones (`#8AFDFF`) y clases heredadas (`#00F5FF`). |
| **DLUnire Dark Cyber Soft** | `#04080C` | Cyberpunk Neón | Paleta Cyber adaptada a un fondo azul-pizarra suave y descansado. |

---

## 🖥️ 2. Temas de Interfaz incluidos (`.sublime-theme`)

Incluye **4 temas de interfaz (UI Themes)** para una apariencia visual completamente integrada:

| Tema de Interfaz | Fondo UI | Pestaña Activa | Barra Lateral | Barra de Estado | Estilo |
|---|---|---|---|---|---|
| **`DLUnire Dark.sublime-theme`** | `#010305` | `#0A1017` (Texto `#00E8FF`) | `#030508` | `#150030` | Clásico OLED |
| **`DLUnire Dark Soft.sublime-theme`** | `#07090b` | `#0A1017` (Texto `#00b3ff`) | `#070a0d` | `#150030` | Atenuado Grafito |
| **`DLUnire Dark Cyber.sublime-theme`** | `#010305` | `#0A1017` (Texto `#00E8FF`) | `#030508` | `#150030` | Cyberpunk Neón |
| **`DLUnire Dark Cyber Soft.sublime-theme`** | `#04080C` | `#0D151E` (Texto `#00E8FF`) | `#060A0F` | `#150030` | Cyberpunk Suave |

### Características de la Interfaz y Sintaxis:
- **Barra de Estado:** Fondo violeta profundo personalizado (`#150030`) con tipografía en cian suave (`#c8f9ff`) y decoraciones de Git.
- **Botones y Paneles:** Botones estilizados con fondo azul petróleo (`#002030`), texto en blanco nítido (`#FFFFFF`) y hover activo (`#003040`).
- **Guías de Indentación:** Guías de indentación activas e inactivas calibradas en cian (`#00b3ff`) para un seguimiento estructural limpio.
- **Pestañas:** Pestañas no enfocadas con texto blanco puro (`#FFFFFF`) para máxima legibilidad; pestañas activas con texto cian brillante (`#00E8FF` / `#00b3ff`) en negrita y borde superior de acento.
- **Bordes nítidos:** Borde inferior continuo en la barra de pestañas, borde divisor vertical en el sidebar y bordes sutiles en paneles (`#00bbff2d` / `#0099DD2D`).
- **Menú Contextual:** Fondo `#05080C` con marco `#2A3846`, selección en `#0A1017` y atajos en cian.
- **Barras de Desplazamiento:** Pista en `#030508` con puck redondeado en cian DLUnire (`#00bbff80`) con hover interactivo.

---

## 🎯 3. Paleta de Colores

| Elemento | Color | Propósito |
|---|:---:|---|
| **Fondo Ultra-Oscuro** | `#010305` | Fondo de editor OLED / Cyber |
| **Fondo Soft (Grafito)** | `#07090b` | Fondo atenuado para jornadas nocturnas |
| **Fondo Cyber Soft** | `#04080C` | Fondo azul-pizarra equilibrado |
| **Texto por defecto** | `#FFFFFF` | Cadenas de texto y primer plano del editor |
| **Palabras clave** | `#FF6D00` | Control de flujo, modificadores y storage |
| **Clases definidas** | `#00FFAA` | Definiciones de clases y traits (Cyber) / `#00FF00` (Clásico) |
| **Clases heredadas** | `#00F5FF` | Clases extendidas y tipos heredados (Cyber) |
| **Interfaces** | `#B983FF` | Interfaces y contratos de tipos (Cyber) |
| **Structs** | `#FFD580` | Estructuras de datos (Cyber) |
| **Enums** | `#33EEFF` | Enumeraciones (Cyber) |
| **Namespaces** | `#00E5D8` | Declaraciones de espacios de nombres (Cyber) |
| **Funciones y Métodos** | `#8AFDFF` | Declaraciones y llamadas a funciones (Cyber) / `#A0E5FF` (Clásico) |
| **Variables** | `#00E8FF` | Variables y objetos |
| **Parámetros** | `#70F3FF` | Parámetros de función (Cyber) |
| **Propiedades** | `#FF9100` | Propiedades de objetos y claves JSON/YAML |
| **Atributos / Decoradores**| `#F50057` | Atributos y anotaciones del lenguaje |
| **Tipos primitivos** | `#1DE9B6` | Tipos nativos (Cyber) / `#FFC600` (Clásico) |
| **Etiquetas HTML/XML** | `#1DE9B6` | Elementos y tags HTML/XML |
| **Operadores** | `#5C7A88` | Operadores y flechas de función (Cyber) |
| **Constantes / Booleans** | `#A0A0FF` | Constantes del lenguaje y miembros enum |
| **Números** | `#FAA859` | Literales numéricos |
| **Comentarios** | `#656565` | Comentarios sin cursiva |
| **Barra de Estado** | `#150030` | Fondo personalizado de barra de estado |
| **Guías de Indentación** | `#00b3ff` | Guías de indentación estructurales |

---

## 📦 4. Instalación

### Método 1: A través de Package Control (Recomendado)

1. Abre la paleta de comandos en Sublime Text (`Ctrl+Shift+P` en Linux/Windows o `Cmd+Shift+P` en macOS).
2. Escribe `Package Control: Install Package` y presiona Enter.
3. Busca **`Theme - DLUnire Dark`** (o `DLUnire Dark`) y presiona Enter.

### Método 2: Instalación manual (Git)

Clona este repositorio directamente en tu carpeta de paquetes de Sublime Text:

**Linux:**
```bash
git clone https://github.com/dlunire/dlunire-dark-sublime.git ~/.config/sublime-text/Packages/"Theme - DLUnire Dark"
```

**macOS:**
```bash
git clone https://github.com/dlunire/dlunire-dark-sublime.git ~/Library/Application\ Support/Sublime\ Text/Packages/"Theme - DLUnire Dark"
```

**Windows:**
```bash
git clone https://github.com/dlunire/dlunire-dark-sublime.git "%APPDATA%\Sublime Text\Packages\Theme - DLUnire Dark"
```

---

## ⚙️ 5. Activación y Configuración

Abre tus preferencias de usuario en Sublime Text (**Preferences > Settings**) y añade:

```json
{
    "theme": "DLUnire Dark.sublime-theme",
    "color_scheme": "DLUnire Dark.sublime-color-scheme",
    "font_face": "Cascadia Code",
    "font_size": 11,
    "line_padding_top": 2,
    "line_padding_bottom": 2,
    "highlight_line": true
}
```

### Cambiar entre variantes

Puedes alternar entre cualquiera de los 4 temas y 4 esquemas de color desde el menú superior:
- **Tema de Interfaz:** `Preferences > Theme > DLUnire Dark > [DLUnire Dark / Soft / Cyber / Cyber Soft]`
- **Esquema de Sintaxis:** `Preferences > Color Scheme > DLUnire Dark > [DLUnire Dark / Soft / Cyber / Cyber Soft]`

---

## 🌐 6. Otros editores

DLUnire Dark también está disponible para:
- **Visual Studio Code / VSCodium / Cursor:** [VS Code Marketplace](https://marketplace.visualstudio.com/) y [Open VSX](https://open-vsx.org/) como `dlunire.dlunire-dark`.
- **Zed:** Registro oficial de extensiones de [Zed](https://zed.dev) como `dlunire-dark`.

---

## 🚀 7. Sobre DLUnire

DLUnire es un ecosistema PHP modular y orientado a APIs para crear aplicaciones web modernas y de alto rendimiento. Más información en [dlunire.dev](https://dlunire.dev).

---

## 📄 Licencia

MIT — ver [LICENSE](./LICENSE).