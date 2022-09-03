# CRUD

## CRUD es el acrónimo de: “Create”, “Read”, “Update” y “Delete”

>**Crear - Leer - Actualizar - Borrar**  

<br>
Son las funciones básicas para el tratamiento de datos ordenados.       

<br>

## Métodos en Javascript para realizar CRUD en un array de datos

>Create:

        newData = {dato1:”algo”,
                    dato2:”algo”}
        -------------------------
-       --> array.push(newData)
-		--> array.unshift(newData)

>Read: 	

-       console.log(array)

-		array.forEach(e =>{
            console.log(e)
        })

-		for (let i=0; i < arr.length; i++){
            console.log(arr[i])
        }

-       let pos = arr.findIndex(e => e.some === some)
        console.log(arr[some])


>Update: 	
-       let pos = arr.findIndex(e => e.some === some)
        array[pos] = newData

>Delete: 	

-       array.pop()
-		array.shift()
-       let pos = arr.findIndex(e => e.some === some)
		array.splice(pos,1)


<br>
<br>
<br>


# Comandos de la terminal
### Mostrar  
- ls  **(lista los archivos de la carpeta)**  
- ls - **(lista los archivos de la carpeta incluyendo ocultos)**  
- ls -l **(muestra toda la inf de la carpeta (usuario, grupo, permisos, etc))**  
- ls -R **(lista los archivos y carpetas de manera recursiva)**  
- pwd **(Muestra la ruta donde se encuentra)**  
- more [nombre-arch] **(muestra contenido de un archivo)**  

<br>

### Crear  
- mkdir [carpeta] **(crea un directorio o carpeta)**
- touch [nombre archivo] **(crea un nuevo archivo)**

<br>

### Eliminar  
- rm [nombre del archivo] **(elimina un archivo)**  
- rmdir [nombre de la carpeta] **(elimina una carpeta)**
- rm -r [nombre de la carpeta] **(elimina una carpeta y su contedido)**  

<br>

### Copiar/Mover/Renombrar  
- mv [ruta/arch1] [ruta/arch2] **(renombra archivos {si arch2 existe es sobreescrito})**  
- mv [ruta/carpeta1] [ruta/carpeta2] **(renombra carpeta1 como carpeta2 {carpeta2 NO debe existir})**  
- mv [ruta/carpeta1] [ruta/carpeta2] **(mueve el contenido de carpeta1 a carpeta2 {carpeta2 debe existir})**  
- cp [ruta/arch1] [ruta/arch2] **(copia un archivo o una carpeta)**  
##### **con la opción -r se indica que copie recursivamente el contenido de la carpeta**

<br>

### Navegación entre carpetas  
- cd .. **(sube un nivel de carpeta)**
- cd **(cambia de carpeta)**  

<br>

### Otros Comandos  
- clear **(limpia la pantalla)**
- comando --help **(muestra ayuda del comando)**