# 📰 NewsHub - App de Noticias Interactiva

Una aplicación web moderna de lectura de noticias con **gestos táctiles naturales** y **patrones de feedback avanzados** para una experiencia de usuario excepcional.

## ✨ Características Principales

### 🎮 Gestos Táctiles Implementados

#### **Gesto A: Pull-to-Refresh** ⬇️
- **Contexto:** Pantalla principal del feed de noticias
- **Acción:** Desliza hacia abajo para actualizar contenido
- **Beneficio:** Actualización intuitiva sin buscar botones, emulando apps nativas
- **Feedback Visual:** Indicador de distancia, cambio de color, animación suave

#### **Gesto B: Swipe Left/Right** ⬅️➡️
- **Contexto:** Navegación entre categorías (Todas, Deportes, Política, Tecnología, Salud)
- **Acción:** Desliza horizontalmente para cambiar de sección
- **Beneficio:** Navegación fluida como pasar páginas de un periódico físico
- **Feedback Visual:** Animación de transición suave, hint visual al inicio

### 📋 Patrones de Feedback Implementados

#### **Feedback A: Skeleton Screens** 💀
- **Tipo:** Retroalimentación de estado de carga
- **Uso:** Mientras se ejecuta Pull-to-Refresh
- **Características:**
  - Cajas grises pulsantes con forma de noticias
  - Animación fluida de carga (1.5s)
  - Reduce percepción del tiempo de espera
- **Beneficio:** Confirma actividad sin usar ruedas bloqueantes

#### **Feedback B: Snackbar con "Deshacer"** 📍
- **Tipo:** Retroalimentación de confirmación
- **Uso:** Al guardar, compartir, o abrir noticias
- **Características:**
  - Animación de entrada desde abajo
  - Botón "Deshacer" para revertir acciones
  - Múltiples mensajes contextuales
  - Feedback táctil con Vibration API
- **Beneficio:** Confirma acciones sin bloquear lectura, permite recuperación de errores

## 🎨 Mejoras de Diseño

### Diseño Visual
- 🎯 Paleta moderna: Azul profesional (#1976D2), Cian (#00BCD4), Rojo suave (#FF6B6B)
- 📝 Tipografía clara con jerarquía definida
- 🌙 Dark mode completo integrado
- 📱 Completamente responsive

### Micro-interacciones
- ⚡ Animaciones suaves con cubic-bezier optimizado
- 🌊 Ripple effect en botones (Material Design)
- 💫 Entrada escalonada de elementos
- ✨ Efectos de hover y active mejorados

### Accesibilidad
- ♿ ARIA labels completos
- ⌨️ Keyboard navigation (flechas)
- 🎯 Focus states visibles
- 🏃 Respeto a `prefers-reduced-motion`

### Contenido Mejorado
- 🔥 Sección "Featured" con noticias destacadas
- 👤 Avatares de fuentes con iniciales
- 🏷️ Badges para noticias premium
- 📰 Información de autor mejorada

2. **Abrir la aplicación:**
   - Navegador: Abre `PrototipoFuncional/index.html`
   - Live Server (VS Code): Click derecho → "Open with Live Server"

3. **Interactuar:**
   - **Desliza hacia abajo** en las noticias para actualizar
   - **Desliza horizontalmente** para cambiar categorías
   - **Haz clic en noticias** para guardar o compartir
   - Usa **flechas del teclado** para navegar (si está en desktop)

## 💻 Tecnologías

- **HTML5** - Estructura semántica
- **CSS3** - Diseño responsive, animaciones, dark mode
- **JavaScript Vanilla** - Sin dependencias
- **Touch Events API** - Para gestos táctiles
- **Vibration API** - Feedback táctil en móviles
- **Web Standards** - ARIA, accesibilidad completa

## 📊 Especificaciones de Gestos

### Pull-to-Refresh
- **Distancia activación:** > 60px
- **Tiempo de carga:** 2000ms (simulado)
- **Animación:** spin-smooth (1.2s)
- **Feedback:** Texto dinámico, opacidad variable

### Swipe
- **Umbral mínimo:** 50px horizontal
- **Transición:** 400ms cubic-bezier(0.25, 0.46, 0.45, 0.94)
- **Hint visual:** Pulsa después de 2s
- **Keyboard:** Flechas izq/der

### Skeleton Screens
- **Duración:** 1.5s por animación
- **Items:** 3 placeholders
- **Animación:** Shimmer effect horizontal

### Snackbar
- **Duración:** 3.5s por defecto
- **Posición:** Bottom (fixed)
- **Animación:** slideUpSnackbar (300ms)
- **Acción:** Deshacer disponible según contexto

## 📱 Compatibilidad

- ✅ Chrome/Edge (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Dispositivos móviles (iOS, Android)
- ✅ Tablets
- ✅ Desktop responsive

## 🎓 Propósito Educativo

Este proyecto fue desarrollado como parte del curso **"Interacción Humano Computador"** en la Universidad Nacional de San Agustín (UNSA), demostrando:

- Implementación de gestos táctiles naturales
- Patrones de feedback y retroalimentación
- Diseño responsive y accessible
- Micro-interacciones modernas
- Mejores prácticas en UX/UI

## 👤 Autor

**Leonardo Baca Calsin**  
UNSA - Ingeniería de Sistemas  
Curso: Interacción Humano Computador 2025-B

---

**¿Preguntas o sugerencias?** Abre un Issue en GitHub o contáctame.

Made with ❤️ for better user experiences
