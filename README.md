# PRUEBA #1 BIMESTRE 
## _Integrantes: ✒️_ 
```
* Karla Chinacalle
* Xavier Calle
* Gabriel Salgado
```
_Se presenta como se realizó la app nativa en Android Studio sobre un directorio de contactos._   
_CRUD implementado en firebase y Login respectivamente_  
## Creación de proyecto en firebase   
Se crea proyecto en firebase _androidClase_ y le otorgamos permisos de autenticación.
 ![image](https://drive.google.com/uc?export=view&id=1eSp9Fb-vREWWmgQbhI4KAHMA3un2TUa_)
    
    
## Diseño Layout 📃
```
En el diseño de las pantallas se lo realizo con 4 archivos .xml en el directorio layout.   
* activity_adap_usuario.xml - Los campos que contiene cada objeto del directorio.   
* activity_auth.xml - En este acreen se realiza el diseño de login 
* activity_home.xml - Aquí se realizara todo el proceso de CRUD y sus botones.   
* activity_register.xml - Screen de registro de usuarios.
```
 ![image](https://drive.google.com/uc?export=view&id=1d1VURzW4-KzQ86_0UHZn3_7_30ILdeiY)

## Creación de funciones✏️
En el directorio java se crearon las clases respectivamente de cada screen y adicional la clase _Usuario_ que contiene los atributos del objeto a guardar.   
![image](https://drive.google.com/uc?export=view&id=1hLCzfZM4mhYuGA-82WetQNIem_-KfQTl)


### Variables utilizadas en el home para el CRUD:   
![image](https://drive.google.com/uc?export=view&id=1SDzjL7kXqtygQOf0MOZKmc4603PQj5P9)

 
### Nuestro proyecto consta de 4 funciones principales en el Home.java:   

* **btnAgregar.setOnClickListener(view -> agregarUsuario());** - Esta función agrega al direcotirio la información del contanto ingresado.   
* **btnEditar.setOnClickListener(view -> editarUsuario());** - Aquí toma el id del usario y lo edita, una vez ingresado los nuevos datos los guarda.   
* **btnEliminar.setOnClickListener(view -> eliminarUsuario());** -Toma el usuario que se deasea eliminar y lo remueve.      
* **btnConsultar.setOnClickListener(view -> obtenerUsuarios());** - La función permite leer los contactos en nuestro directorio.   


## Test de ejecución ✅
### Login 🔑
![image](https://drive.google.com/uc?export=view&id=1UFDZEanPuF_NGvO3QAykQTaoCEDD5A7Q)
### Agregar contacto a directorio.
![image](https://drive.google.com/uc?export=view&id=1mEmRfeuUXeCJf30vT21Y2fA9GZNvc6Y6)

## _GRACIAS POR SU VISITA_ 👌
