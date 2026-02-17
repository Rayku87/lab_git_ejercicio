***Paso 1: Crear un repositorio local***

1º Uso el comando “pwd” que me muestra la ruta del directorio de trabajo actual en la terminal.

2º Creo un repositorio con el comando “ mkdir” llamado lab_git_ejercicio

3º Ingreso a la carpeta con el comando “cd”.

4º Inicializo el repositorio con el comando “git init”.

<img width="635" height="217" alt="image" src="https://github.com/user-attachments/assets/0f52d78b-3b18-4327-8a1f-306ed2ba1bd2" />

<img width="695" height="80" alt="image" src="https://github.com/user-attachments/assets/79305e91-0877-49ed-b1da-6fdbe374900b" />

***Paso 2: Subir el repositorio a GitHub***

1º Creamos el nuevo repositorio en remoto (GitHub).

2º Copiamos la URL del repositorio.

3º Conectamos mi repositorio local con el repositorio en remoto usando el comando “git remote add”, usamos un alias (origin) y añadimos la URL.

4º Verifico la conexión con el comando “git remote” o “git remote -v” para mayor detalle.

<img width="600" height="88" alt="image" src="https://github.com/user-attachments/assets/e12ed3cf-3b7c-4bb1-8682-951df8a78ffd" />

***Paso 3: Hacer un commit y un push***

1º Crear un archivo en la carpeta del repositorio: En File abro en folder, selecciono lab_git_ejercicio y accedo. Ya en visual studio code creo el archivo de nombre “fichero.txt”.

2ª Añado el archivo al staging: Con el comando “git add” y usando el nombre del archivo “fichero.txt”.

3º Crea un commit con un mensaje descriptivo: usando el comando “git commit -m” añadiendo además el mensaje descriptivo “Primer commit - archivo fichero agregado”.

4º Subo cambios a GitHub con el comando “git push -u origin master (master el nombre de la rama).

Extra: He usado el comando "git branch" para verificar la rama.

<img width="251" height="132" alt="image" src="https://github.com/user-attachments/assets/8b942ea8-601f-4de1-b1e1-b081c9931136" />

<img width="756" height="115" alt="image" src="https://github.com/user-attachments/assets/c43d4846-4ca5-4d6c-b8b5-04f924ef52c3" />

<img width="732" height="326" alt="image" src="https://github.com/user-attachments/assets/d77f2689-f686-4eee-b025-94188f6464e1" />

***PASO 4: Crea una rama***

1º Crea una nueva rama llamada development: uso el comando “git branch” y añado development.

2º Cambia a la nueva rama: uso el comando “git checkout” y añado development.

3º Realiza cambios en el archivo: uso el comando “echo” y añado la frase más el archivo “cambios realizado en development” >> fichero.txt

4º Añadir y hacer commit en development: uso git add.

5º Subir cambios a GitHub: uso git push -u origin development.

<img width="747" height="331" alt="image" src="https://github.com/user-attachments/assets/6bd5e5f0-86a5-4627-8fcd-72684afcd966" />

***PASO 5: Hacer una merge***

1º Vuelve a rama master: ejecuto git checkout master.

2º Hacer el merge de development en master: ejecuto git merge development.

3º No hay conflictos.

4º Subo los cambios a GitHub: ejecuto git push.

<img width="752" height="507" alt="image" src="https://github.com/user-attachments/assets/6fbb139a-3e23-4e54-9803-1258ec0eb964" />













