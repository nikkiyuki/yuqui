# yuqui

1.Desde la línea de comandos, copia el repositorio a la ubicación deseada utilizando el siguiente comando: git clone ruta https://github.com/nikkiyuki/yuqui.git

2.Navega hasta la carpeta donde se realizó la clonación utilizando el comando cd "nombre_carpeta".

3.Dirígete a la carpeta llamada "Truco Concurso" con el comando cd Truco Concurso.

4.Luego, entra en la siguiente carpeta con el comando cd Truco Concurso.

5.Dentro de esta carpeta, encontrarás una subcarpeta llamada "front" y un archivo llamado "main.ft". Dentro de "front" está todo el código de la página junto con su archivo Dockerfile. El archivo "main" es responsable de automatizar la creación de una máquina virtual en AWS (requiere credenciales) y la creación de los contenedores. Asegúrate de tener configuradas las credenciales de AWS desde la CLI.

6.Necesitarás generar un par de claves con el nombre "llaveIac" y un tamaño de 4096 en la carpeta ".ssh". Para hacer esto, primero navega hasta la carpeta ".ssh" con el comando cd ~/.ssh, luego crea el par de claves usando ssh-keygen -b 4096, y finalmente, asegura los permisos adecuados con chmod 400 llaveIac y chmod 400 llaveIac.pub. Para salir de la carpeta, usa el comando cd ...

7.Una vez dentro de la carpeta "ProyectoFinalTelematica", ejecuta el archivo "main" con los siguientes pasos:

    Navega hasta la ubicación del archivo utilizando el comando cd "carpeta donde clonaste el repositorio"/PF_telematica/ProyectoFinalTelematica.
    Ejecuta los siguientes comandos en orden:
        terraform init
        terraform fmt
        terraform validate
        terraform apply
        terraform destroy (si deseas eliminar la infraestructura)
