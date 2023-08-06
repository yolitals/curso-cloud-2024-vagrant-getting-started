# Levantar una Vagrant Box

```sh
$ vagrant init
# Inicializa el ambiente de vagrant y genera un Vagrantfile, es necesario editarlo para seleccionar la Box. Desde el Vagrantfile se pueden personalizar las configuraciones de la Box y provisionarla.

$ vagrant up
# Si hay varios providers es necesario agregar el flag --provider [PROVIDER].

$ vagrant up --provider --help 
# Lista los hipervisores disponibles y el vagrant provider correspondiente.
```
