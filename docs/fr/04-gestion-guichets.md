# Gestion Des Guichets

*Comment créer, configurer, attribuer et exploiter les guichets, les
points de service de première ligne où les agents traitent les tickets
des clients.*

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><h3 id="dans-ce-chapitre">Dans ce chapitre</h3>
<p>• 4.1 Qu’est-ce qu’un guichet ?<br />
• 4.2 Création d’un guichet<br />
• 4.3 Attribution des guichets aux agents<br />
• 4.4 Ouverture et fermeture d’un guichet<br />
• 4.5 Gestion des guichets<br />
• 4.6 Bonnes pratiques des guichets</p></td>
<td><h3 id="après-ce-chapitre-vous-serez-en-mesure-de">Après ce
chapitre, vous serez en mesure de :</h3>
<p>• Comprendre le rôle du guichet dans Queco<br />
• Créer un nouveau guichet dans une agence<br />
• Attribuer un agent à un guichet<br />
• Ouvrir et fermer un guichet pour les opérations quotidiennes<br />
• Modifier, désactiver et supprimer des guichets<br />
• Appliquer les bonnes pratiques pour optimiser le flux des files
d’attente</p></td>
</tr>
</tbody>
</table>

## 4.1 Qu'est-ce qu'un guichet ?

Un guichet est un point de service désigné au sein d'une agence où les
tickets des clients sont reçus et traités. Dans un bureau physique, un
guichet correspond à un bureau ou à une fenêtre de service. Dans un
environnement virtuel ou hybride, il représente un canal de service
numérique attribué à un agent spécifique.

Les guichets constituent le cœur opérationnel de Queco. Chaque ticket
qui entre dans le système est finalement acheminé vers un guichet, où il
est appelé, traité et clôturé par l'agent assigné. Sans au moins un
guichet ouvert, aucun ticket ne peut être pris en charge.

### **4.1.1 Modèle de statut des guichetss**

Chaque guichet dans Queco possède l'un des quatre statuts à tout moment.
Comprendre ces statuts est essentiel aussi bien pour les agents gérant
leur poste de travail que pour les responsables supervisant le flux des
files d'attente.

| **Statut** | **Indicateur de couleur** | **Signification**                                                                                                                    |
|------------|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| **Ouvert** | Vert                      | Le guichet est actif et disponible. Les tickets y sont acheminés. L'agent est connecté et prêt.                                      |
| **Pause**  | Amber                     | Le guichet est temporairement en pause (ex. : déjeuner). Aucun nouveau ticket ne lui est acheminé. Il peut être rouvert par l'agent. |
| **Close**  | Gris                      | Le guichet est hors ligne. Aucun ticket ne peut lui être acheminé. Typique en fin de service ou lorsqu'un guichet est désaffecté.    |

NB : *L'ouverture ou la fermeture de tous les guichets d'une agence est
effectuée par le super administrateur ou par toute personne ayant le
rôle de gestion des guichets.*

|                                                                                                                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="../images/image12.png"                                                                                                                                
 style="width:7.21057in;height:1.47986in" />*Figure 4.1 — Grille des statuts des guichets sur le tableau de bord du responsable (code couleur Ouvert / Fermé)*  |

## 4.2 Création d'un guichet

Les guichets doivent être créés avant que les agents puissent commencer
à traiter les tickets. Seuls les super administrateurs et les
responsables peuvent créer et attribuer des guichets à un utilisateur
particulier dans une agence. Chaque guichet appartient à exactement une
agence et un utilisateur, et peut prendre en charge un ou plusieurs
services.

### 4.2.1 Étape par étape : Créer un nouveau guichet

**Étape 1 :** Depuis la barre latérale gauche, cliquez sur « Agence »

*La liste des agences actives s'affichera.*

**Étape 2 :** Choisissez l'agence spécifique dans laquelle vous
souhaitez créer un guichet et cliquez dessus.

**Étape 3 :** Accédez à la gestion des guichets et cliquez sur le bouton
vert « +Ajouter » situer dans le coin supérieur de la carte.

**Étape 4 :** Un formulaire contextuel apparaîtra, remplissez tous les
champs requis.

**Étape 5 :** Dans la section Services, sélectionnez tous les services
que ce guichet est autorisé à traiter.

*Un guichet doit être lié à au moins un service pour recevoir
l'acheminement des tickets.*

**Étape 6 :** Assignez éventuellement un agent dans le champ «
Utilisateur assigné »

*Vous pouvez également assigner l'agent ultérieurement.*

**Étape 7 :** Cliquez sur Enregistrer.

*Le guichet est créé avec le statut Fermé. Il ne recevra aucun ticket
tant qu'un administrateur ne l'aura pas ouvert.*

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><blockquote>
<p><img src="../images/image13.png"
style="width:6.24931in;height:4.05208in" /></p>
</blockquote></td>
</tr>
</tbody>
</table>

|         |                                                                                                                                                                                                                                                                |
|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **TIP** | Nommez vos guichets de manière claire et cohérente (ex. : « Guichet A », « Fenêtre 3 », « Bureau Paiements »). Les agents voient le nom de leur guichet sur leur tableau de bord chaque jour un bon nommage réduit la confusion pendant les périodes chargées. |

### 4.2.2 Référence des champs du formulaire de guichet

| **Champ**               | **Description**                                                                                         | **Statut**      |
|-------------------------|---------------------------------------------------------------------------------------------------------|-----------------|
| **Nom du guichet**      | Nom affiché aux agents sur leur tableau de bord et sur les écrans d'affichage clients.                  | **Obligatoire** |
| **Utilisateur assigne** | L'agent responsable de ce guichet. Peut être laissé vider et assigné ultérieurement.                    | **Optionnel**   |
| **Services**            | Un ou plusieurs services que ce guichet peut traiter. Seuls les services liés y acheminent les tickets. | **Obligatoire** |

|             |                                                                                                                          |
|-------------|--------------------------------------------------------------------------------------------------------------------------|
| **WARNING** | Si vous créez et assignez un guichet à la mauvaise agence, vous devez le supprimer et le recréer dans l'agence correcte. |

## 4.3 Assigner des guichets aux agents

Chaque guichet doit être assigné à un agent. L'agent assigné voit le
guichet sur son tableau de bord et est responsable de son ouverture au
début de son service. Un agent ne peut être assigné qu'à un seul guichet
à la fois.

### 4.3.1 Assigner ou réassigner un agent après la création

Lors du processus de création du guichet (Section 4.2.1, Étape 6), vous
pouvez sélectionner un agent dans le menu déroulant « Utilisateur
assigné ». Seuls les utilisateurs ayant le rôle d'Agent dans la même
agence apparaissent dans cette liste.

### 4.3.2 Assigner ou réassigner un agent après la création

**Étape 1 :** Depuis la barre latérale, cliquez sur « Agences » et
choisissez l'agence dans laquelle vous avez créé le guichet.

**Étape 2 :** Accédez à la gestion des guichets et localisez le guichet
créé.

**Étape 3 :** Sur le guichet créé, cliquez sur le bouton « personnes
vertes » et un formulaire apparaîtra avec un menu déroulant des
utilisateurs assignés à cette même agence.

Seuls les agents de la même agence sont affichés. Si aucun agent
n'apparaît, vérifiez que des comptes agents ont été créés pour cette
agence (Chapitre 3 Section 3.4).

**Étape 4 :** Cliquez sur Enregistrer.

Les modifications prennent effet à la prochaine connexion de l'agent ou
au prochain rafraîchissement du tableau de bord.

|          |                                                                                                                                                                                                                                        |
|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **NOTE** | Si aucun agent n'est affecté à un guichet, celui-ci reste au statut « Fermé » et n'accepte aucun ticket. Assurez-vous toujours que chaque guichet actif dispose d'un agent affecté avant le début du service (ou du quart de travail). |

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><img src="../images/image14.png"
style="width:3.89583in;height:2.88717in" /></p>
<p><em>Figure 4.3 Vue d'édition du profil du guichet affichant le menu
déroulant Utilisateur assigné</em></p></td>
</tr>
</tbody>
</table>

### 4.3.3 Désassigner un agent

Pour retirer temporairement un agent d'un guichet sans supprimer le
guichet :

**Étape 1 :** Accédez à la gestion des guichets, localisez le guichet
créé et cliquez sur le bouton « icône personnes rouge ».

**Étape 2 :** Cliquez sur Supprimer. Les modifications prennent effet
immédiatement.

|         |                                                                                                                                                                                                                             |
|---------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **TIP** | Utilisez la désassignation plutôt que la désactivation lorsqu'un agent est temporairement absent (congé maladie, vacances). Cela permet de conserver le guichet intact et de le réassigner rapidement au retour de l'agent. |

## 4.4 Ouverture et fermeture d'un guichet

L'ouverture d'un guichet marque le début d'une session de service. Les
tickets commencent à être acheminés vers le guichet uniquement après son
ouverture. La fermeture d'un guichet met fin à la session et arrête tout
nouvel acheminement de tickets. Il s'agit d'un flux de travail quotidien
effectué par l'agent assigné, bien que les responsables puissent
également effectuer cette action à distance. Seul l'administrateur ayant
le rôle d'ouverture ou de fermeture d'un guichet peut effectuer cette
action.

**4.4.1 Ouverture d'un guichet fermé (Agent)**

**Étape 1 :** Connectez-vous à Queco en tant que super administrateur.

**Étape 2 :** Sur votre tableau de bord administrateur, localisez le
widget Agence et repérez le guichet fermé dans l'agence concernée.

Il affiche le numéro du guichet avec la mention FERMÉ en surbrillance
grise.

**Étape 3 :** Cliquez sur l'icône verte ressemblant à une icône d'écran
pour Ouvrir le guichet.

**Étape 4 :** Une boîte de dialogue de confirmation apparaît, cliquez
sur Ouvrir pour continuer.

Le statut du guichet passe à Ouvert (vert). Les tickets de la file
d'attente sont désormais acheminés vers votre guichet.

### 4.4.2 Mise en pause d'un guichet

Utilisez la fonction pause pour les courtes pauses (ex. : déjeuner,
etc.)

**Étape 1 :** Connectez-vous en tant qu'agent.

**Étape 2 :** Dans la barre supérieure du guichet, localisez le bouton
pause/lecture et cliquez dessus. Le guichet sera mis en pause et le
minuteur de pause s'activera automatiquement.

Ceci est pratique pour les pauses.

|          |                                                                                                                                                                                                    |
|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **NOTE** | Les guichets en pause sont exclus du calcul du temps d'attente moyen pendant la période de pause. Cela évite d'augmenter artificiellement les temps d'attente lorsqu'aucun agent n'est disponible. |

### 4.4.3 Fermeture d'un guichet

Les responsables peuvent ouvrir ou fermer n'importe quel guichet de leur
agence à distance, ce qui est utile lorsqu'un agent est absent de
manière inattendue ou ne répond pas. Pour les étapes suivantes, veuillez
consulter la section 4.4.1.

Suivez les mêmes étapes, identifiez le guichet ouvert que vous souhaitez
fermer, cliquez sur l'icône d'écran rouge sur la barre du guichet et
confirmez la boîte de dialogue.

|          |                                                                                                                                                                                                      |
|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **NOTE** | Lorsqu'un guichet est fermé, l'agent se connectera mais ne verra pas ses guichets et un message l'informera de contacter l'administrateur ou lui indiquera qu'une action administrative est requise. |

## 4.5 Gestion des guichets

Toute la gestion des guichets est effectuée par le super administrateur
et l'administrateur, ou par toute personne disposant du rôle et des
permissions nécessaires. Tous les guichets sont gérés en correspondance
avec leur agence spécifique, c'est-à-dire que chaque guichet appartient
à une agence particulière. Ainsi, pour gérer un guichet ou effectuer
toute action spécifique sur un guichet, vous devez d'abord localiser son
agence avant le guichet.

### 4.5.1 Actions de gestion des guichets

| **Action**                       | **Comment l'effectuer**                                                                                                                                                                                     |
|----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Modifier le nom du guichet       | Cliquez sur le nom du guichet → cliquez sur Modifier → modifiez les champs → cliquez sur Enregistrer.                                                                                                       |
| Réassigner un agent              | Ouvrez le guichet → Modifier → changez l'Utilisateur assigné → Enregistrer. Voir Section 4.3.2.                                                                                                             |
| Ajouter / Supprimer des services | Localisez le guichet → cliquez sur le menu déroulant du guichet → cliquez sur Ajouter pour ajouter un service attribué à ce guichet.                                                                        |
| Désactiver                       | Sur le guichet → cliquez sur le bouton icône d'écran rouge et confirmez la boîte de dialogue. Le guichet passe en statut Fermé et est masqué des tableaux de bord des agents. Réactivez de la même manière. |

### 4.5.2 Mise à jour des services d'un guichet

Si votre agence élargit son offre de services, vous devrez peut-être
ajouter de nouveaux services aux guichets existants. La suppression d'un
service d'un guichet empêche les nouveaux tickets de ce type d'y être
acheminés, mais n'affecte pas les tickets déjà en file d'attente.

**Étape 1 :** Localisez le guichet et cliquez sur le menu déroulant du
guichet.

L'administrateur devra assigner ou allouer un service particulier à un
guichet avant de pouvoir l'ajouter et l'activer.

**Étape 2 :** Dans la section services, activez ou désactivez un service
à l'aide de la case à cocher.

|         |                                                                                                           |
|---------|-----------------------------------------------------------------------------------------------------------|
| **TIP** | Un guichet peut traiter plusieurs services, qui ne peuvent être assignés que par le super administrateur. |

## 4.6 Bonnes pratiques des guichets

Le respect de ces pratiques contribuera à garantir un fonctionnement
quotidien fluide et une qualité de service cohérente dans toutes vos
agences.

> **Pour les responsables**

- Créez au moins deux guichets par service actif afin que si un agent
  est absent, le service puisse continuer sans interruption.

- Consultez la grille des statuts des guichets sur le tableau de bord du
  responsable au début de chaque journée pour vérifier que tous les
  guichets sont correctement ouverts.

- Surveillez les guichets présentant des taux d'occupation élevés, car
  cela peut indiquer la nécessité d'un guichet supplémentaire pour ce
  service.

- Définissez une taille maximale de file d'attente sur les guichets pour
  éviter les files d'attente incontrôlées pendant les heures de pointe.
  Lorsque le plafond est atteint, les nouveaux tickets sont maintenus
  dans un pool général jusqu'à ce que la capacité se libère.

> **Pour les agents**

- Terminez toujours le ticket En cours du client actuel avant de mettre
  en pause ou de vous déconnecter de votre guichet.

- Si vous constatez que votre file d'attente s'allonge plus vite que
  vous ne pouvez la traiter, alertez votre responsable via la
  notification de la plateforme ou par message direct n’ignorez pas
  simplement la file d'attente.

- Déconnectez-vous toujours correctement ne fermez jamais simplement
  l'onglet du navigateur. Le délai de fermeture automatique peut
  entraîner des lacunes dans l'acheminement des tickets.

## 4.7 Résumé du chapitre

Ce chapitre a couvert le cycle de vie complet d'un guichet dans Queco,
de la création à l'exploitation quotidienne jusqu'à la gestion à long
terme. À présent, vous devriez être en mesure de :

1.  Créer des guichets avec les valeurs de champs correctes et les
    assignations de services appropriées.

2.  Assigner des agents aux guichet et les réassigner en fonction des
    changements de personnel.

3.  Ouvrir, mettre en pause et fermer les guichets en suivant la
    procédure correcte.

4.  Appliquer les bonnes pratiques pour maintenir les guichets en
    fonctionnement efficace.

*Chapter 5*

