# 🎤 Secuencia de Prompts para la Demo (10 minutos)

## Minuto 1-2: Setup Inicial
```bash
# Autenticación y configuración
github-copilot-cli auth
copilot init
```

## Minuto 2-4: Estructura Base
```bash
# Prompt 1: Crear estructura HTML
copilot exec "Crea un archivo HTML5 completo con un formulario para tarjeta de presentación que incluya campos para nombre, cargo, empresa, email y teléfono. Incluye un botón 'Generar Tarjeta' y un área para mostrar el resultado."
```

## Minuto 4-6: Estilos y Diseño
```bash
# Prompt 2: Diseño profesional
copilot exec "Añade CSS para darle un diseño profesional a la tarjeta. Usa la paleta de colores azul (#2563eb) y blanco. La tarjeta debe tener bordes redondeados, sombra y verse como una tarjeta de presentación física real."
```

## Minuto 6-8: Funcionalidad JavaScript
```bash
# Prompt 3: Lógica de generación
copilot exec "Implementa la funcionalidad JavaScript para que al hacer click en 'Generar Tarjeta' se tome la información del formulario y se muestre una tarjeta de presentación elegante en el área de resultados."
```

## Minuto 8-9: Feature de Copiado
```bash
# Prompt 4: Copiar al portapapeles
copilot exec "Añade un botón 'Copiar HTML' que copie el código HTML de la tarjeta generada al portapapeles. Muestra un mensaje de '¡Copiado!' cuando se complete la acción."
```

## Minuto 9-10: Mejoras Finales
```bash
# Prompt 5: Responsive y validación
copilot exec "Haz el diseño responsive para móviles y añade validación básica: nombre obligatorio y email con formato válido."
```

## Comandos de Verificación
```bash
# Abrir con Live Server
npx live-server project/

# Probar funcionalidad
# 1. Llenar formulario
# 2. Generar tarjeta
# 3. Copiar HTML
# 4. Verificar en móvil
```

## 💡 Tips para el Presentador
- **Minuto 2**: Mostrar HTML generado
- **Minuto 4**: Mostrar diseño CSS
- **Minuto 6**: Demostrar generación
- **Minuto 8**: Probar copiado
- **Minuto 9**: Mostrar en móvil
- **Minuto 10**: Resumen y cierre
