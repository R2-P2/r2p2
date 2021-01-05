# R2-P2 CNRS Prime Project
## Analyse de données multi-modales pour les Pathologies complexes par la conception et l’implémentation de Protocoles Reproductibles et Réutilisables
L’étude de pathologies telles les anévrismes intracrâniens nécessite l’utilisation d’une grande variété de données et la conception de protocoles d’analyse complexes. La diversité de leurs implémentations rend leur maintenance et partage difficile et limite la confiance des biologistes dans les données produites. Reproduire et réutiliser les protocoles est pourtant crucial pour comparer systématiquement les résultats biologiques, adapter des protocoles à de nouvelles problématiques et répondre aux exigences des plans de gestion de données. R2-P2 fournit (i) une large bibliothèque de protocoles organisés, (ii) un module de conception et d’exécution de protocoles reproductibles, réutilisables et citables (conception d’algorithmes d’indexation et de recherche efficace de motifs dans les graphes formés par les workflows implémentant les protocoles), (iii) une évaluation de l’approche sur de nouveaux jeux de données et (iv) un ensemble de critères FAIR pour les protocoles.

By Lucie Biton
Creative Commons License
This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivs 2.0 France License.

## Objectifs du projet
R2-P2 a un double objectif (i) concevoir un cadre pour la conception, l’implémentation, et l'exécution de protocoles d’analyse de données reproductibles et réutilisables pour l’étude des anévrismes intracrâniens et (ii) démontrer l'intérêt de cette approche en ré-utilisant et adaptant les protocoles obtenus en (i) sur des données générées dans de nouveaux projets. Sur le plan informatique, R2-P2 apporte des solutions concrètes à la définition de protocoles FAIR, avec un focus sur les composantes R (réutilisation des protocoles) et F (indexation des protocoles). Les contributions informatiques attendues seront relatives à la conception i)  d’algorithmes d’indexation et de recherche efficace de motifs dans les graphes formés par les workflows et ii) la conception et l’implémentation d’outils d’aide à la réutilisation (et à la citation) de workflows. Sur le plan applicatif, R2-P2 fournit des solutions concrètes pour documenter automatiquement les données produites par les protocoles annotés, tel qu’attendu dans un Data Management Plan. R2-P2 fournit un cadre d’échange de protocoles compréhensibles par les pairs, il démontrera sa capacité à réutiliser et adapter facilement des protocoles complexes développés dans un projet sur les données d’un nouveau projet. 

## Partenaires
- LISN : Laboratoire Interdisciplinaire des sciences du Numérique, équipe bioinformatique (UMR CNRS 9015),
- ITX : Institut du thorax, équipe de génétique (UMR CNRS 6291);
- CHU de Nantes, Service de neuroradiologie interventionnelle, 
- Institut Pasteur, C3BI (USR 3756)
- Lamsade : Laboratoire d'Analyse et de Modélisation de Systèmes d'Aide à la Décision (UMR 7243) 

## Bilan de la première année
- Définition de workflows FAIR
  - Participation active à des sessions de groupes de travail et workshops nationaux et internationaux autour de la thématique de worklows FAIR. L’objectif ici est de mieux comprendre les utilisateurs des workflows et leurs besoins, de dégager les manques des systèmes de workflows actuels pour être plus (ré)utilisables et de mettre en évidence les verrous à la fois technologiques mais aussi de recherche en informatique qu’il convient de pouvoir lever pour tendre vers la conception de workflows FAIR. Un article accepté en 2019 sur ces thématiques a été publié cette année [1].
  - Journée de la conférence Internationale de Bioinformatique ECCB “Workshop on FAIR Computational Workflows” [expose1]
  - Animation et la participation à une une session de la conférence FAIR [expose2];
  — Participation à la journée  “Outils et environnements FAIR pour la Bioanalyse” [expose3] organisée par les plateformes bioinformatique du réseau BioGenOuest. 
- Provenance et Annotation sémantique de données
  - “FAIRification” de données biomédicales [5].  
- Analyse de données  (ITX, CHU Nantes)
  - Identification de 17 facteurs de risques génétiques [2] qui s'appuie sur les études d’association pan-génomoiques (GWAS).
  - Analyse d’images médicales visant à caractériser la géométrie du réseau vasculaire cérébral [3]. 
  - Analyse de données cliniques du projet ICAN permettant de mettre en évidence l’importance de la localisation de l’anévrisme dans le risque de rupture [4].  Les processus d’analyse de données biostatistiques et de modélisation prédictive (apprentissage machine) peuvent également bénéficier de la notion de workflows FAIR, car ils se prêtent aisément à la représentation sous forme de workflows scientifique.

## Publications et exposés des équipes du projet 
- [1] Carole A. Goble, Sarah Cohen-Boulakia, Stian Soiland-Reyes, Daniel Garijo, Yolanda Gil, Michael R. Crusoe, Kristian Peters, Daniel Schober: FAIR Computational Workflows. Data Intelligence  2(1-2): 108-121 (2020). https://doi.org/10.1162/dint_a_00033
- [2] Bakker, M.K., van der Spek, R.A.A., van Rheenen, W. et al. Genome-wide association study of intracranial aneurysms identifies 17 risk loci and genetic overlap with clinical risk factors. Nat Genet (2020). https://doi.org/10.1038/s41588-020-00725-7
- [3] A. Nouri, F. Autrusseau, R. Bourcier, A. Gaignard, V. L’allinec, C. Menguy, J. Véziers, H. Desal, G. Loirand, R. Redon. Characterization of 3D bifurcations in micro-scan and MRA-TOF images of cerebral vasculature for prediction of intra-cranial aneurysms, Computerized Medical Imaging and Graphics, Volume 84, 2020, 101751, ISSN 0895-6111, https://doi.org/10.1016/j.compmedimag.2020.101751
- [4] Rousseau O, Karakachoff M, Gaignard A, et al. Location of intracranial aneurysms is the main factor associated with rupture in the ICAN population. Journal of Neurology, Neurosurgery & Psychiatry  Published Online First: 23 October 2020. https://doi.org/10.1136/jnnp-2020-324371
- [5] Gaignard, Alban, Skaf-Molli, Hala, and Belhajjame, Khalid. ‘Findable and Reusable Workflow Data Products: A Genomic Workflow Case Study’. 1 Jan. 2020 : 751 – 763.  https://doi.org/10.3233/SW-200374
- [6] L'Allinec V, Chatel S, Karakachoff M, Bourcereau E, Lamoureux Z, Gaignard A, Autrusseau F, Jouan S, Vion AC, Loirand G, Desal H, Naggara O, Redon R, Edjlali M, Bourcier R. Prediction of Unruptured Intracranial Aneurysm Evolution: The UCAN Project. Neurosurgery. 2020 Jul 1;87(1):150-156. https://doi.org/10.1093/neuros/nyaa093. PMID:32374868.
- [expose1] ECCB 2020 - WORKSHOP FAIR Computational Workflows : Sarah Cohen-Boulakia (keynote) https://eccb2020.info/ntbew01-workshop-on-fair-computational-workflows/
- [expose2] International FAIR Convergence Symposium 2020 - Session on FAIR  WORKFLOWS Organizers : Sarah Cohen-Boulakia, Carole Goble, Daniel Garijo. Speaker (flash) : Alban Gaignard https://conference.codata.org/FAIRconvergence2020/sessions/218/
- [expose3] Journée outils et environnements FAIR pour la bioanalyse - plateformes BioGenOuest, Speaker : Sarah Cohen-Boulakia https://www.biogenouest.org/evenements/fair-bioanalyse-outils-et-environnements/
