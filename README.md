# Desafio 01 - Bootcamp

## El desafio es crear una pagina web más este readme.md

# Creo un repositorio de GIT

```sh
git init 
```

1. Me fijo el estado de los archivos

```sh
git status
```

2. Agrego al staging los archivos

```sh
git add . <nombre-archivo> # ( en caso de querer agregar todo)
git add <nombre-archivo> # (en caso de querer agregar uno solo)
```

3. Hago un commit

```sh
git commit -m "mensaje"
```

## Utilizo las etiquetas aprendidas

```sh
Etiquetas: strong, b, em, i, h1, ,h2, p, entre otras.
```

Finalizado el codigo lo valido y compruebo en la siguiente pagina para ver si esta todo correcto
```sh
https://validator.w3.org/nu/
```

ya con el archivo HTML comprobado, pasamos el repositorio local a remoto a github

```sh
git remote add origin https://github.com/GiannMlclz/desafio-01.git
git push -u origin main
```