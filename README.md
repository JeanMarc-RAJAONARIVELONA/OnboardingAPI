# OnboardingAPI

Ceci contient mon devoir API concernant l'exercie OnboardingAPI

# Petstore Link

[You can see here the UI in Petsore](https://petstore.swagger.io/?url=https://gist.githubusercontent.com/JeanMarc-RAJAONARIVELONA/be234a2576a12e4124b0efd087207486/raw/abeaddec3a0667c41448cad97b9be8c8a9cb8c73/gistfile1.txt)

## Cette API fournit deux points de terminaison :

- /Student : Obtenir une liste de tous les étudiants.
- /Student : Ajouter un nouvel étudiant.

### Obtenir une liste de tous les étudiants

    Pour obtenir une liste de tous les étudiants, faites une demande GET au point de terminaison /Student. La réponse sera un tableau JSON d'objets, chacun représentant un étudiant.

### Ajouter un nouvel étudiant

Pour ajouter un nouvel étudiant, faites une demande POST au point de terminaison /Student avec un objet JSON dans le corps de la demande. L'objet doit avoir les propriétés suivantes :

    - id: L'identifiant de l'étudiant.
    - name: Le nom de l'étudiant.
    - email: L'adresse e-mail de l'étudiant.
    - birthdate: LE date d'anniversaire de l'étudiant

### La réponse à une demande POST réussie sera un objet JSON avec les propriétés suivantes :

    - id: L'identifiant de l'étudiant nouvellement créé.
    - name: Le nom de l'étudiant nouvellement créé.
    - email: L'adresse e-mail de l'étudiant nouvellement créé.
    - birthdate: LE date d'anniversaire de l'étudiant
