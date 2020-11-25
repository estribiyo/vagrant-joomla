# vagrant-joomla

**IMPORTANTE!** Sólo se ha probado correctamente con las versiones de VirtualBox especificadas. Con versiones superiores fallaba.

## Instalación

### Windows

- https://download.virtualbox.org/virtualbox/6.0.14/VirtualBox-6.0.14-133895-Win.exe
- [Extension Pack 6.0.14](https://download.virtualbox.org/virtualbox/6.0.14/Oracle_VM_VirtualBox_Extension_Pack-6.0.14.vbox-extpack)

### Linux

- [https://download.virtualbox.org/virtualbox/6.0.14/virtualbox-6.0_6.0.14-133895\~Debian\~buster_amd64.deb](https://download.virtualbox.org/virtualbox/6.0.14/virtualbox-6.0_6.0.14-133895~Debian~buster_amd64.deb)

### Plugins

    vagrant plugin install vagrant-vbguest
    vagrant plugin install vagrant-hostmanager

## Configuración

### config.custom.yaml

Editaremos este fichero para adaptar las rutas de proyectos preexistentes.



## Funcionamiento

Inicializamos:

    vagrant init joomlatools/box

Arrancamos:

    vagrant up
