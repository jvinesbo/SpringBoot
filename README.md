# SpringBoot
Integración continua con Spring boot

## 1 Instalación de la máquina virtual vagrant.

### 1.1 Requisitos

* [Instalar vagrant](https://www.vagrantup.com/downloads.html)
* [Instalar virtual box](https://www.virtualbox.org/wiki/Downloads)

## 2 VagrantFile

Fichero con la configuración de la máquina virtual. Este fichero contiene todo el software necesario para poder iniciar la tarea de desarrollo de aplicaciones Spring Boot con integración continua.

[Comandos básicos Vagrant](http://albertoromeu.com/7-comandos-vagrant/). Para más información consultar la [documentación oficial](https://www.vagrantup.com/docs/cli/) de Vagrant

* PostgreSql
* MySql
* SmartGit
* Java JDK 8
* Eclipse Neon
* DBeaver
* Maven
* Node
* Bower
* Jenkins
* Angular Cli
* Firefox

### 2.1 Primera ejecución del fichero Vagrant

1. Descargar el fichero __Vagrantfile__ y alojarlo en el directorio que de desee.
2. Abrir un terminal y colocarnos en el directorio donde se ha colocado el fichero __Vagrantfile__
3. Ejecutar el comando __vagrant up --provision__ (La primera ejecución del fichero es larga ya que tiene que descargar todo el software e instalarlo.)
