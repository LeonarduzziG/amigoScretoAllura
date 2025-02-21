# amigoScretoAllura
# Proyecto: Sortear Amigos

Este es un proyecto simple que permite a los usuarios agregar nombres a una lista de amigos, mostrar la lista y sortear un amigo aleatoriamente de la lista. Es una aplicación web básica en JavaScript, HTML y CSS.

## Descripción

La aplicación permite:
1. **Agregar amigos**: Los usuarios pueden ingresar el nombre de un amigo y agregarlo a una lista.
2. **Mostrar lista de amigos**: La lista de amigos se muestra en tiempo real.
3. **Sortear un amigo aleatoriamente**: Se puede seleccionar un amigo aleatoriamente de la lista mediante un sorteo.

## Instalación

Este proyecto no requiere ninguna instalación especial. Solo necesitas un navegador web moderno. Para usarlo en tu entorno local, sigue los siguientes pasos:
Cómo ejecutar el proyecto
Abrir el archivo HTML:

Si estás trabajando en un editor de código o un entorno de desarrollo, abre el archivo index.html.
Si deseas ver la aplicación en un navegador, solo abre el archivo index.html directamente desde tu explorador de archivos.
Uso de la aplicación:

Ingresa un nombre en el campo de texto.
Haz clic en "Agregar Amigo" para añadir un amigo a la lista.
Haz clic en "Sortear un Amigo" para elegir un amigo aleatoriamente de la lista.
Funcionalidades
Agregar Amigo: Permite agregar un nombre al array amigos. Si el campo está vacío, se muestra una alerta pidiendo al usuario que ingrese un nombre.
Mostrar Amigos: Muestra la lista de amigos en un formato de lista (<ul>), actualizándola cada vez que se agrega un nuevo amigo.
Sortear un Amigo: Selecciona aleatoriamente un amigo de la lista y muestra el nombre del amigo sorteado en un elemento h3.
Posibles Problemas y Soluciones
1. El sorteo no funciona si no hay amigos:
Si la lista de amigos está vacía, la función de sorteo mostrará una alerta diciendo que no hay amigos para sortear. Asegúrate de agregar al menos un amigo antes de intentar realizar un sorteo.
2. Los amigos no se muestran correctamente:
Si la lista de amigos no se muestra, asegúrate de que el código JavaScript esté vinculado correctamente al archivo HTML y que no haya errores en la consola del navegador. Para verificar los errores, abre las herramientas de desarrollo de tu navegador y revisa la pestaña "Consola".
3. Problemas con el navegador:
Este proyecto debería funcionar en la mayoría de los navegadores modernos (Chrome, Firefox, Edge). Si encuentras un problema en un navegador específico, intenta actualizarlo a la última versión disponible.
