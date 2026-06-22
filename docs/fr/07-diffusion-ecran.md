# Diffusion d’Ecran & Gestion des Affichages

*Comment configurer, gérer et exploiter les écrans d'affichage orientés
clients de la création des écrans et des playlists à la planification du
contenu média et à la surveillance de l'état des écrans.*

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Dans ce Chapitre</strong></p>
<ul>
<li><p>7.1 Qu'est-ce que la Diffusion d'écran ?</p></li>
<li><p>7.2 Anatomie de l'écran de diffusion</p></li>
<li><p>7.3 Concepts fondamentaux : Écrans, Playlists &amp;
Médias</p></li>
<li><p>7.4 Gestion des écrans</p></li>
<li><p>7.5 Gestion des playlists</p></li>
<li><p>7.6 Gestion des éléments médias</p></li>
<li><p>7.7 Le Lecteur Comment tout s'assemble</p></li>
<li><p>7.8 Résumé du chapitre</p></li>
</ul></th>
<th><p><strong>Apres ce chapitre vous serez en mesure de</strong></p>
<ul>
<li><p>Expliquer ce que fait la diffusion d'écran</p></li>
<li><p>Identifier les deux zones de l'écran d'affichage</p></li>
<li><p>Comprendre la hiérarchie Écran → Playlist → Média</p></li>
<li><p>Créer et configurer des écrans d'affichage</p></li>
<li><p>Créer des playlists et les attacher aux écrans</p></li>
<li><p>Importer des éléments médias et définir des
planifications</p></li>
</ul>
<ul>
<li><p>Comprendre comment le lecteur récupère et affiche le
contenu</p></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 7.1 Qu'est-ce que la Diffusion d'écran ?

La Diffusion d'écran est le système intégré de gestion des affichages de
Queco. Il contrôle les écrans orientés clients installés dans les salles
d'attente de votre agence les écrans que les clients regardent en
attendant que leur numéro de ticket soit appelé.

Diffusion d'écran est le système intégré de gestion des affichages de
Queco. Il contrôle les écrans orientés clients installés dans les salles
d'attente de votre agence les écrans que les clients regardent en
attendant que leur numéro de ticket soit appelé.

| **Fonction**                  | **Description**                                                                                                                                   |
|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **Visibilité de la file**     | Les clients peuvent voir quels numéros de tickets sont actuellement appelés et à quel guichet, réduisant l'anxiété et évitant les appels manqués. |
| **Diffusion de contenu**      | L'agence peut afficher des images, vidéos, bannières promotionnelles et annonces sur le même écran sans aucune intervention manuelle.             |
| **Contrôle par zone**         | Plusieurs écrans peuvent être déployés dans différentes zones ou étages de l'agence, chacun affichant le contenu pertinent à son emplacement.     |
| **Mises à jour automatiques** | Les écrans se mettent à jour automatiquement lorsqu'un agent appelle un nouveau ticket aucun rafraîchissement manuel n'est nécessaire.            |

**NOTE**

**N**

|          |                                                                                                                                                                                                                                                                               |
|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **NOTE** | La Diffusion d'écran est entièrement gérée depuis la plateforme Queco. Les écrans physiques n'ont besoin que d'un navigateur et d'une connexion internet pour recevoir et afficher le contenu aucune installation de logiciel dédié n'est requise sur l'appareil d'affichage. |

|                                                                                                                                               |
|-----------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="../images/image25.png" />*Figure 7.1 — Écran d'affichage orienté client dans une salle d'attente (exemple de mise en page)*  |

|         |                                                                                                                                                                                                                                                                                                                     |
|---------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **TIP** | Considérez la Zone 1 comme une chaîne TV que votre agence contrôle, diffusant le contenu que vous programmez. La Zone 2 est le tableau de file d'attente en direct elle fonctionne automatiquement au fur et à mesure que les agents traitent les tickets. La Zone 3 est la bannière contextuelle en direct en bas. |

## 7.2 Concepts fondamentaux : Écrans, Playlists et Médias

Avant de configurer quoi que ce soit, il est important de comprendre la
hiérarchie à trois niveaux qui alimente le système d'affichage de Queco.
Chaque contenu visible sur un écran de diffusion passe par cette
structure.

### 7.2.1 La hiérarchie à trois niveaux

| **Level**   | **Entité**    | **Role**                                                                                                                                                                                      |
|-------------|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Level 1** | Écran         | Un appareil d'affichage physique enregistré dans l'agence. Chaque écran possède un code unique utilisé pour récupérer son contenu. Les écrans sont assignés à des zones au sein d'une agence. |
| **Level 2** | Playlist      | Une collection ordonnée d'éléments médias. Une playlist définit ce qui est diffusé sur un écran et dans quel ordre. Un écran peut avoir plusieurs playlists ; une seule est active à la fois. |
| **Level 3** | Élément média | Un contenu individuel une image ou une vidéo avec une durée d'affichage définie. Les éléments médias peuvent avoir des planifications qui contrôlent quand ils apparaissent.                  |

### 7.2.2 Analogie

Pensez-y comme un système de diffusion télévisée :

- L'**Écran** est le téléviseur fixé au mur l'appareil physique que les
  clients regardent.

- La **Playlist** est la chaîne TV un programme de contenu planifié qui
  se diffuse dans l'ordre.

- **Élément média** est une émission ou publicité individuelle une image
  ou clip vidéo dans le programme.

Un écran peut avoir plusieurs playlists (comme un téléviseur avec
plusieurs chaînes), mais une seule playlist est active à tout moment la
playlist courante. Les administrateurs peuvent changer la playlist
active à tout moment.

### 7.2.3 Planification

Les éléments médias supportent une planification basée sur le temps. Une
planification définit une fenêtre pendant laquelle un élément média
spécifique est éligible à la diffusion. En dehors de cette fenêtre,
l'élément est automatiquement ignoré. Cela vous permet d'afficher des
annonces matinales le matin, des offres promotionnelles aux heures de
pointe, et des avis de fermeture en fin de journée sans aucune
intervention manuelle.

## 7.3 Gestion des écrans

Les écrans représentent les appareils d'affichage physiques dans votre
agence. Chaque écran doit être enregistré dans Queco avant de pouvoir
recevoir et afficher du contenu. Seuls les Super Administrateurs et les
Responsables peuvent créer et gérer les écrans.

**7.3.1 Étape par étape : Créer un nouvel écran**

Avant de créer un écran dans une agence, il doit exister un utilisateur
déjà assigné à cette agence sur lequel on active l'option écran, avant
de créer des écrans pour l'agence.

**Étape 1 :** Allez dans « Utilisateurs » et recherchez l'utilisateur
dans l'agence concernée.

**Étape 2 :** Cliquez sur l'icône stylo sur l'utilisateur.

**Étape 3 :** Cochez la case « Utilisateur Écran d'appel » et
enregistrez.

|                                                                                                        |
|--------------------------------------------------------------------------------------------------------|
| <img src="../images/image26.png" />*Figure 7.3 — Activating the screen on a user in an Agency*  |

**Étape 4 :** Allez dans « Gestion des diffusions » dans la barre
latérale.

**Étape 5 :** Filtrez l'agence dans laquelle vous souhaitez créer
l'écran.

**Étape 6 :** Cliquez sur le bouton « + Nouvel écran » et remplissez les
champs.

|                                                                    |
|--------------------------------------------------------------------|
| <img src="../images/image27.png" />*Figure 7.3 New Screen*  |

|         |                                                                                                                                                |
|---------|------------------------------------------------------------------------------------------------------------------------------------------------|
| **TIP** | Pour qu'une agence dispose de plusieurs écrans, elle doit avoir plusieurs utilisateurs, c'est-à-dire qu'un écran est attaché à un utilisateur. |

### 7.4.2 Référence des champs du formulaire d'écran

| **Field**              | **Description**                                                                                        | **Status**      |
|------------------------|--------------------------------------------------------------------------------------------------------|-----------------|
| **Nom de l'écran**     | Nom descriptif de cet écran (ex. : « Écran Hall », « Étage 2 – Zone B »).                              | **Obligatoire** |
| **Code de l'écran**    | Identifiant unique généré automatiquement utilisé par l'URL du lecteur. Non modifiable après création. | **Automatique** |
| **Agence**             | L'agence à laquelle appartient cet écran.                                                              | **Obligatoire** |
| **Zone / Emplacement** | L'emplacement physique de l'écran dans l'agence (ex. : « Hall principal », « Couloir B »).             | **Optionnel**   |
| **Résolution**         | L'utilisateur (Responsable ou Admin) chargé de gérer le contenu de cet écran.                          | **Optionnel**   |
| **Description**        | Notes internes sur cet écran (ex. : « Près de l'entrée, haute visibilité »).                           | **Optionnel**   |
| **Statut**             | Actif ou Inactif. Les écrans inactifs ne reçoivent pas de mises à jour de contenu.                     | **Automatique** |

### 7.3.3 Actions de gestion des écrans

| **Action**           | **Comment l'effectuer**                                                                                  |
|----------------------|----------------------------------------------------------------------------------------------------------|
| Modifier un écran    | Cliquer sur le nom de l'écran → Modifier → modifier les champs → Enregistrer.                            |
| Désactiver           | Basculer le statut de l'écran sur Inactif. L'URL du lecteur cesse de recevoir des mises à jour.          |
| Supprimer            | Cliquer sur (⋮) → Supprimer → confirmer. L'écran et toutes ses associations de playlists sont supprimés. |
| Surveiller le signal | Voir Section 7.4.4 le signal indique si l'écran est actuellement en ligne.                               |

### 7.3.4 Signal de l'écran Surveillance de l'état en ligne

Chaque écran physique envoie périodiquement un signal à Queco pour
confirmer qu'il est en ligne et fonctionnel. Cela permet aux
administrateurs de surveiller l'état de tous les écrans en temps réel
depuis le tableau de bord de gestion des affichages.

| **État du signal**    | **Signification**                                                                |
|-----------------------|----------------------------------------------------------------------------------|
| **En ligne (Vert)**   | L'écran est actif, connecté et reçoit normalement les mises à jour.              |
| **Hors ligne (Gris)** | L'écran n'a pas répondu depuis plus de 5 minutes.                                |
| **Jamais connecté**   | L'écran a été créé mais l'URL du lecteur n'a jamais été ouverte sur un appareil. |

|                                                                                                                                          |
|------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="../images/image28.png" />*Figure 7.5 — Liste des écrans avec indicateurs d'état du signal* |

|          |                                                                                                                                                                                                                                                                        |
|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **NOTE** | Le signal n'affecte pas l'appel des tickets si un écran se déconnecte, les agents peuvent toujours appeler les tickets normalement. Seul l'affichage est affecté. Les clients peuvent ne pas voir les numéros de tickets mis à jour jusqu'à la reconnexion de l'écran. |

## 7.5 Gestion des playlists

Les playlists sont le lien entre votre contenu média et vos écrans
physiques. Une playlist organise les éléments médias en une séquence
ordonnée et détermine ce qui est diffusé sur un écran. Vous pouvez créer
plusieurs playlists pour différentes campagnes, périodes ou zones
d'écran, et basculer entre elles instantanément.

### 7.5.1 Étape par étape : Créer une playlist

**Étape 1 :** Depuis la barre latérale, allez dans Gestion des
diffusions → Playlists.

**Étape 2 :** Cliquez sur « Créer une playlist ».

**Étape 3 :** Saisissez un Nom de playlist et une Description
optionnelle. Exemple : « Campagne Matinale – T1 2025 », « Boucle par
défaut Hall ».

**Étape 4 :** Cliquez sur Enregistrer. La playlist est créée vide.
Ajoutez-y des éléments médias à la Section 7.6

|                                                                                                                           |
|---------------------------------------------------------------------------------------------------------------------------|
| <img src="../images/image29.png" />*Figure 7.6 — Page de liste des playlists avec le bouton Ajouter une playlist*  |

### 7.5.2 Définir la playlist active d'un écran

Un écran peut avoir plusieurs playlists attachées, mais une seule est
active (en cours de diffusion) à tout moment.

**Étape 1 :** Ouvrez le profil de l'écran et allez dans l'onglet
Playlists.

**Étape 2 :** Trouvez la playlist que vous souhaitez activer et cliquez
simplement dessus ; elle deviendra automatiquement la liste en cours de
diffusion avec un bouton « en direct » dessus.

L'écran bascule vers la nouvelle playlist lors de son prochain cycle de
rafraîchissement de contenu (dans les 8 secondes).

|          |                                                                                                                                                                  |
|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **NOTE** | Changer la playlist active ne supprime ni ne détache la playlist précédente elle cesse simplement d'être diffusée. Vous pouvez revenir en arrière à tout moment. |

### 7.5.3 Réorganiser les playlists sur un écran

Lorsque plusieurs playlists sont attachées à un écran, vous pouvez
définir leur ordre de priorité. Cela détermine quelle playlist est
diffusée lorsque la playlist courante se termine ou est désactivée.

**Étape 1 :** Ouvrez le profil de l’ecran → onglet Playlists.

**Étape 2 :** Un bouton fléché est présent sur chaque onglet. Cliquez
sur la flèche vers le haut pour remonter et inversement.

**Étape 3 :** L'ordre est sauvegardé automatiquement.

### 7.5.4 Détacher ou supprimer une playlist d'un écran

**Étape 1 :** Ouvrez le profil de l'écran → onglet Playlists, OU ouvrez
la playlist → onglet Écrans.

**Étape 2 :** Trouvez l'icône de corbeille rouge et cliquez dessus pour
la supprimer.

**Étape 3 :** La suppression s'effectue automatiquement. Si la playlist
détachée était la playlist active, l'écran bascule vers la playlist
suivante dans l'ordre. Si aucune playlist ne reste, l'écran affiche une
zone de contenu vide.

## 7.6 Gestion des éléments médias

Les éléments médias sont les contenus individuels images ou vidéos qui
composent une playlist. Chaque élément possède une durée d'affichage,
une planification optionnelle et un statut qui contrôle s'il est
actuellement actif ou en pause.

### 7.6.1 Étape par étape : Ajouter un élément média à une playlist

**Étape 1 :** Ouvrez la playlist à laquelle vous souhaitez ajouter du
contenu.

**Étape 2 :** Faites défiler jusqu'à la section Éléments médias et
cliquez sur « Ajouter un média ».

**Étape 3 :** Remplissez les champs requis — vous pouvez également
ajouter des photos et des vidéos.

**Étape 4 :** Cliquez sur « Créer l'élément média ». L'élément est
ajouté à la playlist et commence à être diffusé immédiatement si la
playlist est actuellement active sur un écran.

**Étape 5 :** Répétez pour tous les éléments médias nécessaires.
Réorganisez-les si besoin.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><img src="../images/image30.png" /></p>
<p><em>Figure 7.7 — Formulaire d'importation d'élément média dans une
playlist</em></p></td>
</tr>
</tbody>
</table>

|         |                                                                                                                                                                                                                   |
|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **TIP** | Gardez les fichiers images sous 2 Mo et les fichiers vidéo sous 50 Mo pour des performances optimales sur les écrans. Les fichiers volumineux causent des ralentissements et des temps de rafraîchissement lents. |

### 7.6.2 Référence des champs médias

| **Champs**        | **Description**                                                                                                                     | **Statut**       |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------|------------------|
| **Titre**         | Nom interne de cet élément média (ex. : « Bannière Ramadan 2025 »).                                                                 | **Obligatoire**  |
| **Type**          | Choisir entre texte, image ou vidéo.                                                                                                |                  |
| **Fichier média** | Le fichier image (JPG, PNG, GIF) ou vidéo (MP4) à afficher.                                                                         | **Obligatoire**  |
| **Durée**         | Durée d'affichage de cet élément avant de passer au suivant. En secondes (images uniquement les vidéos jouent leur durée complète). | **Obligatoire**  |
| **Contenu**       | Il s'agit du message publicitaire lorsque vous utilisez le type texte.                                                              | **Automatique**  |
| **Statut**        | Choisir entre Brouillon, Actif, En pause, Planifié, Archivé.                                                                        | **Choix manuel** |
| **Planification** | Fenêtre de temps optionnelle pendant laquelle cet élément est éligible à la diffusion. Voir Section 7.6.3.                          | **Optionnel**    |

### 7.6.3 Planifier un élément média

Les planifications permettent à un élément média d'être diffusé
uniquement pendant des fenêtres horaires spécifiques. En dehors de la
fenêtre planifiée, l'élément est automatiquement ignoré aucune
intervention manuelle n'est nécessaire.

**Étape 1 :** Ouvrez l'élément média que vous souhaitez planifier.

**Étape 2 :** Faites défiler jusqu'à la section Planifications et
cliquez sur « Ajouter une planification ».

**Étape 3 :** Définissez-la Date/Heure de début et là Date/Heure de fin
de la fenêtre de planification.

*Exemple : Début - Lundi 09h00, Fin - Lundi 17h00. L'élément ne sera
diffusé qu'entre 9h et 17h le lundi*.

**Étape 4 :** Cliquez sur Enregistrer la planification. Plusieurs
planifications peuvent être ajoutées à un même élément média pour des
fenêtres horaires récurrentes.

|                                                                                                                                                  |
|--------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="../images/image31.png" />*Figure 7.8 — Configuration de la planification d'un élément média avec les sélecteurs de date/heure*  |

|          |                                                                                                                                                                                                                                                                         |
|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **NOTE** | Si un élément média n'a pas de planification, il est diffusé à tout moment lorsque la playlist est active. Les planifications ne font que restreindre la diffusion elles ne forcent pas un élément média à être diffusé en dehors de son ordre normal dans la playlist. |

### 7.6.4 Gestion du statut des éléments médias

Vous pouvez activer ou désactiver des éléments médias individuels sans
les retirer de la playlist. Cela est utile pour mettre temporairement en
pause du contenu saisonnier sans le supprimer.

**Étape 1 :** Ouvrez la playlist et faites défiler jusqu'à la section
Éléments médias.

**Étape 2 :** Sur chaque onglet d'un élément média, vous trouverez une
flèche vers le haut ou vers le bas.

**Étape 3 :** Les modifications prennent effet au prochain cycle de
contenu de l'écran.

## 7.7 Résumé du chapitre

Ce chapitre a couvert l'ensemble du système de Diffusion d'écran dans
Queco de la compréhension de la mise en page des affichages à la
création des écrans, la construction des playlists, l'importation des
médias et la surveillance du lecteur. À présent, vous devriez être en
mesure de :

1.  Expliquer le rôle des deux zones d'affichage le Panneau publicitaire
    et le Panneau des tickets.

2.  Comprendre la hiérarchie Écran → Playlist → Élément média et leurs
    relations.

3.  Créer et configurer des écrans physiques avec les assignations de
    zones correctes.

4.  Créer des playlists, les attacher aux écrans et définir la playlist
    active.

5.  Importer des éléments médias, définir les durées d'affichage et
    configurer des planifications basées sur le temps.

6.  Utiliser la propagation pour diffuser une playlist sur tous les
    écrans de l'agence.

7.  Surveiller l'état des écrans via le signal de connexion.

*Chapter 8*

