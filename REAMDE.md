# Tutoriel d’introduction à Quarto - Rencontres R 2023 - Avignon

Ce dépôt contient le code source du site web utilisé pour les resources
au tutoriel, disponible à https://cderv.github.io/tuto-quarto-rr-2023/

## Pour être prêt et faire les exercices

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
  pkg_list <- c("rmarkdown")
  install.packages(pkg_list)
  ```

- Téléchargez `exercises.zip` et décompressez-le sur votre bureau ou à
  un endroit que vous pouvez facilement le localiser sur votre
  ordinateur. Ensuite, allez dans RStudio \> File \> New Project \>
  Existing Directory et naviguez jusqu’au dossier `exercises` dézippé et
  créez un projet RStudio à l’intérieur et ouvrez-le.