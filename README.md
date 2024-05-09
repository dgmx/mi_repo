El primer fichero del primer repositorio de Diego J. Gonzalez

Para sincronizar git local con remoto necesitamos las claves SSH generadas y subidas a github.
Despues conectamos con el repositorio remoto con los siguientes comandos:

```bash
$ git remote set-url origin git@github.com:dgmx/mi_repo.git
$ git branch -M main
$ git push -u origin main
