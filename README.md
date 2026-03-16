# MisTareas 📝

Una aplicación web simple para organizar tus tareas del día a día.

## ¿Qué hace?

- Podés **agregar** tareas escribiéndolas y haciendo clic en "Agregar" (o presionando Enter)
- Podés **marcar tareas como completadas** con el botón "✓ Listo"
- Podés **eliminar** tareas que ya no necesitás
- Las tareas completadas se muestran en una sección separada

## Herramientas usadas

- [Astro](https://astro.build/) - framework para sitios estáticos
- HTML semántico
- CSS (sin librerías externas)
- JavaScript vanilla (sin librerías externas)

## Cómo ejecutarlo

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/mi-lista-tareas.git
   cd mi-lista-tareas
   ```

2. Instalá las dependencias:
   ```bash
   npm install
   ```

3. Corré el servidor de desarrollo:
   ```bash
   npm run dev
   ```

4. Abrí tu navegador en `http://localhost:4321`

## Estructura del proyecto

```
mi-lista-tareas/
├── src/
│   ├── components/
│   │   ├── Header.astro     → encabezado de la página
│   │   ├── TaskApp.astro    → la aplicación de tareas (lógica + estilos)
│   │   └── Footer.astro     → pie de página
│   └── pages/
│       └── index.astro      → página principal
├── astro.config.mjs
├── package.json
└── README.md
```
