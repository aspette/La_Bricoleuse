# GÉNÉRAL

## <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/bricoleuse.png" width="56px"/> <font color="#b6c303">**La Bricoleuse**</font> se refait une beauté avec cette version 2.0 !

### Toutes les commandes deviennent des commandes dites Slash :

- <font color="#FFCC00">**NEW!**</font> Ces commandes sont disponibles et visibles directement en utilisant le caractère `/`.
- <font color="#FFCC00">**NEW!**</font> Les arguments sont plus intuitifs à l'utilisation.
- <font color="#FF0011">**DELETED**</font> Le préfixe `?` disparaît totalement.

---

### La recherche, la navigation et la lecture :

- La navigation via pagination est améliorée :
  - Les IDs sont mieux identifiables.
  - <font color="#FFCC00">**NEW!**</font> Une liste déroulante a été ajoutée pour sélectionner un élément affiché sur la page.
  - <font color="#FFCC00">**NEW!**</font> Il est possible de retourner aux résultats d'une recherche après avoir sélectionné un élément.
- <font color="#FFCC00">**NEW!**</font> Lorsqu'un élément recherché n'est pas reconnu par <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/bricoleuse.png" width="28px"/> <font color="#b6c303">**La Bricoleuse**</font>, l'erreur est désormais affiché uniquement pour l'utilisateur ayant utilisé la commande.
- <font color="#FFCC00">**NEW!**</font> Plusieurs icônes ont été ajoutées pour améliorer la lisibilité des fiches, notamment pour les effets des objets ou des sorts.
- <font color="#FFCC00">**NEW!**</font> L'autocomplétion fait son entrée : des options correspondant à l'argument entré s'affichent en temps réel lors de la saisie.
- <font color="#FF0011">**DELETED**</font> Les caractères `*` et `/` en début d'argument ne sont plus nécessaires pour rechercher tous les éléments ayant l'argument entré.

# LES COMMANDES

### <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/sidekick.png" width="28px"/> Les compagnons : `/sidekick`

- Renvoie la fiche d'un compagnon, par son nom ou son ID.
- Nouveautés :
  - <font color="#FFCC00">**NEW!**</font> La fiche d'un compagnon est désormais divisée en 3 pages :
    - Ses caractéristiques
    - Ses sorts
    - Sa description
  - <font color="#FFCC00">**NEW!**</font> Il est désormais possible de naviguer entre un compagnon et ses sorts.

---

### <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/spells.png" width="28px"/> Les états : `/state`

- Renvoie la fiche d'un état, par son nom ou son ID.
- L'icône de la fiche a été modifiée.

---

### <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/item.png" width="28px"/> Les objets : `/item`

- Renvoie la fiche d'un objet, par son nom ou son ID.
- Corrections :
  - La densité des runes de forgemagie est de nouveau prise en charge.
  - Le métier lié à une recette est mis en évidence.
  - La panoplie d'un objet est mis en évidence, et dispose désormais d'un lien cliquable redirigeant vers la page DOFUS de la panoplie.
  - Certains effets sont désormais correctement traduits.
  - Certaines conditions sont désormais correctement traduites.
- Nouveautés :
  - <font color="#FFCC00">**NEW!**</font> Depuis un objet, il est désormais possible de naviguer vers :
    - Sa panoplie
    - Son compagnon
    - Son incarnation
    - Son sort appris ou lancé au début du combat
  - <font color="#FFCC00">**NEW!**</font> Pour les objets d'apparat liés temporairement, un nouveau système a été mis en place pour afficher la date de déliaison d'un objet à partir de sa première date de parution.
  - <font color="#FFCC00">**NEW!**</font> L'icône de la fiche et le nom de la super-catégorie changent selon l'objet. <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/item_equipment_alt.png" width="28px"/><img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/item_consumable_alt.png" width="28px"/><img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/item_resource_alt.png" width="28px"/><img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/item_quest_alt.png" width="28px"/><img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/item_cosmetic_alt.png" width="28px"/><img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/item_alteration_alt.png" width="28px"/>
  - <font color="#FFCC00">**NEW!**</font> L'équivalent en pépites d'un objet est désormais affiché. Il en est de même pour l'expérience apportée à un familier ou un montilier.
  - <font color="#FFCC00">**NEW!**</font> Dans le cas d'un objet vivant, toutes les apparences de l'objet vivant recherché sont affichées.

---

### <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/monster.png" width="28px"/> Les monstres : `/monster`

- Renvoie la fiche d'un monstre, par son nom ou son ID.
- Corrections :
  - L'icône de la fiche a été modifiée.
  - La recherche a été optimisée.
  - Une liste déroulante remplace les boutons dans le choix des grades.
- Nouveautés :
  - <font color="#FFCC00">**NEW!**</font> La fiche d'un monstre est désormais divisée en 4 pages :
    - Ses caractéristiques
    - Ses sorts
    - Sa liste de butins disponibles
    - <font color="#FFCC00">**NEW!**</font> Ses modificateurs des Songes Infinis, `?psi` fusionne avec `/monster` <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/breach0.png" width="28px"/><img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/breach1.png" width="28px"/><img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/breach2.png" width="28px"/><img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/breach3.png" width="28px"/><img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/breach4.png" width="28px"/>
  - <font color="#FFCC00">**NEW!**</font> Il est possible de naviguer entre un monstre et ses sorts.
  - <font color="#FFCC00">**NEW!**</font> Les archi-monstres, les gardiens de donjon et les monstres de quête sont désormais mis en avant dans la recherche.

---

### <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/set.png" width="28px"/> Les panoplies : `/set`

- Renvoie la fiche d'une panoplie, par son nom ou son ID.
- Corrections :
  - Il est désormais possible de consulter le bonus de panoplie à 1 objet s'il existe.
  - L'icône de la fiche a été modifiée.
  - S'il y a trop d'effets, la suite est affichée à côté et non plus sous la première liste afin d'économiser de l'espace.
  - Une liste déroulante remplace désormais les boutons pour le choix du nombre d'objets.
- Nouveautés :
  - <font color="#FFCC00">**NEW!**</font> Il est désormais possible de naviguer entre une panoplie et :
    - Un objet de la panoplie
    - Une classe s'il s'agit d'une panoplie de classe
  - <font color="#FFCC00">**NEW!**</font> Tous les visuels des objets d'une panoplie sont affichés.

---

### <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/spells.png" width="28px"/> Les sorts : `/spell`

- Renvoie la fiche d'un sort, par son nom ou son ID.
- Corrections :
  - Certains effets mal traduits ont été corrigés.
  - La traduction des cibles affectées a été améliorée.
  - Lorsqu'un sort possède plus de 5 rangs, une liste avec chaque rang remplace désormais les boutons.
  - Le taux de critique d'un sort n'est plus affiché s'il est nul.
  - L'icône de la fiche a été modifiée.
- Nouveautés :
  - <font color="#FFCC00">**NEW!**</font> Il est désormais possible de naviguer entre un sort et :
    - Sa variante
    - Une classe
    - Un compagnon
    - Une incarnation
    - Un monstre
    - Un monstre invoqué
  - <font color="#FFCC00">**NEW!**</font> Les incarnations utilisant un sort recherché sont désormais affichées.
  - <font color="#FFCC00">**NEW!**</font> La variante d'un sort est dispose désormais d'un lien cliquable redirigeant vers la page DOFUS de la variante.
  - <font color="#FFCC00">**NEW!**</font> Lors de la recherche (autocomplétion & pagination), les sorts des classes sont désormais affichés en tête de liste.

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/alteration.png" width="28px"/> Les altérations : `/alteration`

- Renvoie la fiche d'une altération, par son nom ou son ID.
  - Si aucun argument n'est entré, renvoie la liste de toutes les altérations.

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/about.png" width="28px"/> À propos de <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/bricoleuse.png" width="28px"/> <font color="#b6c303">**La Bricoleuse**</font> : `/about`

- Renvoie quelques détails à propos de <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/bricoleuse.png" width="28px"/> <font color="#b6c303">**La Bricoleuse**</font>.

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/almanax.png" width="28px"/> L'Almanax `/almanax`

- Cette commande fonctionne avec deux sous-commandes :
  - `/almanax today`
    - Renvoie la fiche de l'Almanax du jour.
  - `/almanax auto`
    - Renvoie automatiquement chaque jour l'Almanax du jour dans le salon utilisé.
      - Réutiliser cette commande dans un même salon désactive l'envoi automatique.

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/arena.png" width="28px"/> Les arènes de tournois : `/arena`

- Anciennement `/map`.
- Cette commande fonctionne avec trois sous-commandes :

  - `/arena all`
    - Renvoie toutes les arènes.
      - Les arènes Kolizéum sont également disponibles.
  - `/arena random`

    - Renvoie une ou plusieurs arène(s) aléatoirement.
      - Il est possible de bannir du tirage aléatoire jusqu'à 6 arènes.

  - `/arena select`
    - Renvoie une ou plusieurs arène(s) arbitrairement.
      - Il est possible de sélectionner jusqu'à 5 arènes.

- La navigation entre les arènes est améliorée.

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/challenge.png" width="28px"/> Les challenges : `/challenge`

- Renvoie la fiche d'un challenge, par son nom ou son ID.
  - Si aucun argument n'est entré, renvoie la liste de tous les challenges.
  - Il est possible de naviguer entre les challenges incompatibles avec le challenge recherché.

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/class.png" width="28px"/> Les classes : `/class`

- Renvoie la fiche d'une classe, par son nom ou son ID.
  - Si aucun argument n'est entré, renvoie la liste de toutes les classes.
  - Il est possible de naviguer entre une classe et :
    - Ses sorts
    - Sa panoplie de classe

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/perceptor.png" width="28px"/> Le générateur de percepteurs : `/perceptor`

- Génère un nom de percepteur.

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/sidekick.png" width="28px"/> Les incarnations : `/incarnation`

- Renvoie la fiche d'une incarnation, par son nom ou son ID.
  - La fiche d'un monstre est divisée en 2 pages :
    - Ses caractéristiques (indisponible pour le moment)
    - Ses sorts
  - Il est possible de naviguer entre une incarnation et :
    - Ses sorts
    - Son arme

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/area_modificator.png" width="28px"/> Les modificateurs de zone : `/modificator`

- Renvoie la fiche d'un modificateur de zone, par son nom ou son ID.
  - Si aucun argument n'est entré, renvoie la liste de tous les modificateurs de zone.

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/npc.png" width="28px"/> Les PNJs : `/npc`

- Renvoie un PNJ, par son nom ou son ID.

---

### <font color="#FFCC00">**NEW!**</font> <img src="https://raw.githubusercontent.com/aspette/La_Bricoleuse/master/Icons/Commands/achievement.png" width="28px"/> Les succès : `/achievement`

- Renvoie la fiche d'un succès, par son nom ou son ID.
  - Si aucun argument n'est entré, renvoie la liste de tous les succès.

---

### <font color="#FF0011">**DELETED**</font> Les commandes suivantes ont été supprimées :

- <font color="#FF0011">**DELETED**</font> L'aide `/help `
- <font color="#FF0011">**DELETED**</font> Le Boomerang Perfide `/boomerangperfide`
- <font color="#FF0011">**DELETED**</font> L'enregistrement au SGI '`/register`
- <font color="#FF0011">**DELETED**</font> Le fun `/fun`
- <font color="#FF0011">**DELETED**</font> Le guide `/guide`
- <font color="#FF0011">**DELETED**</font> L'invocation de Chaferfu`/invocationdechaferfu`
- <font color="#FF0011">**DELETED**</font> Le Spell Guesser Interserveur `/spellguesserinterserveur`
- <font color="#FF0011">**DELETED**</font> Les suggestions `/suggestion`
