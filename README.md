This compressed folder contains a repository with 3D models of traffic signs from the UE, particulary Spain, that can be referenced in a Gazebo environment in order to include such models. 
The method is simple:
1-Extract original .zip folder and locate it where you prefer in your computer, it is however recommended to place it at the same level as your .world file or in a model folder where the 
rest of repositories are located.
2-Reference the path absolute or relative (not recommended) to Gazebo. This can be done in multiple ways:
  2.1. In the hidden folder .gazebo/ini.gui
  2.2  In the graphic interface with the insert option that appears when editing a world
  2.3  Exporting directly to Gazebo's environment variable with export command
The path has to reach the folder senales which is in the first level of biblioteca_senales_v3

In case modifications of the models would be required, several readme.txt files are distributed along the directory tree to explain what every file does.


Esta carpeta comprimida contiene un repositorio con modelos 3D de señales de trafico verticales de la Unión Europea, particularmente siguiendo la norma española, de tal forma que puedan ser 
incorporadas en un mundo de Gazebo. Para que Gazebo pueda acceder y cargar estos modelos hay que seguir los siguientes pasos:
1- Descomprimir la carpeta y ubicarla donde se prefiera. Recomendación: en el mismo nivel que el archivo .world o en una carpeta donde estén el resto de repositorios locales.
2- Referenciar la ruta a Gazebo. Hay varias formas
  2.1 En la carpeta oculta .gazebo en el archivo /ini.gui
  2.2 En el interfaz gráfico de Gazebo en el apartado insert que nos guia interactivamente en nuestro arbol de directorios
  2.3 Añadiendolo directamente a la variable de entorno de Gazebo con el comando export
La ruta debe llegar al nivel senales que esta en el primer nivel de biblioteca_senales_v3
