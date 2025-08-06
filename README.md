# Kindle Todo Dashboard

Dashboard de tareas pendientes diseñado específicamente para el navegador experimental del Amazon Kindle Scribe.

## 🎯 Objetivo

Crear una aplicación web de lista de tareas que funcione perfectamente en las limitaciones del Kindle Scribe:
- Pantalla E Ink (sin colores, alto contraste)
- Navegador con JavaScript limitado
- Pantalla táctil de 10.2" (2208 x 1680 píxeles)

## 📱 Versiones Disponibles

### [Version 1](https://mario-hernandez.github.io/kindle-todo-dashboard/index.html)
- Diseño básico con texto grande
- Media queries para orientación landscape/portrait
- Funcionalidad completa de añadir, marcar y eliminar tareas
- Persistencia con localStorage

### [Version 2](https://mario-hernandez.github.io/kindle-todo-dashboard/index-v2.html)
- **Rotación dinámica automática**: El dashboard se muestra en modo apaisado (rotado 90°) por defecto
- **Modo Vista**: Pantalla rotada para máximo aprovechamiento del espacio
- **Modo Edición**: Al tocar el campo de texto, la pantalla vuelve automáticamente a orientación vertical
- Transiciones suaves entre modos

### [Version 3](https://mario-hernandez.github.io/kindle-todo-dashboard/index-v3.html) ✨ Última versión
- **Diseño minimalista y elegante** con tipografía Georgia serif
- **Botón EDITAR**: Muestra/oculta el panel de añadir tareas
- **Título reducido** y más discreto
- **Contador de tareas**: Muestra pendientes y completadas
- **Mejoras visuales**: Hover effects, bordes suaves, mejor espaciado
- Las nuevas tareas se añaden al principio de la lista

## 🛠️ Características Técnicas

### Compatibilidad
- JavaScript vanilla (ES5) para máxima compatibilidad
- Sin dependencias externas
- HTML único con CSS y JS embebidos
- Alto contraste (blanco #FFFFFF y negro #000000)

### Funcionalidades
- ✅ Añadir tareas (Enter o botón)
- ✅ Marcar como completadas (toque/click en la tarea)
- ✅ Eliminar tareas (botón X)
- ✅ Persistencia local con localStorage
- ✅ Diseño responsive para modo vertical y apaisado

### Innovación en v2 y v3
- Solución creativa al problema de orientación del Kindle Scribe
- Uso de CSS transforms para rotar la interfaz
- Detección automática de contexto (edición vs visualización)
- Experiencia de usuario optimizada para E Ink

## 🚀 Instalación Local

```bash
git clone https://github.com/mario-hernandez/kindle-todo-dashboard.git
cd kindle-todo-dashboard
# Abrir index.html, index-v2.html o index-v3.html en un navegador
```

## 📝 Desarrollo

El proyecto evolucionó en tres iteraciones:

1. **v1**: Implementación base con media queries tradicionales
2. **v2**: Innovación con rotación dinámica automática
3. **v3**: Refinamiento del diseño y experiencia de usuario

### Decisiones de Diseño
- **Texto enorme**: 3.5rem para máxima legibilidad en E Ink
- **Sin animaciones complejas**: Solo transiciones básicas
- **Controles grandes**: Optimizados para pantalla táctil
- **Minimalismo**: Reducir distracciones visuales

## 🔗 Enlaces

- [Repositorio GitHub](https://github.com/mario-hernandez/kindle-todo-dashboard)
- [Demo v1](https://mario-hernandez.github.io/kindle-todo-dashboard/index.html)
- [Demo v2](https://mario-hernandez.github.io/kindle-todo-dashboard/index-v2.html)
- [Demo v3](https://mario-hernandez.github.io/kindle-todo-dashboard/index-v3.html)

## 📄 Licencia

Este proyecto está disponible para uso libre. Creado específicamente para mejorar la experiencia del Kindle Scribe.

---

Desarrollado con ❤️ para el Kindle Scribe