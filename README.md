# Accelerazione Landing Page

Landing page comercial moderna y optimizada desarrollada para **Accelerazione**, construida con **Astro** y **Tailwind CSS**.

Este documento sirve como guía técnica y de contexto para que cualquier modelo de IA o desarrollador pueda comprender rápidamente la estructura del proyecto y continuar con su desarrollo sin fricciones.

---

## 🛠️ Tecnologías Principales
- **Astro v6** (Framework de componentes y páginas estáticas/híbridas)
- **Tailwind CSS v4** (Estilos y diseño responsivo)
- **Node.js** (Versión >= 22.12.0)

---

## 📂 Estructura del Proyecto

```text
/
├── public/                 # Archivos estáticos, logos de clientes y recursos multimedia
├── src/
│   ├── components/         # Componentes modulares de la landing page
│   │   ├── Blog.astro
│   │   ├── Contact.astro
│   │   ├── Differentiators.astro
│   │   ├── FAQ.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│   │   ├── MediaCard.astro
│   │   ├── Navbar.astro
│   │   ├── Portfolio.astro
│   │   ├── Pricing.astro
│   │   └── Stats.astro
│   ├── layouts/
│   │   └── Layout.astro    # Layout principal con metadatos y estructura HTML base
│   └── styles/
│       └── global.css      # Estilos globales y configuración de Tailwind
├── astro.config.mjs        # Configuración de Astro
└── package.json            # Dependencias y scripts
```

---

## 🧞 Comandos Útiles

Ejecuta estos comandos desde la raíz del proyecto en tu terminal:

| Comando | Acción |
| :--- | :--- |
| `npm install` | Instala las dependencias del proyecto |
| `npm run dev` | Inicia el servidor de desarrollo local en `localhost:4321` |
| `npm run build` | Genera la compilación de producción en `./dist/` |
| `npm run preview` | Previsualiza la compilación de producción localmente |

---

## 🔒 Seguridad y Credenciales
- **No existen contraseñas, tokens ni API Keys hardcodeadas** en el código fuente ni en el historial de git público.
- Cualquier variable de entorno sensible futura debe manejarse mediante archivos `.env` (excluidos en `.gitignore`).

---

## 🚀 Estado Actual y Próximos Pasos para la IA
- **Estado Actual:** La landing page cuenta con una estructura modular completa en `src/components/`, incluyendo secciones de presentación, clientes/portafolio, precios, estadísticas, diferenciadores, contacto, FAQ y blog.
- **Cómo continuar:** Al retomar el proyecto con cualquier modelo, pídele que lea este `README.md` junto con `package.json` y la estructura dentro de `src/` para tener todo el contexto técnico inmediato.
