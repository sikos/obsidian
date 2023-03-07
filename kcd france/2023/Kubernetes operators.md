---
type: meetup
date: 07/03/2023
---


Stephane Philippart (OVH)

principe de base : ressembler a un operateur humain (tache manuel).
kubernestes : possibilité d étendre les API de kubernetes via CRD.

CRD : sorte de schéma, definition d instance pour l'utilisation

élément centrql du pattern controleur pour la vérfication d un état du système. En général, gère une seul application (simplification de la gestion)

---
3 niveaux d operqteur :
- installation
- sauvegqrde / restauration
- oberservabilité
---
un controleur est un pod qui exécute un pod, ce qui perme l utilisation d'un frqmework pour la 
contruction.
un des operteur le plus utilisé  "operator SDK"" qui est basé sur kubebuilder

génération des CRD et des controleur. / pqckqging de l'opérateur 

integration natif springboot / quarkus

---


\