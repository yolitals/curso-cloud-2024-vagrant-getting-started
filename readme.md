# Vagrant

## Preparación del ambiente

- Descargar e instalar hipervisor
  - [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  
  - [VMWare fusion (Utilizar en Mac m1)](https://customerconnect.vmware.com/en/evalcenter?p=fusion-player-personal-13): Es necesario crear una cuenta para poder obtener una licencia personal.
  
- Para VMWare Fusion es necesario descargar e instalar VMWare utility
  - [VMWare utility](https://www.vagrantup.com/docs/providers/vmware/vagrant-vmware-utility)
  - Crear un link simbolico:
  
    ```sh
    ln -s /Applications/VMWare\ Fusion\ Tech\ Preview.app /Applications/VMWare\ Fusion.app
    ```

- Descargar e instalar Vagrant
  - [Vagrant](https://www.vagrantup.com/downloads)

- Instalar plugin de hipervisor
  
  (*) Revisar indicaciones especiales para mac con chip M1.
  
  ```sh
  vagrant plugin install vagrant-[PROVIDER]
  ```

  Reemplazar _PROVIDER_ por:
  - VirtualBox -> vbguest
  - VMWare fusion -> vmware-desktop

### Indicaciones especiales Mac M1

- Instalar Rosetta
  
  ```sh
  /usr/sbin/softwareupdate --install-rosetta --agree-to-license
  ```
  