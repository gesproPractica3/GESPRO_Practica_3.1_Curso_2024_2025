
A continuación voy a describir los siguientes pasos para llevar a cabo el cambio, subida y actualización de archivos
tanto en github, como en kraken.

1- posicionarse en commit del gitkraken original y hacer un hard discard para ponerlo en modo local con tu contenido
2- asegurarse de estar al día en master y todos los hilos(github y gitkraken)
3- crear rama a partir de la tarea del archivo inicial (en este caso go bees)
4- ir a la rama local y crear un branch (en github)
5- se copian los archivos de inicio en la carpeta del proyecto local (sin .git)
6- git stash all + commit (actualizar y crear branch en gitkraken, haciendo un stage all changes)
7- git fecth all(para asegurar estar al día en gitkraken)+ git pull (para bajar todo de github a local)
8- fetch y pull finales en gitkraken desde el branch creado
