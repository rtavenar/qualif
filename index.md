---
layout: default
---

Dossier de qualification aux fonctions de professeur des universités, section 27

* TOC
{:toc}

# Curriculum vitae

## Expérience Professionnelle

- Maître de Conférences, Université de Rennes 2 (Rennes, France), depuis 2013
  - UMR Laboratoire Littoral, Environnement, Télédétection, Géomatique (LETG)
  - Département Informatique et Statistiques (MIASHS)
  - Justificatifs : **TODO**
- Chercheur post-doctoral, Idiap Research Institute (Martigny, Suisse, 2011 - 2013)
  - Équipe _Perception_, dirigée par Dr. Jean-Marc Odobez
  - Bourse du _Swiss National Science Foundation (SNSF)_
- Doctorant, Université de Rennes 1 (Rennes, France, 2007 - 2011)
  - Équipe TexMex (UMR IRISA), dirigée par Dr. Patrick Gros
  - Contrat doctoral (allocation ministérielle, contingent des ENS)
- Stagiaire de recherche, Centrum voor Wiskunde en Informatica -- CWI (Amsterdam, Pays Bas, 2006 - 2007)
  - _Intelligent and Autonomous Systems Department_, dirigé par Prof. Éric Pauwels
  - Allocation d'Élève Normalien de l'ENS Cachan

## Formation

- Habilitation à Diriger des Recherches, Université de Rennes 2 (Rennes, France, 2020)
  - Titre : Apprentissage statistique et séries temporelles
  - Jury :
    - Prof. Élisa Fromont (Université de Rennes 1, présidente)
    - Prof. Florence d'Alché (Telecom Paris, France, rapporteure)
    - Prof. Panagiotis Pappetrou (Université de Stockholm, Suède, rapporteur)
    - Prof. Nicolas Thome (Conservatoire National des Arts et Métiers, rapporteur)
    - Dr. Hervé Jégou (_Facebook AI Research_, examinateur)
    - Dr. Thomas Corpetti (CNRS, garant)
  - Justificatifs :
    - [Attestation de réussite](assets/scans/attestation_reussite_hdr.pdf)
    - Rapports de manuscrit [[F. d'Alché](assets/scans/rapport_hdr_dalche.pdf)] [[P. Papapetrou](assets/scans/rapport_hdr_papapetrou.pdf)] [[N. Thome](assets/scans/rapport_hdr_thome.pdf)]
    - [Rapport de soutenance](assets/scans/rapport_soutenance_hdr.pdf)
- Doctorat, Université de Rennes 1 - Inria / IRISA (Rennes, France, 2011)
  - Titre : Indexation de séries temporelles
  - Directeur de thèse: Dr. Laurent Amsaleg (CNRS)
  - Jury :
    - Prof. Marie-Odile Cordier (Université de Rennes, présidente)
    - Prof. Philippe Joly (Université Paul Sabatier, Toulouse, rapporteur)
    - Prof. Hervé Glotin (Université Sud Toulon Var, rapporteur)
    - Dr. Stéphane Marchand Maillet (Université de Genève, Suisse, examinateur)
    - Dr. Patrick Gros (Inria, co-directeur de thèse)
- Élève normalien, École Normale Supérieure de Cachan -- Antenne de Bretagne (Rennes, France, 2006-2008)
- Diplôme d'ingénieur &amp; Master Recherche, Université de Lyon / École Centrale de Lyon (Lyon, France, 2006)

## Distinctions

- Prime d'Encadrement Doctoral et de Recherche (2017 - 2021) **justificatif TODO**
- Prix du meilleur poster à IDA'17 pour le papier "Learning DTW-Preserving Shapelets" (2017) **justificatif TODO**
- Papier sélectionné en couverture d'une _issue_ de journal : "Fused Gromov-Wasserstein Distance for Structured Objects" (2020) [[justificatif](assets/scans/algorithms_cover_2020.pdf)]
- Sélectionné parmi les meilleurs reviewers (top-10%) pour la conférence NeurIPS 2020 [[justificatif](assets/scans/top_reviewer_neurips_2020.pdf)]

# Liste des pièces justificatives

{% assign scan_files = site.static_files | where: "scan", true %}
{% for p in scan_files %}
* <a href="{{ p.path }}">{{ p.name }}</a>{% endfor %}
