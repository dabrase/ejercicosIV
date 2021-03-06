## David Brao Serrano

# Ejercicios Tema 5

## Ejercicio 1. Instalar los paquetes necesarios para usar KVM. Se pueden seguir estas instrucciones. Ya lo hicimos en el primer tema, pero volver a comprobar si nuestro sistema está preparado para ejecutarlo o hay que conformarse con la paravirtualización.

Para instalar KVM se hace mediante el siguiente comando:

```
aptitude install qemu-kvm libvirt-bin
```
![](capturas/tema5/ejer1.png)

Ahora comprobamos si nuestro sistema esta preparado para ejecutarlo con la orden **kvm-ok**

![](capturas/tema5/ejer1-1.png)

## Ejercicio 2. 

### 1. Crear varias máquinas virtuales con algún sistema operativo libre tal como Linux o BSD. Si se quieren distribuciones que ocupen poco espacio con el objetivo principalmente de hacer pruebas se puede usar CoreOS (que sirve como soporte para Docker); GALPon Minino, hecha en Galicia para el mundo; Damn Small Linux, SliTaz (que cabe en 35 megas) y ttylinux (basado en línea de órdenes solo).

Lo primero es activar KVM: `sudo modprobe kvm-intel`

Creamos una maquina virtual con SliTaz:

### 2. Hacer un ejercicio equivalente usando otro hipervisor como Xen, VirtualBox o Parallels.


## Ejercicio 3. Crear un benchmark de velocidad de entrada/salida y comprobar la diferencia entre usar paravirtualización y arrancar la máquina virtual simplemente con qemu-system-x86_64 -hda /media/Backup/Isos/discovirtual.img.


## Ejercicio 4. Crear una máquina virtual Linux con 512 megas de RAM y entorno gráfico LXDE a la que se pueda acceder mediante VNC y ssh.


## Ejercicio 5. Crear una máquina virtual Ubuntu utilizando el CLI de Azure e instalar en ella alguno de los servicios que estamos usando en el proyecto de la asignatura.


## Ejercicio 6. Instalar una máquina virtual con Linux Mint para el hipervisor que tengas instalado.


