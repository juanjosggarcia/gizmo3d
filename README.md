*** He usado una Oculus Meta Quest 2 para el desarrollo y las pruebas ***

1. Se desarrollaron varios cubos que implementan distintas interfaces para distintas interaciones del usuario que se mantienen dentro de la carpeta "Blueprints", pero el realmente importante y que contiene el Fuze Button y el Click como se solicita para esta practica es el que se llama "BP_InteracticeCube" y que tambien es el unico que aparece en el mapa "EntryLevel"

2. En GVR_Pawm esta la logica de las distintas entradas de informacion, y hay 3 variables publicas a destacar que son:
* MaxFuseTime, es la variable que controla el tiempo que hay que permanecer apuntando para que salte el Fuse Button, por defecto 2 segundos
* EnableMouseHandlers, que sirve para habilitar la interacion de pantalla avanzada con el raton permitiendo no solo detectar las pulsaciones del boton sino tambien el curson y su movimiento, por defecto desabilitado.
* ShowRayCastingLaser, activa la visualizacion del rayo laser de depuracion, por defecto desabilitado.

3. Se han añadido la barra de proceso circular que se solicita en la practica, ademas de un mira para saber donde estas apuntado realmente que es mas comoda que el propio layer de depuracion de unreal.