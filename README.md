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
| **DLUnire Dark Cyber** | `#010305` | Cyberpunk Neón | Tokens diferenciados para interfaces (`#B983FF`), structs (`#FFD580`), enums (`#33EEFF`), tipos (`#1DE9B6`) y funciones (`#8afdff`). |
| **DLUnire Dark Cyber Soft** | `#04080C` | Cyberpunk Neón | Paleta Cyber adaptada a un fondo azul-pizarra suave y descansado. |

---

## 🖥️ 2. Temas de Interfaz incluidos (`.sublime-theme`)

Incluye **4 temas de interfaz (UI Themes)** para una apariencia visual completamente integrada:

| Tema de Interfaz | Fondo UI | Pestaña Activa | Barra Lateral | Estilo |
|---|---|---|---|---|
| **`DLUnire Dark.sublime-theme`** | `#010305` | `#0A1017` (Texto `#00E8FF`) | `#030508` | Clásico OLED |
| **`DLUnire Dark Soft.sublime-theme`** | `#07090b` | `#0f1418` (Texto `#00D0FF`) | `#070a0d` | Atenuado Grafito |
| **`DLUnire Dark Cyber.sublime-theme`** | `#010305` | `#081018` (Texto `#00FFFF`) | `#030508` | Cyberpunk Neón |
| **`DLUnire Dark Cyber Soft.sublime-theme`** | `#04080C` | `#0D151E` (Texto `#00FFFF`) | `#060A0F` | Cyberpunk Suave |

### Características de la Interfaz:
- **Pestañas:** Pestañas no enfocadas con texto blanco puro (`#FFFFFF`) para máxima legibilidad; pestañas activas con texto cian brillante (`#00E8FF` / `#00FFFF`) en negrita y borde superior de acento.
- **Bordes nítidos:** Borde inferior continuo en la barra de pestañas, borde divisor vertical derecho en el sidebar y bordes en paneles.
- **Menú Contextual:** Fondo `#05080C` con marco `#2A3846`, selección en `#0A1017` y atajos en cian.
- **Barras de Desplazamiento:** Pista en `#030508` con puck redondeado en cian DLUnire (`#00E8FF`) con hover interactivo.
- **Buscador y Reemplazador:** Botones estilizados con borde delimitador y retroalimentación activa en cian.

---

## 📦 Instalación

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

## ⚙️ Activación y Configuración

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

## 🌐 Otros editores

DLUnire Dark también está disponible para:
- **Visual Studio Code / VSCodium / Cursor:** [VS Code Marketplace](https://marketplace.visualstudio.com/) y [Open VSX](https://open-vsx.org/) como `dlunire.dlunire-dark`.
- **Zed:** Registro oficial de extensiones de [Zed](https://zed.dev) como `dlunire-dark`.

---

## 🚀 Sobre DLUnire

DLUnire es un ecosistema PHP modular y orientado a APIs para crear aplicaciones web modernas y de alto rendimiento. Más información en [dlunire.dev](https://dlunire.dev).

---

## 📄 Licencia

MIT — ver [LICENSE](./LICENSE).