# Rapport du projet Medialibs

## Prérequis

- Ruby >= 1.8.7
- Gem

## Installation

Pour installer AsciiDoctor, vous devez l'installer de la façon suivante
`$ gem install asciidoctor`.
Vous pourrez ensuite vérifier son installation avec la commande suivante
`$ asciidoctor --version`

Vous devriez avoir la sortie suivante en cas de réussite d'installation :
```
Asciidoctor 1.5.4 [http://asciidoctor.org]
Runtime Environment (ruby 2.3.0p0 [x86_64-linux]) (lc:UTF-8 fs:UTF-8 in:- ex:UTF-8)
```

Vous devrez ensuite installer la librairie *rouge*, afin d'avoir la coloration
syntaxique sur les exemples de code sources : `$ gem install rouge`.

## Compilation du rapport

Pour compiler le rapport complet, il vous suffit de taper la commande suivante
dans le dossier contenant le fichier *index.adoc* :
`$ asciidoctor -r asciidoctor-pdf -b pdf index.adoc`

Vous générerez alors le rapport final compiler automatiquement, et ayant pour nom
index.pdf.

## Auteur

* Nicolas GILLE : <nic.gille@gmail.com>
