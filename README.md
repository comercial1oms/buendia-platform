# Buen Día Fresh — Plataforma Digital

Plataforma tecnológica centralizada de Buen Día Fresh. Todos los módulos del negocio en un solo lugar.

## Stack tecnológico

- **Frontend**: Next.js
- **Base de datos**: Supabase
- **Deploy**: Vercel
- **Versiones**: GitHub

## Estructura del repositorio

```
buendia-platform/
├── styles/              ← Design system compartido
│   └── design-tokens.css
├── components/          ← Componentes UI reutilizables
├── modules/             ← Módulos por vertical
│   ├── horarios/        ← Sistema de horarios y asistencia
│   ├── picking/         ← App de picking para tienda
│   ├── tienda/          ← Tienda en línea (delivery/pickup)
│   ├── ventas-inst/     ← Ventas institucionales WhatsApp
│   ├── compras/         ← Requisiciones y compras
│   └── dashboard/       ← Reportes y métricas
├── database/            ← Migraciones y esquema Supabase
└── docs/                ← Documentación del equipo
```

## Reglas del equipo

- **Nadie sube directo a `main`** — main = producción
- Cada módulo tiene su propia rama: `feat/horarios`, `feat/picking`, etc.
- Todo pasa por revisión antes de hacer merge

## Design System

Paleta de colores, tipografía y componentes definidos en `styles/design-tokens.css`.

**Combinación principal digital**: Blanco (#FFFFFF) sobre Verde Oscuro (#004C45)

Tipografías:
- Titulares: **Castledown** (Colophon Foundry)
- Cuerpos: **Basis Grotesque** (Colophon Foundry)

## Módulos activos

| Módulo | Estado | URL |
|--------|--------|-----|
| Horarios | ✅ Activo | horarios-bdf.vercel.app |
| Picking | ✅ Activo | picking-app-steel.vercel.app |
| Tienda | 🔄 En desarrollo | — |
| Ventas inst. | 🔄 En desarrollo | — |

## Contacto

Alberto J. Juan Garza — Gerente General  
comercial1.oms@gmail.com
