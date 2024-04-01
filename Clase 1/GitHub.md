# Git y GitHub

Software de control de versiones

Git: Repositorio Local
GitHub: Resopitorio remoro

Crear cuenta de GitHub
Crear Repositorio en GitHub

# Configurando GitHub
```bash
git init # Inicializa el repositorio (1era en proyecto)
# Antes de 2020 era master
git branch -m main # Cambiar de nombre la rama (branch) 

ls -a # Para listar los archivos ocultos

git status # Ver el estado de los archivos (existen en el proyecto pero no están en el stage de git

git add . # Agrega todos los archivos al stage de git 
git add index.html # Agrega solo el archivo index.html

git remote add origin "url" #Agrega el link del repositorio de Git Hub
git remote -v # Confirmar vinculación

git config --list # Observar características de usuario GitHub en ordenador
git config --global user.name "jeanpier22" # Agregar nombre de usuario de GitHub
git config --global user.email "jeanpier.ancori@gmail.com" # Agregar email de GitHub

git add . 
git commit -m "Mi primer commit" # Crea un commit 
git push origin main # Carga a GitHub el commit generado 
# En este punto es probable que pida ingresar a la cuenta de GitHub

git config --global --unset user.mail # Para eliminar algún atributo mal colocado en la configuración global
git remote set-url origin "http" # En caso no encuentre el repositorio en GitHub

git checkout main # Para cambiar de rama
```
# GitHub Page

```bash
Settings --> Pages --> Source (deploy from a branch) --> Branch(main) --> Save
```