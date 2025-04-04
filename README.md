# 📌 Implement Community Features for NodeSpeak v2.5.5

## Descripción
Este PR implementa mejoras significativas en las funcionalidades de comunidad para NodeSpeak v2.5.5, centradas en aumentar la interacción y el compromiso de los usuarios.

## Cambios Implementados

### 1. Contador de Miembros en Comunidades
- Muestra el número de miembros en cada tarjeta de comunidad
- Proporciona mayor contexto sobre el tamaño y actividad de cada comunidad

### 2. Usuarios Viendo en Vivo
- Agrega un indicador en tiempo real que muestra cuántos usuarios están viendo cada comunidad
- El contador se actualiza dinámicamente cada 5 segundos para simular actividad en vivo
- Incluye indicador visual "watching live" con animación para una mejor experiencia de usuario

### 3. Sistema de Like y Dislike para Posts
- Implementa botones de like (❤️) y dislike (👎) para todos los posts
- Agrega contadores visuales para likes y dislikes
- Incluye animaciones de feedback al hacer clic en los botones
- Agrega campo `dislikeCount` al modelo de Post para almacenar esta información

### 4. Actualización de Versión
- Actualiza la versión del proyecto a 2.5.5
- Cambia el nombre del paquete de "nextjs" a "nodespeak" en package.json

## Consideraciones Técnicas
- Las funcionalidades están implementadas con React y TypeScript
- Se mantiene la compatibilidad con el tema Matrix existente
- Los efectos visuales y animaciones se implementan con Tailwind CSS
- Se considera la experiencia de usuario para dar feedback visual apropiado

## Pruebas Realizadas
- Verificación del contador de miembros en cada comunidad
- Comprobación de la simulación de usuarios en vivo
- Pruebas de interacción con los botones de like y dislike
- Validación del correcto almacenamiento de los contadores
