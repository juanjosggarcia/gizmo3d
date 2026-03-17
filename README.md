*** He usado una Oculus Meta Quest 2 para el desarrollo y las pruebas ***

1. Se desarrollaron varios cubos que implementan distintas interfaces para distintas interaciones del usuario que se mantienen dentro de la carpeta "Blueprints", pero el realmente importante y que contiene lo diseñado para este proyecto son los 'BP_EditableCone', 'BP_EditableCylinder', 'BP_EditableCube', 'BP_EditableSphere', que son copias solo cambia la malla, y para los gizmos el 'BP_Gizmo'

2. En GVR_Pawm esta la logica de las distintas entradas de informacion, y hay 3 variables publicas a destacar que son:
* ShowRayCastingLaser, activa la visualizacion del rayo laser de depuracion, por defecto desabilitado.
* EnableOnlyOneButtonHandler, que sirve para que aparezca el menu al selecionar una figura y asi poder hacer todo con un dispositibo con un solo boton,
* MotionSpeed, que es el numero por el que se multiplicara para moverse por el entorno a saltos
* Enable2DMode, que sirve para que el menu sea en 2D para su uso en el editor o dispositivos sin VR
