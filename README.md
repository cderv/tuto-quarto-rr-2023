# Tutoriel d’introduction à Quarto - Rencontres R 2023 - Avignon

Ce dépôt contient le code source du site web utilisé pour les resources
au tutoriel, disponible à https://cderv.github.io/tuto-quarto-rr-2023/

## Pour être prêt et faire les exercices

Configuration de votre environment:

- Téléchargez et installez les dernières versions de R, RStudio et
  Quarto :

  - Une version de R récente (4.2 ou plus) :
    <https://cran.r-project.org>
  - Dernière version de RStudio (`2023.03.1+446` ou supérieur) :
    <https://posit.co/download/rstudio-desktop>
  - Derniere version de Quarto (`1.3.361` ou supérieur) :
    <https://quarto.org/docs/get-started>

- Installez les paquets suivants :

  ``` r
  # Pour les exercices (dplyr et ggplot2 devraient être suffisant si vous ne voulez pas tout le tidyverse)
  pkg_list <- c("rmarkdown", "palmerpenguins", "gt", "tidyverse") 
  # R base
  install.packages(pkg_list)
  # ou pak
  pak::pkg_install(pkg_list)
  ```

Si vous préférez avoir les fichiers en local en avance:

- Téléchargez [`exercises.zip`](exercices.zip).  
  Ce dossier compressé contient les différentes resources qui pourront
  être utiles pour les exercices. Décompressez-le sur votre bureau ou à
  un endroit que vous pouvez facilement le localiser sur votre
  ordinateur. Vous pourrez ainsi simplement copier coller au fil du
  tutoriel les fichiers dont vous aurez besoin.

- Téléchargez [`exemples-correction.zip`](exemples-correction.zip).  
  **Il s’agit d’équivalent de corrections aux exercices - Ne pas
  regarder en avance si vous souhaitez vous exercez vraiment le jour
  J**.  
  Ce dossier compressé contient les différentes resources servant
  d’exemples et démonstrations. Décompressez-le sur votre bureau ou à un
  endroit que vous pouvez facilement le localiser sur votre ordinateur.
  Vous pourrez ainsi simplement copier coller au fil du tutoriel les
  fichiers dont vous aurez besoin.

## Licence

![](https://i.creativecommons.org/l/by/4.0/88x31.png) Ce travail est
soumis à la licence [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
