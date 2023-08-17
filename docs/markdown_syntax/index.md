<head>
  <link rel="stylesheet" href="../css/styles.css">
</head>

# Coucou le Markdown

## Les titres

> Le but est d'organiser le contenu.

- # Titre de niveau 1 : `#`
- ## Titre de niveau 2 : `##`
- ### Titre de niveau 3 : `###`
- #### Titre de niveau 4 : `####`
- ##### Titre de niveau 5 : `#####`
- ###### Titre de niveau 6 : `######`

## Les listes

### Listes non ordonnées

> Permet le lister des éléments

On utilise `-` ou `*` devant chaque ligne

- Elément 1
- Elément 2

    - Sous élément 1
    - Sous élément 2

### Listes ordonnées

> Permet le lister des éléments de manière ordonnée

On utilise `1.` devant chaque ligne (penser à incrémenter ;))

1. Elément 1: `coucou`
2. Elément 2

    1. Sous élément 1
    2. Sous élément 2

## Les liens

La syntaxe : `[contenu_a_afficher](cible)`

- [Lien vers VSCodium](https://vscodium.com/)
- [Autre doc](./admin_linux/module1.md)
- [Les tableaux](#les-tableaux)

## Les images

La syntaxe : `![texte_a_afficher](./images/tux.png)`

![pwet](./images/Tux-2.png)

## Le formatage de texte

On peut mettre :

- **en gras**
- *en italique*
- ~~du texte barré~~
- `du code inline`
- du code en mode bloc

    ```
    Mon bloc de code !
    ```

    ```bash
    #!/bin/bash
    addition(){
    sum=$(($1+$2))
    return $sum
    }
    read -p "Entrez un numéro : " int1
    read -p "Entrez un numéro : " int2
    add $int1 $int2
    echo "Le résultat est : " $?
    ```

## Les tableaux

| Commande | Description |
| --- | --- |
| `ls` | Lister des fichiers |
| `cat` | Affiche un contenu |

## Personnalisation avancée

Je mon texte en <span style="color: red;">rouge</span> !
Je mon texte en <span class="red">rouge</span> ou en <span class="green">vert</span> !
