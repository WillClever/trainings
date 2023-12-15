# Trainings CleverIT 🦾 Present 
![Training](https://github.com/WillClever/trainings/blob/gh-pages/media/trainingsclever.png)
# 🧠 HeadsOps GitHub Team 🦾
Presentations As a Code
![by @willclever](https://github.com/WillClever/trainings/blob/v1/media/headsOps.jpg)

# Información
En este repositorio estara toda la informacion acerca de los trainings para clever !

Funciones Disponibles
- Crear Presentaciones apartir de templates en reveal JS
- Configurar CSS
- Pitch(guiones) de cada una de las siguientes presentaciones
    - Cultura DevOps [Canva](https://www.canva.com/design/DAF248rMD48/4XoO_25PQmMDV7NklH_wIQ/edit?utm_content=DAF248rMD48&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) ,
    [Guiones](https://github.com/WillClever/trainings/blob/v1/media/Guiones/github-knowledge.md)
    - Git Knowledge [Canva](https://www.canva.com/design/DAF2-ANrJCA/flWS-HAgt47Gvifrrfcivw/edit?utm_content=DAF2-ANrJCA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton),
    [Guiones]()
    - Git / GitHub [Canva](https://www.canva.com/design/DAF24LSIp6c/GZpDFDObL91bn7BgCJfh5A/edit?utm_content=DAF24LSIp6c&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) , [Guiones](https://github.com/WillClever/trainings/blob/v1/media/Guiones/git-github.md)
    - Git Hands On [Canva](https://www.canva.com/design/DAF3Aru51yI/BHr_gaQf7PTp3qckjihfUg/edit?utm_content=DAF3Aru51yI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton),
    [Guiones]()



# Versiones y Branchs

| Branch       |               Descripcion                    |
| ------------ |              ------------                    |
| min          | Aun no se ha hecho merge sobre esta rama     |
| v1           | Contiene todo lo que se esta creando para presentaicones BICe     |
| gh-pages     | Actions para desplegar revealJS              |

# Reveal JS 🛠️
- - - - - - - - - - - - - - - - - - - - - - - - -
- Install Node.js (10.0.0 or later)
- Hacer clone del repositorio
```
git clone https://github.com/hakimel/reveal.js.git
```
- Move to the reveal.js folder and install dependencies
```
cd reveal.js && npm install
```
Serve the presentation and monitor source files for changes
```
npm start
```
Open http://localhost:8000 to view your presentation

# Slides SSH 🚀
- - - - - - - - - - - - - - - - - - - - - - - - -

- Abrir el navegador.

- Info como usar slides SH
https://github.com/ivantsepp/ssh-slides

##### about:debugging

# SliDev 🚀
- - - - - - - - - - - - - - - - - - - - - - - - -

- Abrir el navegador.
- Slidev requires Node.js >=18.0
```
npm init slidev@latest
npm install @slidev/cli @slidev/theme-default
touch slides.md
npx slidev
echo 'shamefully-hoist=true' >> .npmrc
```
- Info como usar slides SH
https://sli.dev/guide/install.html#starter-template

##### about:debugging

# Gitpitch 🚀
- - - - - - - - - - - - - - - - - - - - - - - - -

- Abrir el navegador.

- Git pitch
https://github.com/gitpitch/gitpitch

##### about:debugging


# referencia :


# Colaboradores ⌨️

Team DevOps / Github clever IT
- [Gabriel Berlot]()
- [Sebastian Ramos](https://github.com/sebastianramospina)
- [Ramiro Garcia](https://github.com/ramirogarcia-clever)
- [Joan Aliberti](https://github.com/JoanAliberti)
- [William Quintero]() [@WillClever]

# Soporte/Contacto

# Uso expresion regular para ajustar los paths
```
!\[.*\]\(([^)]*)\)
![$1](media/$1)
```