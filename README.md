# 🎀 Florencia Lee - App de Lectoescritura para Niños

## ¿Qué es?

**Florencia Lee** es una aplicación web educativa diseñada para ayudar a niños en edad preescolar y primer grado a aprender a leer y escribir en español. Con una estética inspirada en Barbie (rosa, brillante y divertida), la app convierte el aprendizaje en un juego atractivo y motivador.

---

## 🎯 Objetivo Pedagógico

La aplicación trabaja el **reconocimiento de letras** y la **construcción de palabras**, habilidades fundamentales en el proceso de alfabetización inicial. El niño debe:

1. Identificar la palabra objetivo (con apoyo visual de emoji)
2. Seleccionar las letras correctas en el orden correcto
3. Completar la palabra para avanzar

Este enfoque refuerza:
- **Conciencia fonológica**: asociación sonido-letra
- **Memoria visual**: reconocimiento de la forma de las palabras
- **Motricidad fina**: selección táctil precisa
- **Autoconfianza**: feedback positivo inmediato

---

## 🎮 Cómo Funciona

### Pantalla de Inicio
- Muestra todas las palabras disponibles como tarjetas
- Cada tarjeta tiene un emoji representativo y la palabra
- Las palabras completadas se marcan con una estrella ⭐
- Una barra de progreso arcoíris muestra el avance general

### Ejercicio de Armado de Palabras
1. Se muestra un emoji grande (ej: 🐶 para PERRO)
2. El botón "📢 Tarea" reproduce la instrucción por voz
3. Aparecen casilleros vacíos (uno por letra)
4. Abajo hay un banco de letras mezcladas (correctas + distractoras)
5. El niño toca las letras en orden para armar la palabra

### Sistema de Feedback
- **Letra correcta**: Se ilumina en verde, suena la letra, avanza al siguiente casillero
- **Letra incorrecta**: Se sacude en rojo, suena "Esa no", puede reintentar
- **Palabra completa**: Confetti, mensaje de éxito, voz de felicitación

### Voz de Maestra
La aplicación incluye síntesis de voz en español rioplatense configurada con tono femenino y pausado, simulando una maestra que guía al niño con calidez.

---

## 📚 Palabras Incluidas

La app incluye 20 palabras cuidadosamente seleccionadas por su relevancia para niños pequeños:

| Palabra | Emoji | Categoría |
|---------|-------|-----------|
| MAMÁ | 👩‍👧 | Familia |
| PAPÁ | 👨‍👧 | Familia |
| TÍA | 👩 | Familia |
| ABUELA | 👵 | Familia |
| ABUELO | 👴 | Familia |
| BEBÉ | 👶 | Familia |
| PERRO | 🐶 | Animales |
| GATO | 🐱 | Animales |
| RATA | 🐀 | Animales |
| ESCUELA | 🏫 | Lugares |
| SEÑO | 👩‍🏫 | Personas |
| AGUA | 💧 | Objetos |
| VERDURAS | 🥦 | Alimentos |
| BANANA | 🍌 | Alimentos |
| YOGURT | 🥛 | Alimentos |
| REMERA | 👕 | Ropa |
| VESTIDO | 👗 | Ropa |
| LÁPIZ | ✏️ | Escuela |
| PAPEL | 📄 | Escuela |
| MOCHILA | 🎒 | Escuela |
| AUTO | 🚗 | Vehículos |

---

## 🛠️ Características Técnicas

### Tecnologías
- **HTML5 + CSS3 + JavaScript** (vanilla, sin frameworks)
- **Web Speech API** para síntesis de voz
- **LocalStorage** para guardar progreso
- **PWA-ready**: puede instalarse como app

### Diseño Responsivo
- Optimizado para tablets y celulares
- Interfaz táctil con botones grandes
- Safe area para dispositivos con notch

### Persistencia
- El progreso se guarda automáticamente en el navegador
- Las palabras completadas persisten entre sesiones
- No requiere cuenta ni conexión a internet (después de cargar)

---

## 📱 Cómo Usar

### En Celular/Tablet (Recomendado)
1. Abrir el archivo HTML en el navegador
2. Opcionalmente, agregar a pantalla de inicio para experiencia de app
3. ¡Listo para jugar!

### En Computadora
1. Abrir el archivo HTML en Chrome, Firefox o Edge
2. Para simular experiencia móvil: F12 → Toggle Device Toolbar

---

## 🎨 Identidad Visual

La aplicación usa una paleta "Barbie" moderna:

| Color | Uso | Código |
|-------|-----|--------|
| Rosa Barbie | Color principal | `#E0218A` |
| Rosa Claro | Acentos | `#FF69B4` |
| Cyan | Botones secundarios | `#00C1DE` |
| Blanco | Fondos de tarjetas | `#FFFFFF` |
| Gris Claro | Fondo general | `#F9F9F9` |

**Tipografías:**
- **Quicksand**: Títulos (redondeada, amigable)
- **Nunito Sans**: Texto general (legible, moderna)

---

## 🔊 Sistema de Voz

La voz está configurada para sonar como una maestra argentina:

```javascript
utterance.lang = 'es-AR';    // Español argentino
utterance.rate = 0.85;       // Velocidad pausada
utterance.pitch = 1.2;       // Tono femenino
```

El sistema busca automáticamente voces femeninas en español, priorizando:
1. Voces argentinas (es-AR)
2. Voces latinoamericanas (es-MX, es-419)
3. Voces españolas (es-ES)

---

## 👩‍💻 Créditos

- **Diseño y Desarrollo**: Creado con asistencia de Claude (Anthropic)
- **Concepto**: Aplicación educativa para alfabetización inicial
- **Destinatario**: Niños de 4-7 años aprendiendo a leer en español

---

## 📄 Licencia

Uso libre para fines educativos. 

---

*¡Que Florencia disfrute aprendiendo a leer!* 🌈✨
