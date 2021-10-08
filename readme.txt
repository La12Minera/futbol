Hola!
Boca campeón


LISTA DE COMANDOS BÁSICOS
ls: Listado de carpeta y archivos
cd /: Cambiando de ubicación (Ejemplo cd carpeta1/)
cd ..= Para volver a la carpeta anterior
mkdir: Creando una carpeta
rm -rf: Eliminando archivos y carpetas
mv: Moviendo acrchivos y carpetas
cp: copiando archivos y carpetas 
cls o clean: Limpiar pantalla
pwd: Nos indica donde estamos parados
touch: Crear un archivo 
code ..= Para abrir el Visual Basic Code


Crear una nueva rama: git checkout -b Fede_feature master
    El -b indica que la cree si no existe y de este modo pasara automaticamente a esta nueva rama.
    Fede_feature: es el nombre de la rama
    master: arranque de master
    De esta forma cambia al nuevo branch

Borrar archivos que no quiero: rm -rf 'no sirve.txt'
    no sirve: es el nombre del archivos

Visualizar como esta el proyecto en el momento: git status
    Para que se rastree es necesario aplicarle commit:
        git commit -am "Delete files"
        