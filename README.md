# masterpidgey-examen
## Parte 1
## Comandos
Clonamos el repositorio creado en una carpeta local con el comando:
- git clone https://github.com/maaarcmorla/masterpidgey-examen.git
![captura](Capturas/1.png)

Creamos el archivo README.md con los siguientes comandos y hacemos un commit inicial.
- git add README.md
- git status
- git commit -m "commit inicial"
- git push
![captura](Capturas/2.png)
![captura](Capturas/3.png)

Creamos con comandos el archivo "privado.txt", la carpeta "privada" y el .gitignore para que github ignore tanto privado.txt como el directorio privada.
- touch privado.txt
- mkdir privada
- touch .gitignore
![captura](Capturas/4.png)
- nano .gitignore
![captura](Capturas/5.png)
![captura](Capturas/6.png)
![captura](Capturas/7.png)

Creamos el archivo "1.txt" con el siguietne comando:
- touch 1.txt
![captura](Capturas/8.png)

Creamos el tag v0.1 y posteriormente subimos los cambios al repositorio.
- git tag v0.1
![captura](Capturas/9.png)

![captura](Capturas/10.png)

Historial de commits hasta el momento

![captura](Capturas/11.png)

Creamos una tabla con el nombre de Máximo Fernández Riera y su enlace a github.
| NOMBRE | GITHUB |
| -- | -- |
| Máximo Fernández Riera | [enlace a github 1](https://github.com/maximofernandezriera) |

![captura](Capturas/12.png)

Añadimos a Máximo como colaborador del repositorio.
![captura](Capturas/13.png)

## Parte 2

En primer lugar creamos un fork para hacer una copia del repositorio first-contributions y lo clonamos en un directorio local
![captura](Capturas/14.png)
- git clone https://github.com/maaarcmorla/first-contributions.git
![captura](Capturas/15.png)

Creamos una rama nueva y posrteriormente un archivo .txt y subimos los cambios.
- git checkout -b MarcMorla
- touch MarcMorlaIsern.txt
- git commit -m "Archivo MarcMorlaIsern.txt"
- git remote
- git push origin MarcMorla
![captura](Capturas/16.png)

Volvemos al repositorio y vamos al apartado de Pull Request, le damos y si hemos hecho los pasos bien podremos crear una pull request
![captura](Capturas/17.png)
Como podemos ver hemos hecho perfectamente la pull request, ahora solo faltaria que nos acepten los cambios.
![captura](Capturas/18.png)
