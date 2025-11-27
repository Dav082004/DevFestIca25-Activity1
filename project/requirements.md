# QuickBuild Cards - Generador de Tarjetas Digitales

## 🎯 Objetivo del Proyecto
Desarrollar un MVP funcional en 10 minutos que permita generar tarjetas de presentación digitales.

## 📋 Requisitos Funcionales

### Formulario de Datos
- [ ] Campo: Nombre completo (obligatorio)
- [ ] Campo: Cargo (opcional)
- [ ] Campo: Empresa (opcional) 
- [ ] Campo: Email (validación formato)
- [ ] Campo: Teléfono (opcional)
- [ ] Botón: "Generar Tarjeta"

### Visualización de Tarjeta
- [ ] Diseño profesional estilo tarjeta física
- [ ] Mostrar todos los datos ingresados
- [ ] Iconos para email y teléfono
- [ ] Layout organizado y legible

### Funcionalidades
- [ ] Generación en tiempo real
- [ ] Botón "Copiar HTML" al portapapeles
- [ ] Mensaje de confirmación al copiar
- [ ] Diseño responsive

### Validaciones
- [ ] Nombre obligatorio
- [ ] Email con formato válido
- [ ] Mensajes de error claros

## 🎨 Especificaciones de Diseño

### Estructura Visual
```
┌─────────────────────────────────┐
│  👤 [Nombre Completo]           │
│  💼 [Cargo]                     │
│  🏢 [Empresa]                   │
│                                 │
│  📧 [email@empresa.com]         │
│  📞 [+1 (555) 123-4567]         │
└─────────────────────────────────┘
```

### Paleta de Colores
- **Fondo tarjeta**: #ffffff
- **Texto principal**: #1e293b
- **Acentos**: #2563eb
- **Bordes**: #e2e8f0
- **Éxito**: #10b981

## ⚙️ Requisitos Técnicos
- **Vanilla JavaScript**: Sin frameworks
- **CSS Grid/Flexbox**: Para layout
- **Clipboard API**: Para copiado
- **Mobile First**: Diseño responsive
