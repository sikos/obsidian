---
type: meetup
date: 07/03/2023
---


mohammed abdennebi (sfeir)

raison : 
- augmentation du nombre d atttaque ~+742% 
- injection de code malicieux (confusion du nom de librairie)

SLSA  (seccurity layer for software artifact) : 
- ensemble de regle
- inspiré pqr binqry authorization for Borg (google)
	- provenance est une attesation 
	- ensemble de regle de surité
---
attestation SLSA :
- ensemble d information sur artifact
	- subject du buld
	- ce qui a permi le build (github action par exemple)
	- intégrité du binaire
	- éventuellement rejouer le buld
- liste de vulnerabilité
- SBOM

---
SLSA L level 2
build signature automatique la provenance des builds

SLSA level 3
les utilisateurs ne peuvent pas falsifier sans acces aux clefs de signature
les job éphémères pour ne pas impacter les job suivant (destruction du job)

---
Sigstore 3 elements :
- cosign : cli de signature
- fulcio : CA de certificat
- rekor : transparency log pour les certificats / signatures

principe de signature keyless pour eviter les soucis de revocation

---
kyverno 
- validation de la provenance