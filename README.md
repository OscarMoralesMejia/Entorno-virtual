# Entorno virtual para python
Este espacio podrás encontrar Cómo crear un entorno virtual para python paso a paso.

## Opción 1 Creación desde el simbolo de sistema de windows

Debemos considerar que ya tenemos instalado python junto con la libreria **virtualenv** si no la tienes instalada solamente utiliza el siguiente comando y lo ejecutas en el simbolo del sistema
```
pip install virtualenv
```

**Paso1.-** Teclea cmd en la opción de buscar en la barra de tareas de windows y abrir la aplicación

![image](https://github.com/OscarMoralesMejia/entorno_virtual/assets/159685580/d3b519fa-b9e4-4e5f-9d49-e63573e117bb)

**Paso 2.-** Ubicate en la carpeta donde quieres crear tu entorno virtual de python para este ejemplo nos ubicamos en projectsData

![image](https://github.com/OscarMoralesMejia/entorno_virtual/assets/159685580/a4fbb90a-a64d-4b84-87e8-0b501935c974)

**Paso 3.-** Tecleas el siguiente comando, tomando en cuenta que "miEntorno" es el nombre que deseas para tu entorno
```
Virtualenv miEntorno
```
![image](https://github.com/OscarMoralesMejia/entorno_virtual/assets/159685580/2ddb2dc8-f5f1-44ef-a786-0e598261d644)

**Paso 4.-** Ya puedes activarlo para trabajar en el e instalarle las librerias necesarias para tu proyecto con el siguiente comando

```
.\miEntorno\Scripts\activate
```
![image](https://github.com/OscarMoralesMejia/entorno_virtual/assets/159685580/b8a3fdb1-3ba4-46d4-8dcf-065e657b84fa)

Para desactivarlo lo puedes hacer con el siguiente comando
```
deactivate
```
![image](https://github.com/OscarMoralesMejia/entorno_virtual/assets/159685580/5a0f7797-cb1d-4a8a-8ed4-74fc2753d608)

**Paso 5.-** Podrás corroborar las librerias que tienes instaladas con el comando

```
pip list
```
![image](https://github.com/OscarMoralesMejia/entorno_virtual/assets/159685580/044e6a47-542d-4919-b0d5-45371124979b)





