# Simulador de Ingeniería Social

⚠️ Aviso importante: Este repositorio contiene una demo educativa que simula técnicas de ingeniería social y *no* explota vulnerabilidades reales. Está destinada únicamente para fines de concienciación y formación sobre seguridad. Úsala de forma responsable, legal y ética.

## Descripción

Este pequeño proyecto contiene una demo visual y local llamada `simulador-ingenieria-social.html`. La página reproduce la experiencia de un formulario aparentemente inocente que, tras interactuar con el usuario, muestra una secuencia simulada que representa un exploit (todo es una simulación con fines pedagógicos).

El objetivo es ayudar a concienciar sobre cómo preguntas aparentemente inútiles o botones llamativos pueden formar parte de un ataque de ingeniería social.

## Contenido del repositorio

- `simulador-ingenieria-social.html` — la demo completa en HTML + CSS + JavaScript.

## Uso / Cómo probar

Las opciones más simples para ejecutar la demo localmente son:

1) Abrir directamente el archivo en tu navegador:

   - Haz doble clic en `simulador-ingenieria-social.html` o ábrelo manualmente desde el navegador.

2) Servir localmente con Python (recomendado para evitar problemas con políticas de navegador o CORS):

```bash
# desde la raíz del repo (Linux/macOS / Python 3.x)
python3 -m http.server 8000

# luego abre en tu navegador:
http://localhost:8000/simulador-ingenieria-social.html
```

## ¿Qué muestra la demo?

- Un formulario con preguntas aparentemente inocuas.
- Al enviar se muestra un aviso y un botón rojo que, al presionarlo, simula una serie de mensajes de ataque en un terminal visual antes de mostrar un mensaje final de "solo una demo".

## Buenas prácticas y advertencias

- Esta demo está pensada para concienciación y formación interna o personal; **no** debe usarse para engañar, atacar o vulnerar a terceros.
- Antes de realizar cualquier prueba con personas reales, asegúrate de tener autorización explícita y de seguir las leyes y políticas aplicables.

## Contribuciones y mejoras

Si quieres mejorar la demo o añadir material formativo (por ejemplo: escenarios, documentación o traducciones), abre un issue o un pull request. Ten presente el enfoque responsable y educativo.

## Licencia

Usa este repositorio de forma responsable. No se proporciona una licencia explícita en este proyecto; si necesitas usarlo públicamente o en un entorno profesional, te recomendamos añadir una licencia adecuada (por ejemplo MIT) y documentar el ámbito de uso.

---

Proyecto: IngenieraSocial — Demo educativa para concienciación sobre ingeniería social.