# 1. Instalación de GitLab.
Vamos a realizar la instalación de GitLab, así como su configurador. En este ejemplo se usara una maquina Ubuntu 20.

## 1.1 Actualizar.
Primero vamos a actualizar tanto las librerías como el sistema para esto vamos a usar el siguiente comando.
```
 -> sudo apt update && sudo apt upgrade
```

![01-update-upgrade](capturas/01-update-upgrade.png)

1.2 Instalación paquetes.
Vamos a instalar una serie de paquete necesarios para instalar GitLab en nuestro sistema, para esto realizamos el comando en nuestra maquina.
```
 ->   sudo apt install -y vim curl ca-certificates apt-transport-https
```

![02-dependiencias](capturas/02-dependiencias.png)

1.3 Instalar GitLab.
Primer para instalar GitLab realizamos un curl como el siguiente:
```
 -> curl -s https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh | sudo bash
```

![03-install](capturas/03-install.png)

y ahora si realizamos la instalación .
```
 ->  sudo apt install gitlab-ce
```

![04-install-gitlab](capturas/04-install-gitlab.png)


Comprobamos que al final nos muestro lo siguiente para asegurarnos de que se ha instado.

![05-gitlab-instalado](capturas/05-gitlab-instalado.png)

Con GitLab instalado deberemos realizar el siguiente comando para dejar configurado la herramienta.
```
 ->  sudo gitlab-ctl reconfigure
```

![06-gitlab-config](capturas/06-gitlab-config.png)


Y al final veremos algo como esto.

![06-gitlab-config02](capturas/06-gitlab-config02.png)

1.4 Acceso.
Ahora ya tenemos instalado el GitLab vamos a acceder por medio de la ip.ip a

![07-comprobacion](capturas/07-comprobacion.png)


Ahora para acceder deberemos poner el usuario “root” y la contraseña que se encuentra en la carpeta que te avisa al terminar la configuración. En este caso estaba en “/etc/gitlab/initial_root_password”.

![08-acceso](capturas/08-acceso.png)