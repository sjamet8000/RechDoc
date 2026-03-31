<!--
author:   Samuel Jamet

email:    samuel.jamet.bib@proton.me

version:  0.0.1

language: fr

comment:  Try to write a short comment about
          your course, multiline is also okay.

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

translation: Deutsch  translations/German.md

translation: Français translations/French.md
-->

# Course Main Title

This is your **course** initialization stub.

Please see the [Docs](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md)
to find out what is possible in [LiaScript](https://liascript.github.io).

If you want to use instant help in your Atom IDE, please type **lia** to see all available shortcuts.

## Éléments du template HTML sur eCampus

### 1. Les niveaux de titre

<section>
#### 1.1. Niveau H2 (titre principal)
</section>

Copier-coller le code suivant :

```
<h2 style="
    background-color: #f7f3f5;
    color: #63003C;
    border-top: 6px solid #63003C;
    padding: 12px 15px;
    margin-top: 30px;
    margin-bottom: 20px;
    font-size: 1.6rem;
    font-weight: 700;
    border-radius: 4px 4px 0 0;
">
    1. TITRE H2 - Niveau de Section Majeure
</h2>
```

Pour obtenir ce titre :

<h2 style="
    background-color: #f7f3f5;
    color: #63003C;
    border-top: 6px solid #63003C;
    padding: 12px 15px;
    margin-top: 30px;
    margin-bottom: 20px;
    font-size: 1.6rem;
    font-weight: 700;
    border-radius: 4px 4px 0 0;
">
    1. TITRE H2 - Niveau de Section Majeure
</h2>

<section>
#### 1.2. Niveau H3 (titre intermédiaire)
</section>

Copier-coller le code suivant :

```
<h3 style="
    background-color: #63003C;
    color: #fff;
    padding: 8px 12px;
    margin-top: 24px;
    margin-bottom: 16px;
    font-size: 1.2rem;
    font-weight: 600;
    border-radius: 4px;
">
    1.1. Titre H3 - Sous-Section ou Bloc Thématique
</h3>
```

Pour obtenir ce titre

<h3 style="
    background-color: #63003C;
    color: #fff;
    padding: 8px 12px;
    margin-top: 24px;
    margin-bottom: 16px;
    font-size: 1.2rem;
    font-weight: 600;
    border-radius: 4px;
">
    1.1. Titre H3 - Sous-Section ou Bloc Thématique
</h3>

<section>
#### 1.3. Niveau H4 (titre mineur)
</section>

Copier-coller le code suivant :

```
<h4 style="
    color: #63003C;
    background-color: #f7f3f5;
    border-left: 5px solid #63003C;
    padding: 6px 10px;
    margin-top: 20px;
    margin-bottom: 12px;
    font-size: 1.1rem;
    font-weight: 600;
    border-radius: 0 4px 4px 0;
">
    1.1.1. Titre H4 - Point ou Objectif Spécifique
</h4>
```

Pour obtenir ce titre :

<h4 style="
    color: #63003C;
    background-color: #f7f3f5;
    border-left: 5px solid #63003C;
    padding: 6px 10px;
    margin-top: 20px;
    margin-bottom: 12px;
    font-size: 1.1rem;
    font-weight: 600;
    border-radius: 0 4px 4px 0;
">
    1.1.1. Titre H4 - Point ou Objectif Spécifique
</h4>

### 2. Introduction de section

<section>
#### 2.1. Titre de section
</section>

Copier-coller le code suivant

```
<!-- Titre de section -->
<div style="display: flex; align-items: center; justify-content: center; margin:
2em 0 1.5em 0; gap: 1.5em;">
    <i class="fa-solid fa-flag" style="text-align: center; font-size: 3em;
color:#72003e;" aria-hidden="true"></i>
    <div style="text-align: center; font-size: 2em; font-weight: bold; line-height:
1.3; color:#72003e;">
        Titre de section
    </div>
</div>
```

Pour obtenir ce titre
<div style="display: flex; align-items: center; justify-content: center; margin:
2em 0 1.5em 0; gap: 1.5em;">
    <i class="fa-solid fa-flag" style="text-align: center; font-size: 3em;
color:#72003e;" aria-hidden="true"></i>
    <div style="text-align: center; font-size: 2em; font-weight: bold; line-height:
1.3; color:#72003e;">
        Titre de section
    </div>
</div>

Il est possible de modifier l’icône en piochant dans la bibliothèque Font Awesome.

<section>
#### 2.2. Bloc objectif(s)
</section>

Copier-coller le code suivant

```
<!-- Bloc Objectifs -->
<div style="background-color:#72003e; padding: 0.8em; border-radius: 6px;">
    <div style="color:white; display:flex; align-items:center;">
        <i class="fa-solid fa-compass" style="font-size: 1.8em; margin-right:
10px;"></i>
        <div style="font-size: 1.2em;"><strong>Objectifs</strong></div>
    </div>
</div>

<div style="background-color:#F5F6F9; font-size: 0.95em; padding: 1em 1.2em;
margin-top:-8px; border-radius: 0 0 6px 6px;">
    <ul>
        <li>Objectif 1</li>
        <li>Objectif 2</li>
        <li>Objectif 3</li>
    </ul>
</div>
```

Pour obtenir ce bloc :
<div style="background-color:#72003e; padding: 0.8em; border-radius: 6px;">
    <div style="color:white; display:flex; align-items:center;">
        <i class="fa-solid fa-compass" style="font-size: 1.8em; margin-right:
10px;"></i>
        <div style="font-size: 1.2em;"><strong>Objectifs</strong></div>
    </div>
</div>

<div style="background-color:#F5F6F9; font-size: 0.95em; padding: 1em 1.2em;
margin-top:-8px; border-radius: 0 0 6px 6px;">
    <ul>
        <li>Objectif 1</li>
        <li>Objectif 2</li>
        <li>Objectif 3</li>
    </ul>
</div>

<section>
#### 2.3. Bloc contenus abordés
</section>

Copier-coller le code suivant

```
<!-- Bloc Contenus abordés -->
<div style="background-color:#72003e; padding: 0.8em; border-radius: 6px; margin-
top:2em;">
    <div style="color:white; display:flex; align-items:center;">
        <i class="fa fa-layer-group" style="font-size: 1.8em; margin-right:
10px;"></i>
        <div style="font-size: 1.2em;"><strong>Contenus abordés</strong></div>
    </div>
</div>

<div style="background-color:#F5F6F9; font-size: 0.95em; padding: 1em 1.2em;
margin-top:-8px; border-radius: 0 0 6px 6px;">
    <ol style="margin-top: 0;">
        <li>Contenu 1</li>
        <li>Contenu 2</li>
        <li>Contenu 3</li>
    </ol>
</div>
```

Pour obtenir ce bloc

<div style="background-color:#72003e; padding: 0.8em; border-radius: 6px; margin-
top:2em;">
    <div style="color:white; display:flex; align-items:center;">
        <i class="fa fa-layer-group" style="font-size: 1.8em; margin-right:
10px;"></i>
        <div style="font-size: 1.2em;"><strong>Contenus abordés</strong></div>
    </div>
</div>

<div style="background-color:#F5F6F9; font-size: 0.95em; padding: 1em 1.2em;
margin-top:-8px; border-radius: 0 0 6px 6px;">
    <ol style="margin-top: 0;">
        <li>Contenu 1</li>
        <li>Contenu 2</li>
        <li>Contenu 3</li>
    </ol>
</div>

<section>
#### 2.4. Bloc résumé de section
</section>

```
<!-- Bloc Résumé -->
<div style="background-color:#72003e; padding: 0.8em; border-radius: 6px; margin-
top:2em;">
    <div style="color:white; display:flex; align-items:center;">
        <div style="font-size: 1.2em;"><strong>En résumé</strong></div>
    </div>
</div>

<div style="background-color:#F5F6F9; font-size: 0.95em; padding: 1.1em 1.2em;
margin-top:-8px; border-radius: 0 0 6px 6px; line-height: 1.6;">
    <p>
        Paragraphe 1
    </p>
    <p>
        Paragraphe 2
    </p>
</div>
```

Pour obtenir ce bloc

<div style="background-color:#72003e; padding: 0.8em; border-radius: 6px; margin-
top:2em;">
    <div style="color:white; display:flex; align-items:center;">
        <div style="font-size: 1.2em;"><strong>En résumé</strong></div>
    </div>
</div>

<div style="background-color:#F5F6F9; font-size: 0.95em; padding: 1.1em 1.2em;
margin-top:-8px; border-radius: 0 0 6px 6px; line-height: 1.6;">
    <p>
        Paragraphe 1
    </p>
    <p>
        Paragraphe 2
    </p>
</div>

<section>
#### 2.5. Bloc téléchargement(s)
</section>

```
<!-- Bloc Téléchargement -->
<div style="background-color:#72003e; padding: 0.8em; border-radius: 6px; margin-
top:2em;">
    <div style="color:white; display:flex; align-items:center;">
        <i class="fa-solid fa-cloud-arrow-down" style="font-size: 1.8em; margin-
right: 10px;"><br></i>
        <div style="font-size: 1.2em;"><strong>Les fiches à télécharger</strong></div>
    </div>
</div>

<div style="background-color:#F5F6F9; font-size: 0.95em; padding: 1em 1.2em;
margin-top:-8px; border-radius: 0 0 6px 6px;">
    <ul>
        <li>Fiche "<a href="url">Nom de fiche 1</a>"</li>
        <li> Fiche "<a href="url">Nom de fiche 1</a>"</li>
    </ul>
</div>
```

Pour obtenir ce bloc

<div style="background-color:#72003e; padding: 0.8em; border-radius: 6px; margin-
top:2em;">
    <div style="color:white; display:flex; align-items:center;">
        <i class="fa-solid fa-cloud-arrow-down" style="font-size: 1.8em; margin-
right: 10px;"><br></i>
        <div style="font-size: 1.2em;"><strong>Les fiches à télécharger</strong></div>
    </div>
</div>

<div style="background-color:#F5F6F9; font-size: 0.95em; padding: 1em 1.2em;
margin-top:-8px; border-radius: 0 0 6px 6px;">
    <ul>
        <li>Fiche "<a href="url">Nom de fiche 1</a>"</li>
        <li> Fiche "<a href="url">Nom de fiche 1</a>"</li>
    </ul>
</div>

### 3. Tableaux

Copier-coller ce code :

```
<table style="width:100%; border-collapse: collapse; margin: 1em 0; font-family:
sans-serif;">
    <thead>
        <tr style="background-color: #f2f2f2;">
            <th style="padding: 10px; text-align: left; border: 1px solid #ddd;
color: #333;">Colonne 1</th>
            <th style="padding: 10px; text-align: center; border: 1px solid #ddd;
color: #333;">Colonne 2</th>
            <th style="padding: 10px; text-align: left; border: 1px solid #ddd;
color: #333;">Colonne 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule</td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule</td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule</td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
    </tbody>
</table>
```

Pour obtenir ce tableau
<html>
<table style="width:100%; border-collapse: collapse; margin: 1em 0; font-family:
sans-serif;">
    <thead>
        <tr style="background-color: #f2f2f2;">
            <th style="padding: 10px; text-align: left; border: 1px solid #ddd;
color: #333;">Colonne 1</th>
            <th style="padding: 10px; text-align: center; border: 1px solid #ddd;
color: #333;">Colonne 2</th>
            <th style="padding: 10px; text-align: left; border: 1px solid #ddd;
color: #333;">Colonne 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule</td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule</td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule</td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
        <tr>
            <td style="padding: 8px; border: 1px solid #ddd; font-weight:
bold;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd; text-align:
center;">Cellule<br></td>
            <td style="padding: 8px; border: 1px solid #ddd;">Cellule<br></td>
        </tr>
    </tbody>
</table>
</html>

### 4. Eléments divers

<section>
#### 3.1. Box
</section>

Copier-coller le code suivant :

```
<!-- Box -->
<div style="font-family: system-ui, sans-serif; display: flex; flex-wrap: wrap;
gap: 1em; justify-content: center; margin-top: 1em">
    <div style="flex: 1 1 45%; min-width: 320px; max-width: 600px; background-
color: #f9f9f9; border: 1px solid #ddd; border-radius: 12px; padding: 1.3em 1.5em;
box-shadow: 0 3px 8px rgba(0,0,0,0.08); box-sizing: border-box;">
        <div style="font-size: 1.18em; color: #111; font-style: italic; margin-
bottom: 0.8em;">
            <strong style="color: #777;">Titre
            </strong>
        </div><strong style="color: #777;">
            <div style="color: #333; line-height: 1.6; font-size: 0.98em;">
                <p style="text-align: left;">Texte</p>
            </div>
        </strong>
    </div>
</div>
```

Pour obtenir cette box

<div style="font-family: system-ui, sans-serif; display: flex; flex-wrap: wrap;
gap: 1em; justify-content: center; margin-top: 1em">
    <div style="flex: 1 1 45%; min-width: 320px; max-width: 600px; background-
color: #f9f9f9; border: 1px solid #ddd; border-radius: 12px; padding: 1.3em 1.5em;
box-shadow: 0 3px 8px rgba(0,0,0,0.08); box-sizing: border-box;">
        <div style="font-size: 1.18em; color: #111; font-style: italic; margin-
bottom: 0.8em;">
            <strong style="color: #777;">Titre
            </strong>
        </div><strong style="color: #777;">
            <div style="color: #333; line-height: 1.6; font-size: 0.98em;">
                <p style="text-align: left;">Texte</p>
            </div>
        </strong>
    </div>
</div>

<section>
#### 3.2. Box imbriquées
</section>

Copier-coller le code suivant :

```
<!-- Box imbriquées -->
<div style="flex: 1 1 100%; min-width: 100%; max-width: 100%; background-color:
#f9f9f9; border: 1px solid #ddd; border-radius: 12px; padding: 1.3em 1.5em; box-
shadow: 0 3px 8px rgba(0,0,0,0.08); box-sizing: border-box; margin-top: 1em">
    <div style="font-size: 1.18em; color: #111; font-style: italic; margin-bottom:
0.8em;"><strong>Titre</strong></div>
    <p style="color: #333; line-height: 1.6; font-size: 0.98em; margin-bottom:
12px;">Texte</p>

    <div style="display: flex; flex-wrap: wrap; gap: 1em; justify-content: space-
between; margin-top: 12px;">
        <div style="flex: 1 1 45%; min-width: 200px; background-color: #fff;
border: 1px solid #eee; border-radius: 8px; padding: 12px; box-sizing: border-
box;">
            <h4 style="margin-top: 0; color: #d32f2f; font-size: 1em;">Sous-titre
1</h4>
            <ul style="margin: 8px 0 0 20px; padding: 0; color: #555;">
                <li>Texte</li>
                <li>Texte</li>
            </ul>
        </div>

        <div style="flex: 1 1 45%; min-width: 200px; background-color: #fff;
border: 1px solid #eee; border-radius: 8px; padding: 12px; box-sizing: border-
box;">
            <h4 style="margin-top: 0; color: #2e7d32; font-size: 1em;">Sous-titre
2</h4>
            <ul style="margin: 8px 0 0 20px; padding: 0; color: #555;">
                <li>Texte</li>
                <li>Texte</li>
            </ul>
        </div>
    </div>
</div>
```

Pour obtenir ces box imbriquées

<div style="flex: 1 1 100%; min-width: 100%; max-width: 100%; background-color:
#f9f9f9; border: 1px solid #ddd; border-radius: 12px; padding: 1.3em 1.5em; box-
shadow: 0 3px 8px rgba(0,0,0,0.08); box-sizing: border-box; margin-top: 1em">
    <div style="font-size: 1.18em; color: #111; font-style: italic; margin-bottom:
0.8em;"><strong>Titre</strong></div>
    <p style="color: #333; line-height: 1.6; font-size: 0.98em; margin-bottom:
12px;">Texte</p>

    <div style="display: flex; flex-wrap: wrap; gap: 1em; justify-content: space-
between; margin-top: 12px;">
        <div style="flex: 1 1 45%; min-width: 200px; background-color: #fff;
border: 1px solid #eee; border-radius: 8px; padding: 12px; box-sizing: border-
box;">
            <h4 style="margin-top: 0; color: #d32f2f; font-size: 1em;">Sous-titre
1</h4>
            <ul style="margin: 8px 0 0 20px; padding: 0; color: #555;">
                <li>Texte</li>
                <li>Texte</li>
            </ul>
        </div>

        <div style="flex: 1 1 45%; min-width: 200px; background-color: #fff;
border: 1px solid #eee; border-radius: 8px; padding: 12px; box-sizing: border-
box;">
            <h4 style="margin-top: 0; color: #2e7d32; font-size: 1em;">Sous-titre
2</h4>
            <ul style="margin: 8px 0 0 20px; padding: 0; color: #555;">
                <li>Texte</li>
                <li>Texte</li>
            </ul>
        </div>
    </div>
</div>

<section>
#### 3.3. Callouts
</section>

Copier-coller le code suivant :

```
<div style="border-left:4px solid #1971c2; background-color:#f0f8ff; padding:10px
12px; margin:12px 0;">
    <p style="margin:0; color: #2e7d32; font-weight: 600;">Callout titre vert</p>
    <p style="margin:0;">Texte</p>
</div>
```

Pour obtenir ce callout :

<div style="border-left:4px solid #1971c2; background-color:#f0f8ff; padding:10px
12px; margin:12px 0;">
    <p style="margin:0; color: #2e7d32; font-weight: 600;">Callout titre vert</p>
    <p style="margin:0;">Texte</p>
</div>

Copier-coller le code suivant :

```
<div style="border-left:4px solid #d32f2f; background-color:#fff0f0; padding:10px
12px; margin:12px 0;">
    <p style="margin:0; color: #d32f2f; font-weight: 600;">Callout rouge</p>
    <p style="margin:0;">Texte</p>
</div>
```

Pour obtenir ce callout :

<div style="border-left:4px solid #d32f2f; background-color:#fff0f0; padding:10px
12px; margin:12px 0;">
    <p style="margin:0; color: #d32f2f; font-weight: 600;">Callout rouge</p>
    <p style="margin:0;">Texte</p>
</div>

Copier-coller le code suivant :

```
<div style="border-left:4px solid #1971c2; background-color:#f0f8ff; padding:10px
12px; margin:12px 0;">
    <p style="margin:0;"><strong>Callout neutre</strong></p>
    <p style="margin:0;"><span>Texte</span></p>
</div>
```

Pour obtenir ce callout :

<div style="border-left:4px solid #1971c2; background-color:#f0f8ff; padding:10px
12px; margin:12px 0;">
    <p style="margin:0;"><strong>Callout neutre</strong></p>
    <p style="margin:0;"><span>Texte</span></p>
</div>

Copier-coller le code suivant :

```
<div style="border-left:4px solid #1971c2; background-color:#f0f8ff; padding:10px
12px; margin:12px 0;">
    <p style="margin:0;"> Texte</p>
</div>
```

Pour obtenir ce callout :

<div style="border-left:4px solid #1971c2; background-color:#f0f8ff; padding:10px
12px; margin:12px 0;">
    <p style="margin:0;"> Texte</p>
</div>