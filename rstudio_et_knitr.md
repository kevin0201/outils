# Sous windows faire marcher rstudio et knitr 

## Attention les chemins d'accès des fichiers de miktex et/ou R ne doivent pas contenir d'espace.

1. Installer miktex à la racine (le chemin d'accès ne doit pas avoir d'espace)
2. Installer R à la racine 
3. Installer Rstudio normalement 
4. Installer le package knitr (install.packages('knitr')) via rstudio
5. Dans rstudio, tools -* global option -* sweave -* definri knitr comme converter par defaut à la place de sweave
6. Creer un ficher R sweave qui sera converti par pdflatex
7. Le code latex dans un fichier knitr va dans les chunks << [paramètres chunk] >>=  (Code R)  @
8. Le type de fichier de knitr est Rnw (R noweb)
