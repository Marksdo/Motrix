# README.md
- [Deutsch](README.de.md)
- [English](README.md)
- [Spanish](README.es.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)

# 🎠 Motrix - Cliente nativo de chatGPT para macOS  

Descargar [la última versión de la App Store de macOS](https://apps.apple.com/us/app/id6447776319)  

## Características clave  
- Soporte para proxy local LLM litellm  
- Debes tener una clave API de GPT para ejecutar la aplicación Motrix  
- Conectar API de chatGPT o servicio proxy GPT (host personalizado)  
- Soporte de chat grupal  
- Reintentos automáticos  
- Selector rápido de plantilla de prompt  
- Los nodos de chat se pueden organizar como un árbol (arrastrar y soltar)  
- Interruptor de apertura rápida global para volver al chat  
- Nodos de chat personalizados en la barra de menú  
- Conversaciones con formato Markdown  
- Guardar chats y consultas favoritas para más tarde  
- Icono visible de AI que muestra cuántos mensajes contextuales puede leer AI  
- Búsqueda de conversaciones por palabras clave  
- Incrustar 6 temas con soporte claro/oscuro  

V1.9.2  
---  
- Agregar función para hacer copia de seguridad de todos los datos y restaurarlos en las preferencias  
- Agregar función para duplicar un mensaje a otro nodo de chat  
- Agregar modo de chat de notas para solo guardar algo y no enviarlo al servidor de AI  
- Agregar mensaje temporal como mensaje de chat grupal comenzando un nuevo chat con el formato '@nodo1;nodo2;nodo5 nueva línea texto a traducir'  
- Agregar chat grupal temporal rápido desde el menú contextual del árbol izquierdo  
- Agregar función para bloquear el contexto en una fila, permitiendo que la conversación siempre se envíe desde la fila de contexto bloqueado  
- Agregar doble toque para editar temporizador en una pequeña ventana emergente en modo editor  
- Agregar opciones de hilos paralelos de chat grupal en la barra deslizante, se usa para reducir las solicitudes paralelas a la API debido a problemas de respuesta del servidor  
- Agregar opciones de edición de temporizador directamente en la ventana emergente de chat  
- Agregar acceso directo para abrir cualquier nodo de chat con una ventana flotante  
- Corregir estilo incorrecto de la ventana rápida  
- Corregir el modo de transmisión que no puede leer datos del proyecto de código abierto litellm en modo proxy  
- [V1.9.2-Uni](https://download.marksdo.com/apps/Motrix/V1.9.2/Motrix.dmg)   
  
  
  
V1.9.1  
---  
- Agregar doble toque para editar temporizador en una pequeña ventana emergente en modo editor  
- Agregar opciones de edición de temporizador directamente en la ventana emergente de chat  
- Agregar acceso directo para abrir cualquier nodo de chat con una ventana flotante  
- Corregir estilo incorrecto de la ventana rápida  
- [V1.9.1-Uni](https://download.marksdo.com/apps/Motrix/V1.9.1/Motrix.zip)   
  
V1.9.0  
---  
- Agregar soporte para proxy llm/gpt desplegado localmente (litellm) http://127.0.0.1:8000 como host para admitir la mayoría de los servidores de chat llm/gpt de código abierto  
- Agregar función de clonación para nodos de chat en el menú contextual derecho  
- Agregar función de configuración de parámetros del modelo de varios nodos a la vez (seleccionar varios nodos del árbol y luego utilizar el menú contextual -> configuración masiva)  
- Corregir descripción incorrecta de las instrucciones del sistema que no se pueden contraer  
- [73,6 MB](https://download.marksdo.com/apps/Motrix/V1.9.0/Motrix.zip)   
![image](/images/V190.webp)  
  
V1.8.9  
---  
- Agregar acceso directo para cambiar al siguiente nodo de chat en el árbol (se utiliza para combinar con otras aplicaciones de acceso directo en lote del sistema)  
- Agregar captura instantánea en el menú contextual derecho del contenido del chat  
- La ventana emergente de resultados de consulta de IA programada se puede guardar como imagen completa en el portapapeles  
- Se ha eliminado la barra de herramientas de la fila de contenido del chat. Se utiliza el menú contextual derecho como reemplazo  
- Corregido el problema de diseño al compartir contenido de chat en modo de selección en lote  
- Corregido el bloqueo al iniciar en macOS 11  
- Descargar edición universal [73,5 MB](https://download.marksdo.com/apps/Motrix/V1.8.9/Motrix.zip)   
  
  
V1.8.7  
---   
- Agregar configuración de clave de modelo. Puede configurar la clave del modelo al conectarse a un nuevo modelo.  
- Agregar función de selección en lote para eliminar filas de chat  
- Agregar opción para desactivar el desplazamiento automático al final de la lista de chat  
- Agregar configuración de apariencia para cambiar el tamaño de fuente de la interfaz de usuario  
- Agregar acceso directo ⌘+(+-) para cambiar rápidamente el tamaño del contenido del chat  
- Agregar opción de altura de caja de entrada fija en el control deslizante de opciones  
- El tamaño de la barra de navegación izquierda puede ser más pequeño  
- El nuevo nodo de chat utilizará los parámetros AI del nodo de chat seleccionado anteriormente  
- Corregido el problema de que la ventana emergente personalizada de preguntas de IA todavía se abre cuando el sistema está en reposo  
- Corregida la opción para renderizar Markdown que no se puede alternar en la configuración  
- Corregido el problema de intención de la aplicación Motrix con las aplicaciones de acceso directo  
  
V1.8.5  
---  
- Se añadió soporte para modelos GPT3.5 y GPT4 16K  
- Se añadió soporte para configurar el ancho predeterminado de la ventana emergente del temporizador (se utiliza para obtener consejos diarios de AI con respuestas largas)  
- Se corrigió el problema de visualización en el modo de transmisión  
- Se corrigieron los errores de visualización en la ventana emergente del temporizador  
- Se corrigió el problema de atascamiento en los nuevos nodos en macOS 11.0  
  
V1.8.4  
---  
- Se agregó una nueva página de guía de chat. Puede seleccionar un rol de IA predefinido para comenzar a chatear.  
- Correcciones de errores y mejoras de rendimiento.  
  
V1.8.3  
---  
- Se agregó la vista de cuadrícula en el selector de nodos de chat del servicio rápido de Motrix  
- Se agregó opción para habilitar/deshabilitar los mensajes no leídos en el nodo del árbol izquierdo  
- Se agregó opción para desactivar el desplazamiento automático al escribir  
- Se corrigió el problema de que no se puede seleccionar la aplicación al hacer clic en el icono de la barra lateral  
- Se corrigió el problema de que algunos textos en varios idiomas no se traducen  
- Se corrigió el problema de bloqueo en el modo de voz en algunos casos  
  
  
V1.8.2  
---  
- Se agregó soporte para la aplicación Shortcuts (macOS 13.0+). Consulta la preferencia de la aplicación para ver cómo usarla  
- El servicio rápido de Motrix ahora puede mostrar una ventana emergente pequeña para mostrar el contenido de la respuesta de AI  
- Se corrigió el problema de que el servicio de Motrix no se puede mostrar en el navegador u otras aplicaciones de texto  
  
  
V1.8.1  
---  
- Se corrigió el problema de que a veces la búsqueda global no muestra los datos  
- Se corrigió el problema de que los planes pro aún limitan algunas funciones  
- Se corrigió el problema de altura incorrecta del cuerpo del mensaje  
  
V1.8  
---  
- Agregue un temporizador diario para solicitar automáticamente un nodo de chat de AI para mostrar consejos inspiradores o motivacionales, o puedes usarlo para mostrar automáticamente un consejo de programación diario o práctica de idiomas (Doble clic en la fila de pregunta del usuario)  
- Agregue un temporizador diario que se puede invocar directamente desde el menú contextual de la barra de menú Motrix  
- Agregue el acceso directo global CMD+SHIFT+F para cambiar rápidamente a la búsqueda global de favoritos  
- Corregir problemas de desplazamiento  
- Corregir problemas de selección de plantilla emergente que a veces no permite insertar texto  
- Mejoras de rendimiento en el modo de transmisión  
  
  
Funciones de V1.7  
---  
- Agregue el modo de ventana flotante para crear un panel flotante pequeño  
- Agregue la capacidad de arrastrar texto a cualquier área de la ventana de chat para enviar mensajes  
- Agregue el interruptor de presentación de diseño en la barra de herramientas principal y la opción de restaurar el icono de diseño personalizado  
- Agregue el servicio rápido de Motrix, cuando esté en otra aplicación de edición, seleccione cualquier texto y seleccione "Motrix Quick" para mostrar el selector de nodos de chat y enviar el texto seleccionado al sistema de chat  
- Agregue el menú contextual derecho del mouse en el mensaje para copiar, añadir a favoritos o editar rápidamente  
- Corriga el problema de estabilidad del desplazamiento  
- Corrija el problema de nueva línea en el renderizado de Markdown  
  
Funciones de V1.5~1.6  
---  
- Agregue el modo de transmisión para obtener los tokens de respuesta uno por uno  
- Edite el mensaje incrustado al hacer doble clic en la fila del mensaje  
- Agregue la configuración de apariencia en las preferencias para personalizar la interfaz de usuario  
- Agregue 3 nuevos temas con soporte claro/oscuro  
- Agregue la función de guardar y restaurar el diseño (incluido el tema actual, la elección entre claro/oscuro, el tamaño de fuente y las opciones automáticas, etc.)  
- Agregue la opción de animación de escritura  
- Agregue el servicio de texto del sistema para llamar a la API de Motrix en cualquier otro editor de texto del sistema  
- Correcciones y pruebas de compatibilidad de Mortix con macOS 11.0 y 12.0  
- Correcciones de errores y mejoras de rendimiento  
  
Funciones de V1.4  
---  
- Soporte de búsqueda en todas las conversaciones  
- Modo de selección en lote compatible. seleccione mensajes de chat para compartir o exportar  
- Mostrar favoritos en todas las conversaciones (dentro del menú de búsqueda)  
- Personalice el máximo de tokens para cada nodo (debes saber cómo funcionan, como los mensajes de contexto, esto puede afectar cuánto contexto conoce AI)  
- Modos de entrada predeterminados personalizados para cada nodo  
- Correcciones de errores y mejoras de rendimiento  
  
Funciones de V1.1~V1.3  
---  
- Modo de voz: puedes usar el micrófono para grabar texto. La aplicación lo traducirá a texto y mantendrá la pista de audio.  
- Habla el contenido: haz clic en el avatar del usuario o bot.  
- Modo de chat grupal: puedes establecer un nodo principal y agregar algunos nodos secundarios (debes usar las instrucciones del sistema para inicializar el rol AI y su papel), luego enviar mensajes en el nodo principal y todos los secundarios responderán en la conversación actual.  
- Portapapeles automático: copia automáticamente el contenido al portapapeles cuando haya una respuesta  
- Voz automática: reproduce automáticamente la respuesta  
- Máscara automática: enmascara automáticamente la respuesta de AI. Esto es principalmente para usuarios que desean practicar la dicción en varios idiomas.  
  
Funciones de V1.0  
---  
- Editor Markdown integrado  
- Agrupación libre de nodos de chat con estilo de árbol (compatible con arrastrar y soltar)  
- 3 temas con soporte de colores claros y oscuros  
- Renderizado de bloque de código con colores  
- Guardar cualquier conversación para su revisión o consulta posterior  
- Conversaciones guardadas en local, para poder verlas sin conexión  
- Plantilla de prompt personalizada y ventana emergente rápida con "/"  
  
  
Capturas de pantalla  
  
![captura de pantalla](images/screenshot.webp)  
  
![captura de pantalla1](images/screenshot1.webp)  
  
![captura de pantalla2](images/screenshot2.webp)  
  
![captura de pantalla3](images/screenshot3.webp)  
  
![captura de pantalla4](images/screenshot4.webp)  
  
![captura de pantalla5](images/screenshot5.webp)  
  
![captura de pantalla6](images/screenshot6.webp)  
  
![captura de pantalla7](images/screenshot7.webp)  
  
![captura de pantalla8](images/screenshot8.webp)  
  
![captura de pantalla9](images/screenshot9.webp)  
  
![captura de pantalla10](images/screenshot10.webp)  
  
![captura de pantalla11](images/screenshot11.webp)