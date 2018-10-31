# dgsiaf.nagios-nrpe

Role de ansible para instalar y configurar nrpe.

Plataformas testeadas:
- Rhel 7

## Uso

- Crear o modificar el archivo requirements.yml en el directorio raiz de la receta para incluir el rol.

```
- src: git@dgsiaf-gitlab.mecon.ar:tecnologia/dgsiaf.nagios-nrpe
  scm: git
  version: "master"
```

- Ejecutar el comando galaxy-install para instalar el rol.

```
ansible-galaxy install -r requirements.yml
```

- Incluir el rol en la receta y modificar de ser necesario el valor de las variables definidas en defaults/main.yml a traves del paso de parametros al rol.
