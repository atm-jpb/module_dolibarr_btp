# Change Log
All notable changes to this project will be documented in this file

## UNRELEASED

## 1.3

- FIX : warning php 8 pdf btp *26/01/2023* - 1.3.4
- FIX : dédoublement de la ref commande dans note_public lors de la génération des pdf 'crabe_btp' & 'sponge_btp' *05/10/2022* - 1.3.3
- FIX : fatal error dans le modèle sponge_btp dû à une fuite de mémoire - *04/08/2022* - 1.3.2
  - suppression de caches inutiles
  - optimisation des calculs en boucle
- FIX : taille du tableau préliminaire variable - *29/06/2022* - 1.3.1
- NEW : Intégration bénéfice prévisionnel sur vue d'ensemble chantier - *31/05/2022* - 1.3.0  
  *(récupération de 8.0_btp)* 

## 1.2

- FIX : Compatibilité v16 : this->family *09/06/2022* - 1.2.1
- NEW : Nouvelle configuration *14/01/2022* - 1.2.0  
  Ajoute une configuration pour que les marges présentes dans le tableau des cmd, propal, factures
  tiennent compte de la part de produits / services disponibles dans les ouvrages et sous ouvrages des lignes

## 1.1

- FIX : Changement de la valeur de retour par défault dans le cas d'une retenue de garantie à 0% qui provoquait une incohérence entre les deux lignes TTC sur pdf_sponge_btp - 19/11/2021 - *1.1.9*
- FIX : Traduction sur facture de situation *26/06/2021* - 1.1.8
- FIX : module descriptor (v14 compatibility) *30/06/2021* - 1.1.7
- FIX : Remove useless dependency for workstation *29/06/2021* - 1.1.6
- FIX : V13 GETPOST compatibility *08/03/2021*
