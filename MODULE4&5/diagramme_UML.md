***1.Diagramme des cas d'utilisation***
![UseCaseDiagram1](https://github.com/dylanoufelie/tp_web/assets/95092448/a9646f26-5beb-4057-9a32-6e4dc4270811)

a. **Cas d'utilisation principal : Se Connecter, S'enregistrer et Accéder au Tableau de Bord**
   - **Acteurs :** Utilisateur
   - **Description :** L'utilisateur a la possibilité de se connecter après s'enregistrer avec succès et est redirigé vers son tableau de bord.
   - **Scénario Principal :**
     1. L'utilisateur choisit l'option de s'enregistrer.
     2. Le système affiche le formulaire d'enregistrement.
     3. L'utilisateur entre les informations d'enregistrement.
     4. Le système vérifie et enregistre les informations d'utilisateur.
     5. Si l'enregistrement réussit, l'utilisateur est redirigé vers la page de connexion.
     6. L'utilisateur entre ses identifiants.
     7. Le système vérifie les informations d'identification.
     8. Si la connexion réussit, l'utilisateur est redirigé vers son tableau de bord.

b. **Cas d'utilisation inclus : Visualiser le Tableau de Bord**
   - **Acteurs :** Utilisateur
   - **Description :** L'utilisateur visualise les informations présentées sur son tableau de bord.
   - **Scénario Principal :**
     1. L'utilisateur est connecté.
     2. Le système affiche les informations pertinentes sur le tableau de bord.

c. **Cas d'utilisation étendu : Modifier le Profil depuis le Tableau de Bord**
   - **Acteurs :** Utilisateur
   - **Description :** L'utilisateur a la possibilité de modifier son profil directement depuis le tableau de bord.
   - **Scénario Principal :**
     1. L'utilisateur est connecté.
     2. Le système affiche les informations du tableau de bord.
     3. L'utilisateur choisit l'option de modification du profil.
   - **Scénario d'Extension :**
     - Si l'utilisateur choisit de modifier son profil depuis le tableau de bord, il étend le cas d'utilisation principal "Se Connecter et Accéder au Tableau de Bord".

***2.Diagramme d'activité***  
a. diagramme d'activité du système dans le cas d'un utilisateur déja enregistré.  
![image](https://github.com/yugmerabtene/ESIEA-FISE-WEB-2024/assets/3670077/4c00f24f-c965-4ba6-b8ce-1e048217707a)  

***3.Diagramme de séquence***  
![SequenceqDiagram](https://github.com/dylanoufelie/tp_web/assets/95092448/653b9792-2c6a-4d78-84ef-68afbe0b387b)

***4.Diagramme de flux du système**
![image](https://github.com/yugmerabtene/ESIEA-FISE-WEB-2024/assets/3670077/bc2c4626-aafd-4bdb-b570-154f4ac6ec87)  
  
***5.ERD (Entity Relational Diagram)***  

![ERD](https://github.com/dylanoufelie/tp_web/assets/95092448/bced4c2e-7016-4cfb-ab62-177cf2d80fa5)
