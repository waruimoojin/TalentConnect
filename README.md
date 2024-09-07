# TalentConnect
TalentConnect est le sujet de mon Projet de Fin d'Études (PFE) et a été développé en utilisant la MERN Stack (MongoDB, Express.js, React, Node.js). Cette plateforme web vise à révolutionner le processus de recrutement en offrant une solution intelligente et efficace pour connecter les entreprises avec des talents qualifiés.


## Install

Ce projet utilise [Docker](https://docs.docker.com) et [github packages](https://docs.github.com/en/packages/learn-github-packages/introduction-to-github-packages). 

- Pull `the packages` .
```sh
$ docker pull ghcr.io/waruimoojin/talentconnect/backend:latest
$ docker pull ghcr.io/waruimoojin/talentconnect/frontend:latest
```
- Run les images docker.

### Pour le Frontend 
-la commandes pour demarrer le server: 

```sh
$ docker run -d -p 5173:5173 ghcr.io/waruimoojin/talentconnect/frontend:latest
```


### Pour le Backend
-la commande pour demarrer le server: 


```sh
$ docker run -d -p 3000:3000 ghcr.io/waruimoojin/talentconnect/backend:latest
```
