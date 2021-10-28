# Hacer encuesta docente UPB - Responder todas las preguntas "Siempre"

__Código__:

```JavaScript
var siempre = document.querySelectorAll('[id^="multopt"][value*="-1"]')
siempre.forEach( e =>{ document.getElementById(e.id).click() })
```
