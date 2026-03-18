# @pedrocaballeroweb/caba-nav

Componente web (Lit) para crear una barra de navegación simple con tres zonas (menú, título y acciones) usando **slots** y una propiedad para cambiar el layout.

---

## 📦 Instalación

### Desde npm (cuando esté publicado)
```bash
npm install @pedrocaballeroweb/caba-nav
```

### Desde el repositorio local
```bash
npm install ../components/caba-nav
```

---

## 🚀 Uso

### Importar el componente (módulo)
```html
<script type="module">
  import '@pedrocaballeroweb/caba-nav';
</script>

import '@pedrocaballeroweb/caba-nav/caba-nav.js';

```

### Ejemplo de uso en HTML
```html
<caba-nav menu="right">
  <h2 slot="title">Bienvenidos</h2>
  <span slot="menu">[X]</span>
  <span slot="actions">Create</span>
</caba-nav>
```

---

## 🧩 Propiedades

### `menu`
- Tipo: `String`
- Valores: `"left"` (por defecto), `"right"`
- Efecto: controla la posición de las zonas dentro del layout (menú a la izquierda o a la derecha).

---

## 🪟 Slots

- `slot="menu"` → contenido del menú (ícono, botón de hamburguesa, etc).
- `slot="title"` → título o logo.
- `slot="actions"` → acciones / botones secundarios.

---

## 🎨 Variables CSS personalizables

Puedes cambiar colores, padding y espaciado desde CSS global:

- `--caba-nav-color` *(texto)*  
- `--caba-nav-background-color` *(fondo)*  
- `--caba-nav-align-items` *(alineación vertical)*  
- `--caba-nav-column-gap` *(espacio entre columnas)*  
- `--caba-nav-padding-y` *(padding vertical)*  
- `--caba-nav-padding-x` *(padding horizontal)*  

Ejemplo:
```css
caba-nav {
  --caba-nav-background-color: #222;
  --caba-nav-color: #fff;
}
```

---

## 🛠️ Desarrollo

Para probar cambios localmente puedes servir `app.html` con un servidor estático (live-server, vite, etc.). Ejemplo con `live-server`:

```bash
npm install --save-dev live-server
npx live-server app.html
```

--- 

## 📄 Licencia

MIT  
```// filepath: /Users/pedrocaballeroramirez/Documents/lit/components/caba-nav/README.md
# @pedrocaballeroweb/caba-nav

Componente web (Lit) para crear una barra de navegación simple con tres zonas (menú, título y acciones) usando **slots** y una propiedad para cambiar el layout.

---

## 📦 Instalación

### Desde npm (cuando esté publicado)
```bash
npm install @pedrocaballeroweb/caba-nav
```

### Desde el repositorio local
```bash
npm install ../components/caba-nav
```

---

## 🚀 Uso

### Importar el componente (módulo)
```html
<script type="module">
  import '@pedrocaballeroweb/caba-nav';
</script>
```

### Ejemplo de uso en HTML
```html
<caba-nav menu="right">
  <h2 slot="title">Bienvenidos</h2>
  <span slot="menu">[X]</span>
  <span slot="actions">Create</span>
</caba-nav>
```

---

## 🧩 Propiedades

### `menu`
- Tipo: `String`
- Valores: `"left"` (por defecto), `"right"`
- Efecto: controla la posición de las zonas dentro del layout (menú a la izquierda o a la derecha).

---

## 🪟 Slots

- `slot="menu"` → contenido del menú (ícono, botón de hamburguesa, etc).
- `slot="title"` → título o logo.
- `slot="actions"` → acciones / botones secundarios.

---

## 🎨 Variables CSS personalizables

Puedes cambiar colores, padding y espaciado desde CSS global:

- `--caba-nav-color` *(texto)*  
- `--caba-nav-background-color` *(fondo)*  
- `--caba-nav-align-items` *(alineación vertical)*  
- `--caba-nav-column-gap` *(espacio entre columnas)*  
- `--caba-nav-padding-y` *(padding vertical)*  
- `--caba-nav-padding-x` *(padding horizontal)*  

Ejemplo:
```css
caba-nav {
  --caba-nav-background-color: #222;
  --caba-nav-color: #fff;
}
```

---

## 🛠️ Desarrollo

Para probar cambios localmente puedes servir `app.html` con un servidor estático (live-server, vite, etc.). Ejemplo con `live-server`:

```bash
npm install --save-dev live-server
npx live-server app.html
```

--- 

## 📄 Licencia

MIT  