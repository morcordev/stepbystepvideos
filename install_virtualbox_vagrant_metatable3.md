Link necesarios:

#VirtualBox
https://www.virtualbox.org/wiki/Downloads

#Vagrant
https://developer.hashicorp.com/vagrant/install#windows

#Repositorio GitHub metaesploitable3
https://github.com/rapid7/metasploitable3

Comandos a utilizar:

mkdir metasploitable3-workspace

cd metasploitable3-workspace

Invoke-WebRequest -Uri "https://raw.githubusercontent.com/rap..." -OutFile "Vagrantfile"

vagrant u: tiempo aprox 2hrs dependiendo tu banda ancha de internet

Paso a paso:

1 -> Descargar e instalar VirtualBox
2 -> Descargar e instalar Vagrant
3 -> Ejecutar los comandos de configuración de metaesploitable3 (ir al link)
4 -> Ejecutar "vagrant up" y esperar que se levanten las maquinas virtuales
5 -> Luego de haber levantado las maquinas virtuales, ejecutar "sudo apt-get update" y "sudo apt-get upgrade" en respectivo orden, en la maquina ubuntu server
