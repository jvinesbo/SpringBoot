# SpringBoot
Integración continua con Spring boot

## 1 Instalación de la máquina virtual vagrant.

### 1.1 Requisitos

* [Instalar vagrant](https://www.vagrantup.com/downloads.html)
* [Instalar virtual box](https://www.virtualbox.org/wiki/Downloads)

## 2 VagrantFile

Fichero con la configuración de la máquina virtual. Este fichero contiene todo el software necesario para poder iniciar la tarea de desarrollo de aplicaciones Spring Boot con integración continua.

[Comandos básicos Vagrant](http://albertoromeu.com/7-comandos-vagrant/). Para más información consultar la [documentación oficial](https://www.vagrantup.com/docs/cli/) de Vagrant.

* PostgreSql 
  * (__Usuario:__ brazal)
  * (__Contraseña:__ brazal1234)
  * (__Host:__ 127.0.0.1)
* MySql
  * (__Usuario:__)
  * (__Contraseña:__)
  * (__Host:__)
* SmartGit (__Applications > Development > SmartGit__)
* Java JDK 8
* Eclipse Neon (__/opt/eclipse__)
* DBeaver (__Applications > Development > DBeaver CE__)
* Tomcat (__/opt/tomcat__)
* Maven
* Node (__sudo apt-get install nodejs && sudo apt-get install npm__)
* Jenkins (__http://193.168.33.20:8080/login__)
* Angular Cli (No se puede instarlar cuando se ejecuta el fichero vagrant. Si es necesario instalarlo se debe ejecutar el comando __npm install @angular/cli__)
* Firefox (__Applications > Internet > Firefox Web Browser__)

### 2.1 Primera ejecución del fichero Vagrant

1. Descargar el fichero __Vagrantfile__ y alojarlo en el directorio que de desee.
2. Abrir un terminal y colocarnos en el directorio donde se ha colocado el fichero __Vagrantfile__.
3. Ejecutar el comando __vagrant up --provision__ (La primera ejecución del fichero es larga ya que tiene que descargar todo el software e instalarlo.)
4. Una vez a terminado la ejecución del comando vagrant se abre una máquina virtual virtualbox. 
    * __Usuario:__ vagrant 
    * __Contraseña:__ vagrant

Al iniciar la máquina virtual es posible que no se muestre el escritorio. Para que se muestre el escritorio se debe ejecutar el comando __sudo startxfce4&__.

## 3 Configuración del entorno de desarrollo

Para realizar la configuración del entorno de desarrollo es necesario seguir el [documento]() del repositorio.

## 4 Arrancar aplicación
