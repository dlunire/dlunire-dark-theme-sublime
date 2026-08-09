# DLUnire Dark — Sublime Text

**Una suite de temas y esquemas de color de alto contraste para Sublime Text.**

Official Sublime Text port of the **DLUnire Dark** theme from Visual Studio Code and Zed.

![DLUnire Dark](./images/dlunire-dark.webp)

---

## Variantes de esquemas de color incluidas

El paquete incluye **4 esquemas de color** (`.sublime-color-scheme`) para adaptarse a tu flujo de trabajo:

| Esquema de Color | Fondo | Resaltado Semántico | Descripción |
|---|---|---|---|
| **DLUnire Dark** | `#010305` | Clásico | Contraste puro ultra-oscuro con resaltado semántico estándar. |
| **DLUnire Dark Soft** | `#07090b` | Clásico | Fondo grafito atenuado para reducir la fatiga visual en jornadas largas. |
| **DLUnire Dark Cyber** | `#010305` | Cyberpunk Neón | Tokens diferenciados para interfaces (`#B983FF`), structs (`#FFD580`), enums (`#33EEFF`), tipos (`#1DE9B6`) y funciones (`#8afdff`). |
| **DLUnire Dark Cyber Soft** | `#04080C` | Cyberpunk Neón | Paleta Cyber adaptada a un fondo azul-pizarra suave y descansado. |

---

## Tema de interfaz (`.sublime-theme`)

Incluye el tema de interfaz **`DLUnire Dark.sublime-theme`**, diseñado para ofrecer una apariencia cohesiva en todo Sublime Text:
- Pestañas activas con acento cian (`#00E8FF`) y contraste nítido en inactivas.
- Barra lateral en `#030508` con selección en `#0D1B2A`.
- Barra de estado en `#010305`.
- Inputs y paleta de comandos en `#080D14`.
- Scrollbars sutiles con transparencia adaptativa.

---

## Instalación

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

## Activación y Configuración

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

Puedes alternar entre esquemas de color y temas fácilmente desde el menú superior:
- **Tema:** `Preferences > Theme > DLUnire Dark.sublime-theme`
- **Esquemas:** `Preferences > Color Scheme > DLUnire Dark > [DLUnire Dark / Soft / Cyber / Cyber Soft]`

O directamente desde la paleta de comandos (`Ctrl+Shift+P` / `Cmd+Shift+P`) ejecutando `UI: Select Color Scheme`.

---

## Otros editores

DLUnire Dark también está disponible para:
- **Visual Studio Code / VSCodium / Cursor:** [VS Code Marketplace](https://marketplace.visualstudio.com/) y [Open VSX](https://open-vsx.org/) como `dlunire.dlunire-dark`.
- **Zed:** Registro oficial de extensiones de [Zed](https://zed.dev) como `dlunire-dark`.

---

## Sobre DLUnire

DLUnire es un ecosistema PHP modular y orientado a APIs para crear aplicaciones web modernas y de alto rendimiento. Más información en [dlunire.dev](https://dlunire.dev).

---

## Licencia

MIT — ver [LICENSE](./LICENSE).