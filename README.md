ClasedeGitHUb
=============

Ejemplo de GiHUb by chuko thanks to #Mejorandola


Comandos APrendidos en CLase
Very importan commands



Install GIT First

Then


$ git config --global user.name "yourusername"
$ git config --global user.email "your@email.com"

Creamos clave SSH

$ ssh-keygen
Si queremos el mismo lugar damos enter sino escribimos la direccion
Pide escribir Clave para mas seguridad agregar una (solo por sugerencia)

SAle algo parecido
Your identification has been saved in /c/Users/user001/.ssh/id_rsa.
Your public key has been saved in /c/Users/User001/.ssh/id_rsa.pub.
The key fingerprint is:
2c:75:a3:cc:e3:d9:92:94:59:b0:ae:c4:9b:dc:ac:e7 user001@Z470

Para ver la clave creada y poder usarla en github para conectarnos usamos lo siguiente

$ cat ~/.ssh/id_rsa.pub
Sale algo parecidoa esto
ssh-rsa AAAAB3NzaC1yc2EAAAABIwAAAQEA8cLuGpvz3IKvrP6iCrKYDOVw2Iuz
5hCVikjhSXmmcNfx7fGXa0H3TyX+Mi51idNbcGe0CRDFzwhCEoUI29myS3rQqlLHPHvzb9J1
2j2fHpBC5jt7wJu6QkJNohU9No62dfaKF2MBXY99e1Mw+2gjb42C+wy
Z/Xxwy6DSNbAFfjeQgsRypDdcqnCF+0O8xOJ/8FnAzMxdALx9e2D5VhgRZi2Vyvo0x8RnxF8
QtYNFPbFdtDnn239cBU2kNumF+wLBHjUaA6s0sJgn6AnRGcX/kF0DgQ4vQ== User001@Z470
(obvio modificado por seguridad) Pero sale algo parecido

Crear Carpeta donde descargare el proyecto
$ mkdir ClaseGitHUb
$ cd ClaseGitHUb

Arracando proyecto
$ git init
Initialized empty Git repository in c:/Users/User001/Documents/ClaseGitHUb/.git/

crear archivo
$ touch README

Agregas
$ git add README

Verificar el status de proyecto
$ git Status


Primer commit 
$ git commit -m "mi primer archivo desde mi pc"

Aqui te coenctas remotamente al proyecto que quieras en este caso a la clase de github
$ git remote add origin git@github.com:xtornasol512/ClasedeGitHUb.git

Trae todo el contenido del poryecto elegido
$ git pull origin master
Pide autenticidad si pusiste clave a tu llave ssh


Este comando sube el archivo a gitHUB
$ git push origin master
Tambien pide autencidad volver a poenr clave ssh  