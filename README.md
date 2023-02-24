# Remember-me

## PASOS PARA RESOLVER EL CHECKPOINT:

### 📌 1. FORK y CLONE

Primero debes forkear este repo, haciendo click en el botón fork de arriba a la derecha.No cambiar el nombre del repositorio.
Elegir el boton Code arriba a la derecha y copiar la URL.

Abrir Git Bash y elegir en que carpeta de mi maquina se clonará. Luego ejecutar git clone [URL copiada].Enter y chequear que se clonó.

Una vez clonado, abrir Visual Studio Code,Open Folder, entrá a esa carpeta y empezar a resolver.

### 📌 2. RESOLVER EL CHECKPOINT

Tu tarea es completar el código en checkpoint.py de tal forma que pasen la mayoría de los tests. 
Ejecutar los siguientes comandos:

    python tests.py

### 📌 3. ENTREGAR TU CHECKPOINT

Correr los tests y verificar cuantos pasan. Ten en cuenta que si te aparece "1 failed;1 total" es porque tienes un error de sintaxis: seguramente falta o sobra un corchete, paréntesis, dos puntos, etc. Saca un print de pantalla de tus tests. 

Luego, debes subir un commit a tu repo. Para hacerlo, debes ejecutar el siguiente comando en la Terminal de Visual Studio Code:

    git add .
    git commit -m "checkpoint"
    git push 

Una vez finalizado, chequea:

1. Que veas los cambios reflejados en el repo de tu cuenta de github (entrando a tu repo desde el browser.)
2. Que no haya un require - solo debe haber codigo dentro de las funciones de cada ejercicio

⚠️ Atención: no debes realizar un commit después de la hora de entrega porque se anulara la totalidad del examen.

## 🔎 GUIA DE ERRORES COMUNES

Para identificar el error, vas a tener que leerlo en la consola.

1. 1 failed, 1 total:

    Tenes un error de sintaxis. Revisa el último ejercicio que hayas hecho, seguramente falta o sobra un corchete, paréntesis, dos puntos, etc.
    
2. Author identity unknown.

    a. Intenta ejecutar los siguientes comandos para configurar tu cuenta:

          git config --global user.name "Tu usuario de GitHub aca"
          git config --global user.email "Tu email aca"
          
     b. Ingresa a 🔗 [Github](https://docs.github.com/es/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) y sigue las instrucciones para configurar tu token.
     
     c. La consola se tilda en Runs:

          Revisa tu código, tenes un bucle infinito. Tenes que checkear la condición de corte de tus bucles.
          
    ❗️ Importante: No modificar ni el nombre ni los argumetos que reciben las funciones, sólo deben escribir

# 💡 Recordar utilizar la ruta relativa, no la absoluta para ingestar los datos desde los CSV

EJ: 'datasets/xxxxxxxxxx.csv'
