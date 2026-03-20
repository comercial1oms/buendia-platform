# Cómo arrancar un módulo nuevo

**Regla de oro:** Antes de escribir una sola línea de código, hay que responder estas preguntas. Sin excepción.

---

## Preguntas obligatorias antes de empezar

### 1. ¿A qué vertical pertenece?

| Vertical | Descripción |
|----------|-------------|
| Comercial | Tienda en línea, ventas institucionales, agente WhatsApp |
| Operaciones | Picking, compras, inventario, requisiciones |
| RRHH | Horarios, asistencia, checador |
| Analítica | Dashboard, reportes, métricas |

### 2. ¿Qué problema resuelve?
Describir en una oración el problema concreto que este módulo resuelve.

### 3. ¿Quién lo usa?
- ¿Es para clientes externos o empleados internos?
- ¿Cuántas personas lo usarán?
- ¿En qué dispositivo principalmente? (celular / tablet / PC)

### 4. ¿Qué datos necesita?
- ¿Lee datos de Supabase? ¿De qué tablas?
- ¿Crea datos nuevos? ¿En qué tablas?
- ¿Necesita tablas nuevas? ¿Cuáles?

### 5. ¿Se conecta con otro módulo?
- ¿Comparte datos con horarios, picking, ventas, etc.?
- ¿Quién es el dueño de esos datos?

### 6. ¿Cuál es el flujo mínimo viable?
Describir los 3-5 pasos básicos que el usuario hace en este módulo.

### 7. ¿Cuándo está "listo"?
Definir qué significa que el módulo está terminado y funcionando.

---

## Proceso después de responder las preguntas

1. Crear rama en GitHub: `feat/nombre-del-modulo`
2. Crear carpeta en `modules/nombre-del-modulo/`
3. Definir tablas en Supabase si se necesitan nuevas
4. Desarrollar usando `styles/design-tokens.css` para todos los colores
5. Hacer PR a `main` cuando esté listo para revisión
6. Alberto revisa y aprueba antes del merge

---

## Módulos planificados

| Módulo | Vertical | Estado | Preguntas respondidas |
|--------|----------|--------|-----------------------|
| horarios | RRHH | ✅ Activo | ✅ Sí |
| picking | Operaciones | ✅ Activo | ✅ Sí |
| tienda | Comercial | 🔜 Pendiente | ❌ Faltan |
| ventas-institucionales | Comercial | 🔜 Pendiente | ❌ Faltan |
| agente-whatsapp | Comercial | 🔜 Pendiente | ❌ Faltan |
| compras | Operaciones | 🔜 Pendiente | ❌ Faltan |
| dashboard | Analítica | 🔜 Pendiente | ❌ Faltan |

