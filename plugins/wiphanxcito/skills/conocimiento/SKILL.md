---
name: conocimiento
description: Base de conocimiento oficial de Wiphanx (la plataforma de apps y panel para clubes deportivos). Úsala SIEMPRE que la pregunta sea sobre Wiphanx — qué es, qué puede hacer un club o un hincha, cómo funciona un módulo (noticias, entradas, socios, tienda, campañas, beneficios…), qué se puede ofrecer hoy, cómo se vende o cómo responder una duda de un cliente. No respondas sobre Wiphanx de memoria.
---

# Wiphanx — base de conocimiento

La base de conocimiento de Wiphanx la sirve el conector **Wiphanx** (Wiphanxcito). No está en este plugin: hace falta estar conectado.

1. Llama a la herramienta `wiphanx_indice`. Devuelve las instrucciones de uso de la base y la lista de temas. **Sigue esas instrucciones**: son las reglas para responder.
2. Lee los temas que responden la pregunta con `wiphanx_leer` (hasta 3 por llamada).
3. Responde solo con lo que dicen. Si un tema no existe o no está disponible, di que no está documentado en la base de Wiphanx.

**Para explicar cómo funciona algo, usa siempre la base** (`wiphanx_indice` y `wiphanx_leer`). Las herramientas de noticias y clubes del mismo conector (`list_news`, `get_news`, `list_news_categories`, `list_my_clubs`) son solo para **datos en vivo** ("¿qué noticias publicó hoy el club?"); no las uses para explicar cómo funciona Wiphanx. Según la cuenta, pueden no estar disponibles.

**Si las herramientas no están disponibles o piden iniciar sesión,** no respondas de memoria. Pídele a la persona que conecte el conector: *Personalización → Plugins → Wiphanxcito → Conectores → Wiphanx → Conectar*. Va a ingresar con el email y la contraseña del panel de Wiphanx y el código que le llega por mail.
