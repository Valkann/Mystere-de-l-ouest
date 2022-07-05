---
Created : 2022-06-24-Fri
URL:
Alias :
Type : 
- [[Note Source]]
MOC : 
- [[MOC jeu de rôle|MOC jdr]]
- [[MOC Mystère de l'ouest]]
- [[MOC Légendes et Folklore]]
PROJETS :
- [[PRJ Mystère de l'ouest]]
Source :
Author :
Date :
Tags : #SN/
---

# PROJET - Mystère de l'ouest
## Liste et résumé des intrigues

1. **Forêt de Lorges** - Une panne de voiture est le prétexte pour rencontrer des fantômes de la seconde guerre mondiale et libérer un esprit tourmenté par les Nazis. Occupation de la Bretagne et résistance pendant la seconde guerre
    [[Les marques de la guerre]]
2. **Au choix** - Un projet immobilier est saboté toutes les nuits, les vieux parlent d'un Laer Douar qui cherche à remettre en place les pierres de champs, mais un groupe d'activiste pour la protection du littoral est aussi actif dans la région.
    [[Laer Douar]]
    [[Des pierres mystérieuses]]
3. **Binic** - Le musée d'art et traditions populaires : Le conservateur a entendu parler du bateau qui a tapé la digue et il pense que quelqu'un devrait lui rapporter des objets de ce navire. En fait, ce qui serait le mieux serait de ramener l'astrolabe du bateau situé sans doute dans la cabine du capitaine, afin qu'il puisse compléter sa collection. Il est prêt à laisser aux personnages l'accès à la remise du musée et de prendre un objet en échange.
    [[Binic - musée d'art et traditions populaires]]
4. **Au choix** - Une série de morts étrange survient dans cette ville, chaque victime avait dans le poing serré un petit sac avec des ingrédients faisant penser à de la sorcellerie.
    [[Anatole Le Braz _ La Légende de la Mort chez les B]]
5. **Iliz Koz - Tréménac'h** - Les fouilles de l'église ensevelies semblent rencontrées des problèmes avec les entreprises de construction du coin, jusqu'à ce qu'on retrouve le maitre d'œuvre enseveli dans le sable, les seuls témoins semblent être les nombreux chats du coin
   [[Iliz Koz, le village de mécréants]]
6. **Plouguerneau** - D'étranges processions, vues la nuit, passent le pont du diable et paraissent célébrer des rites près du "_morzel en diaoul_". Malgré les interventions de la Police et de la gendarmerie,, aucune trace n'est jamais trouvée sur les lieux, tout parais se compliquer après la disparition de la petite marie, 12 ans.
   [[Pont du Diable]]

## Liste 
````dataview
table file.ctime as "Created Time"
FROM "/"
WHERE any(file.outlinks, (s) => contains(s, [[]])) OR any(contains(PROJETS, this.file.name))
SORT file.name ASC
````