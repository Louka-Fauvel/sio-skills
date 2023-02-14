# [A 1.5] Mise à disposition des utilisateurs d'un service informatique

---
## Test d'intégration et d'acceptation d'un service

---
### Stage chez Fime
**Projet :** 2

**Mission :** 2 (Frontend)

**Objectif :** modification d'un formulaire

J'ai réalisé des tests d'intégration pour les nouvelles modifications.

**Projet :** 2

**Mission :** 3 (Frontend)

**Objectif :** Ajouter une nouvelle itération dans un projet fermé grâce à 
un nouveau bouton

J'ai ajouté les tests pour vérifier si les nouvelles fonctionnalités sont 
aux normes et qu'il n'y ait pas d'erreur.
![Fime projet 2 mission 3](./doc/fime_projet_2_mission_3_test_1.png)
![Fime projet 2 mission 3](./doc/fime_projet_2_mission_3_test_2.png)
![Fime projet 2 mission 3](./doc/fime_projet_2_mission_3_test_3.png)

**Projet :** 2

**Mission :** 5 (Frontend)

**Objectif :** Ajouter le nom de l'entreprise lors d'un commentaire

J'ai réalisé des tests d'intégration pour les nouvelles modifications.

---
## Déploiement d'un service

---
### CRM
Madame JPF est sophrologue. Elle n'est absolument pas informatisée et
réalise tous ses documents à la main. Elle n'effectue aucun devis.
Sa clientèle se forme grâce au bouche à oreille.
Elle souhaitait dans un futur proche avoir un site internet.
J'ai essayé de lui proposer un logiciel pour l'aider à gérer
son activité.

La cliente attendait un logiciel qui lui permettrait de gérer ses contacts et
l'emplacement des documents de ses patients pour mieux les retrouver.
Elle souhaitait également établir des factures en toute simplicité.

Après une étude des besoins de la cliente et des différents logiciels,
je lui ai préparé un CRM avec Agile CRM.


#### Les cas d'utilisation
La cliente souhaite grâce à une application simple et peu onéreuse :

- Créer des nouveaux patients/contacts et des documents préfabriqués

- Assigner des documents à ses contacts

- Établir et imprimer des factures

**1er cas d'utilisation**

- <u>Objectif</u> : Gestion des nouveaux contacts
- <u>Déroulement</u> :
  - <u>Créer des nouveaux contacts</u> : en ajoutant le nom du patient, 
  ses coordonnées (adresse, ville, téléphone, mail)
  - <u>Supprimer des contacts</u> : si besoin

![WebPOO](./doc/crm_nouveau_contact.png)<br>
Créer des nouveaux contacts

![WebPOO](./doc/crm_supprimer_contact.png)<br>
Supprimer des contacts

**2ème cas d'utilisation**

- <u>Objectif</u> : Gestion des documents préfabriqués
- <u>Déroulement</u> :
  - <u>Créer des documents préfabriqués</u>
    - <u>Fiche de renseignement</u> : on retrouve les coordonnées du contact, 
    son âge, le nom du médecin traitant et un commentaire si besoin.
    - <u>Fiche de consultation</u> : cela comprend les Infos de la première 
    consultation, les problèmes du client, ses difficultés, ses maladies, 
    ses symptômes, ses éventuels traitements...
    - <u>Fiche de protocole</u> : elle contient les exercices à faire 
    en séance ou à la maison ainsi que les progrès et rechutes du patient.
    - <u>Factures</u> : une facture différente pour chaque séance. 
    Le patient doit régler en chèque ou espèces à la fin de chaque séance. 
    Le prix est affiché dans le cabinet donc pas besoin de devis.
  - <u>Modifier ou supprimer un document préfabriqué</u>

![WebPOO](./doc/crm_fiche_renseignement.png)
Fiche de renseignement

![WebPOO](./doc/crm_fiche_consultation.png)
Fiche de consultation

![WebPOO](./doc/crm_fiche_protocole.png)
Fiche de protocole

![WebPOO](./doc/crm_fiche_facture.png)
Factures

![WebPOO](./doc/crm_modifier_supprimer.png)<br>
Modifier ou supprimer un document préfabriqué


**3ème cas d'utilisation**

- <u>Objectif</u> : Gestion des documents pour un client
- <u>Déroulement</u> :
  - <u>Créer des documents pour un client</u> : en remplissant l'un des 
  documents préfabriqués et en l'assignant à un patient. Il se classe 
  automatiquement dans le fichier du patient. On peut retrouver tous 
  les documents d'un même patient au même endroit.
  - <u>Modifier ou supprimer un document pour un client</u>

![](./doc/crm_modifier_document.png)

**4ème cas d'utilisation**

- <u>Objectif</u> : Gestion des factures
- <u>Déroulement</u> :
  - <u>Modifier la facture</u> à chaque séance
  - <u>Imprimer la facture ou l'envoyer directement par mail</u>

![](./doc/crm_facture_imprimer.png)

Depuis, la cliente utilise mon service. 
Elle m'a également demandé des évolutions. 

### WebPOO
Réalisation d'un réseau social pour des étudiants.

<u>Cas d'utilisations</u> :

- Créer ou modifier un compte étudiant

- Avoir une photo de profil

- Créer un message à propos de nous

<u>Langages utilisés</u> : HTML, PHP, CSS

<u>Outils utilisés</u> : Bootstrap, Serveur XAMPP

![WebPOO](./doc/webpoo.png)
Ce projet n'est pas en ligne. 


---
## Accompagnement des utilisateurs dans la mise en place d'un service

---
### Refonte-Site-Artiste
Réalisation d'une [documentation](https://github.com/Louka-Fauvel/Refonte-Site-Artiste/blob/master/document/Documentation%20Client.pdf) pour faciliter la navigation et 
l'utilisation du site par l'artiste.

Elle contient :
- les contacts administrateur et cliente
- le mode d'emploi :
  - pour accéder au site
  - pour accéder au tableau de bord
  - pour éditer un article
  - pour ajouter ou retirer des photos dans les galeries

[![Refonte-Site-Artiste documentation client](./doc/refonte-site-artiste_doc.png)](https://github.com/Louka-Fauvel/Refonte-Site-Artiste/blob/master/document/Documentation%20Client.pdf)
![Refonte-Site-Artiste documentation client](./doc/refonte-site-artiste_doc2.png)

### CRM
Réalisation d'une [documentation](http://www.louka-fauvel.fr/assets/doc/Documentation_Client.pdf) de 9 pages pour faciliter l'expérience utilisateur 
de la cliente.

Elle contient : 
- les contacts administrateur et cliente
- le mode d'emploi :
  - pour accéder au site
  - pour créer ou supprimer un contact
  - pour créer ou document préfabriqué
  - pour créer ou supprimer un document pour un client
  - pour imprimer une facture

[![CRM documentation client](./doc/crm_doc.png)](http://www.louka-fauvel.fr/assets/doc/Documentation_Client.pdf)
![CRM documentation client](./doc/crm_usage.png)

### WebPOO
Réalisation d'un [tuto vidéo](https://www.youtube.com/watch?v=LMfGrRpgTtk) pour améliorer l'expérience utilisateur 
des étudiants.

[![Tuto WebPOO](./doc/webpoo_video.png)](https://www.youtube.com/watch?v=LMfGrRpgTtk)