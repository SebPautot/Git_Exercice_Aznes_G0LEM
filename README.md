# Exo Git 4

## Stratégie pour éviter les conflits
- Eviter de travailler sur la même map
- Eviter de travailler sur le même Blueprint
- L'utilisation de Github Desktop est hautement illégale !

![meme](https://images.steamusercontent.com/ugc/1621679306976962913/ECBBE288EC490205416C124D9FB34579EF0F2313/?imw=637&imh=358&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=true)

## Historique lisible
L'historique des commits est lisible grâce à :
- Notre infaillible communication.
- Une branche unique :
  - Pas besoin de faire plusieurs branches vu qu'on travail à deux.
  - Le multi-branche serait plus pertinent pour des projets plus grands, avec plus de contributeurs, ou demandant que certaines features soient développées séparément pendant plus de temps avant d'être merge.
  - Pas de merge de branche à gérer, uniquement des merge de modifs de la branche principale.
- Noms de commit évocatifs et descriptifs.
- Chaque commit est représentatif d'un objectif de changement spécifique, et non éparpillé entre plusieurs features sans rapport.

## LFS
Git LFS n'est pas utilisé pour des raisons évidentes, on a rien à y stocker même si Github met des alertes dans la console.
![meme2](https://i.redd.it/um6jp400h5zc1.jpeg)

De toute façon je (Sébastien) ne peut pas utiliser Github LFS vu que mon quota est déjà explosé (projet qui utilisait LFS y a quelques années qui a explosé mon quota, je suis toujours en recovery smh).