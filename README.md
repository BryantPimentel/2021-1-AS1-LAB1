# Laboratorio #1
## Datos Personales 📄
**Facultad de Ingeniería en sistemas**

**Curso:** Análisis de Sistemas. 

**Catedrático:** Ing. Josué Barillas

**Nombre:** Bryant Josué Pimentel Garcia

**Carne:** 1290-18-5715

# UML sobre las compras de boletos de los buses extraurbanos

### Instalación 🔧
_Primero tenemos que hunicarnos en donde deseamos descargar el proyecto ya situados dentro de la carpeta que deseamos tener el proyecto
colocamos el siguiebte ejemplo: git push URL del proyecto_


```
git push https://github.com/BryantPimentel/2021-1-AS1-LAB1.git
```

## Inicializar el proyecto desde 0 ⚙️

_Seguimos los siguientes pasos:_

_Inicializamos el proyecto_
```
git init 
```
_Creamos el archivo README.MD_
```
git add README.md
```
_Agregamos el primer comentario_
```
git commit -m "first commit" 
```
_Le indicamos la bracnh que queremos inicializar_
```
git branch -M main 
```

_Indicamos que queremos el control remoto del repositorio, "git remote add origin URL del proyecto ejemplo":_
```
git remote add origin https://github.com/BryantPimentel/2021-1-AS1-LAB1.git
```
_Hacemos la primera subida al proyecto (carpeta vacia)_
```
git push -u origin main 
```

## Hacemos el PUSH al proyecto  🔩

_Verificamos si hay cambios o no, si hay cambios nos pasamos al paso 2:_

```
git status
```
_Tenemos que agregar todos los cambios:_

```
git add .
```
_Luego hacemos el COMMIT con un comentario:_

```
git commit -m "Segundo commit" .
```
_Luego de tener todo listo para subir, colocamos el push y le indicamos en que branch queremos hacer el push:_

```
git push -u origin main .
```
### Hacer PULL al proyecto ⌨️

_Dentro la linea de comandos nos situamos donde tenemos el proyecto
al ya estar situados en la carpeta colocamos el siguiente comando:_

```
git pull origin master
```
_El cual nos ayuda actualizar el proyecto con la branch especifica que deseamos_
