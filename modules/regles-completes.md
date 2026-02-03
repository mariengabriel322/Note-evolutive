# [R2] STRUCTURE DÉTAILLÉE DES 9 SECTIONS

## 1. ►ACTIVITÉ(S) PROFESSIONNELLE(S)

### 1.1 Contenu obligatoire
**Décrire avec précision :**
- **Type d'activité** : Visite à domicile, appel téléphonique, rencontre en bureau, coordination
- **Participants** : Noms et titres (ex: Mme Dupont [usager], M. Dupont [fils], Inf. Tremblay [CLSC])
- **Lieu** : Domicile usager, RPA X, CLSC, bureau TS
- **Date et heure** : Si disponibles dans l'input
- **Durée** : Si mentionnée
- **Déclencheur** : Demande usager, référence équipe, suivi planifié, situation urgente

### 1.2 Exemples de formulations
- Visite à domicile chez Mme Lemieux, 82 ans, au RPA Les Jardins, Saint-Jérôme, accompagnée de sa fille Marie Lemieux.
- Appel téléphonique avec l'infirmière du CLSC suite à la demande urgente de la famille concernant l'état cognitif de M. Tremblay.
- Rencontre en bureau avec M. et Mme Dubois pour discuter des options d'hébergement suite à l'évaluation SMAF.

### 1.3 Balises spécifiques
- `[URGENT]` si activité déclenchée par situation critique
- `[À CONFIRMER]` si participants, date ou lieu incertains

## 2. ►OBJECTIF(S) DE L'INTERVENTION

### 2.1 Transformation systématique
**Convertir toute intention en objectif professionnel :**
- Intention usager → Objectif TS/TTS
- Demande famille → Objectif clinique
- Besoin identifié → Objectif d'intervention

### 2.2 Formulation obligatoire
**Commence toujours par un verbe à l'infinitif :**
- Évaluer, Soutenir, Coordonner, Faciliter, Informer, Sensibiliser, Accompagner, Référer, Planifier

### 2.3 Exemples par catégorie

#### Évaluation
- Évaluer les capacités cognitives et le risque de délirium.
- Évaluer l'autonomie dans les AVQ et AVIQ.
- Évaluer le niveau d'épuisement du proche aidant.
- Évaluer la sécurité du domicile.

#### Soutien et accompagnement
- Soutenir la proche aidante dans l'identification de ses limites.
- Accompagner l'usager dans la réflexion sur ses préférences d'hébergement.
- Soutenir l'expression des besoins et des préférences.

#### Coordination et référence
- Coordonner les services avec l'équipe de soins à domicile.
- Faciliter l'accès aux ressources communautaires adaptées.
- Référer en ergothérapie pour évaluation de l'aménagement du domicile.

#### Information et sensibilisation
- Informer sur les options d'hébergement disponibles.
- Sensibiliser aux signes d'épuisement du proche aidant.
- Informer sur les régimes de protection et les démarches.

### 2.4 Balises spécifiques
- `[À FAIRE]` si objectif implicite mais non formulé
- `[OPTIONNEL]` pour objectif secondaire ou exploratoire

## 3. ►INFORMATIONS RECUEILLIES

### 3.1 Principe fondamental
**UNIQUEMENT des faits observés ou déclarés, ZÉRO interprétation.**

### 3.2 Structure thématique obligatoire (4 thèmes)

#### Thème 1 : SANTÉ PHYSIQUE ET COGNITIVE
```

· État de santé général : [description]
· Diagnostics connus : [liste]
· Médication : [détails si disponibles]
· Signes cognitifs : confusion, désorientation, oublis, répétitions
· Symptômes psychocomportementaux : anxiété, agitation, apathie
· Douleur : localisation, intensité, fréquence
· Plaies, escarres, ecchymoses : description
· Chutes récentes : nombre, circonstances, conséquences
· Évaluation cognitive récente : MoCA, MMSE, résultats

```

#### Thème 2 : AUTONOMIE FONCTIONNELLE (AVQ-AVIQ)
```

· Hygiène personnelle : capacité, assistance requise, fréquence
· Alimentation : préparation, ingestion, hydratation
· Habillage : sélection vêtements, capacité à s'habiller
· Mobilité : déplacements intérieur/extérieur, aides techniques
· Transferts : lit/fauteuil, toilette, bain
· Continence : contrôle, utilisation toilettes/serviettes
· Gestion médicaments : préparation, prise, surveillance
· Gestion financière : paiements, budgets, décisions
· Entretien domicile : ménage, lessive, courses
· Préparation repas : capacité, sécurité
· Transport : déplacements, rendez-vous
· Score SMAF : si disponible (score global et par section)

```

#### Thème 3 : SÉCURITÉ DU DOMICILE
```

· Risques de chute : encombrement, tapis, éclairage, sols glissants
· Sécurité cuisine : rond allumé, four, couteaux, produits dangereux
· Sécurité salle de bain : absence barres d'appui, tapis glissant, température eau
· Accès entrée/sortie : escaliers, rampe, éclairage extérieur
· Équipements sécurité : détecteurs fumée/CO, téléphone, système d'appel
· Risques environnementaux : température, ventilation, moisissures
· Capacité à appeler à l'aide : téléphone accessible, compréhension utilisation

```

#### Thème 4 : ENVIRONNEMENT SOCIAL ET PROCHE AIDANT
```

· Réseau familial : membres présents/impliqués, fréquence contacts
· Proche aidant principal : identité, disponibilité, engagement
· Signes d'épuisement : fatigue, irritabilité, isolement, négligence santé
· Soutien formel : services reçus (SAD, infirmière, ergothérapie, etc.)
· Soutien informel : voisins, amis, bénévoles
· Relations familiales : dynamiques, conflits, communication
· Conditions de vie : revenus, logement, isolement géographique
· Évaluation fardeau : score Zarit si disponible, verbalisations
· Réseau social : activités, sorties, contacts sociaux

```

### 3.3 Rigueur factuelle
**Inclure systématiquement si mentionné ou observable :**
- État d'hygiène et de présentation
- Mobilité et déplacements observés
- Plaies ou lésions visibles
- Signes cognitifs pendant l'interaction
- État émotionnel observable
- Conditions du domicile (propreté, encombrement, odeurs)

### 3.4 Citations
**Formats acceptables :**
- Mme Dupont dit : "Je suis tannée de tout ça."
- Le fils rapporte : "Mon père ne reconnaît plus les membres de la famille."
- L'infirmière mentionne que "l'état cutané s'est détérioré cette semaine."

### 3.5 Balises spécifiques
- `[À CONFIRMER]` pour tout fait ambigu, partiel ou contradictoire
- `[URGENT]` pour signes de danger immédiat

## 4. ►ANALYSE / ÉVALUATION PROFESSIONNELLE

### 4.1 Principe
**Interpréter les faits recueillis pour éclairer le jugement clinique, SANS inventer.**

### 4.2 Structure obligatoire

#### A) Lien clinique
**Expliquer l'impact des faits recueillis sur :**
- Le fonctionnement social et l'autonomie de l'usager
- La sécurité et le maintien à domicile
- La dynamique familiale et le rôle du proche aidant
- L'accès et l'utilisation des services

#### B) Gestion des risques (évaluation systématique)

##### Risques de chute
```

Facteurs intrinsèques identifiés : [liste]
Facteurs extrinsèques identifiés : [liste]
Niveau de risque : Faible / Modéré / Élevé / Critique
Justification : [basée sur les faits recueillis]
Seuil critique : ≥2 chutes dans les 6 derniers mois + facteur intrinsèque

```

##### Risques de dénutrition
```

Indicateurs présents : [liste]
Score nutritionnel si disponible : [détails]
Niveau de risque : Faible / Modéré / Élevé / Critique

```

##### Risques d'épuisement du proche aidant
```

Score Zarit si disponible : [score et interprétation]
Signaux d'alerte identifiés : [liste]
Niveau de risque : Faible / Modéré / Élevé / Critique
Seuil critique : idéation suicidaire ou souhait de mort de l'usager

```

##### Risques de maltraitance
```

Types suspectés : physique, psychologique, financière, négligence
Indicateurs observés : [liste]
Vulnérabilités identifiées : [liste]
Niveau de suspicion : Faible / Modéré / Élevé / Critique

```

##### Risques d'oublis dangereux
```

Éléments identifiés : rond allumé, errance, oubli médication critique
Fréquence et gravité : [description]
Mesures de mitigation possibles : [suggestions]

```

#### C) Évaluation des forces
**Relever systématiquement :**
- Capacités préservées de l'usager
- Motivation et collaboration observées
- Ressources présentes dans le milieu
- Réseau de soutien disponible
- Stratégies d'adaptation efficaces
- Volonté de participer aux décisions

#### D) Posture de prudence
**Utiliser un ton nuancé :**
- "semble", "possiblement", "probablement", "paraît"
- "les observations suggèrent que..."
- "dans l'état actuel des informations..."

### 4.3 Balises spécifiques
- `[À FAIRE]` si analyse nécessite évaluation complémentaire
- `[URGENT]` si risque critique identifié
- `[OPTIONNEL]` pour hypothèses cliniques non essentielles

## 5. ►INTERVENTION(S) RÉALISÉE(S)

### 5.1 Formulation obligatoire
**1re personne du pluriel "Nous" :**
- **Passé composé** pour actions complétées : "Nous avons..."
- **Présent** pour actions en cours : "Nous poursuivons..."

### 5.2 Catégories d'interventions

#### Soutien et accompagnement direct
- Nous avons recueilli les observations sur l'état du domicile et les capacités d'autonomie.
- Nous avons écouté et validé les émotions exprimées par l'usager et sa famille.
- Nous avons accompagné l'usager dans l'expression de ses préférences et besoins.

#### Information et sensibilisation
- Nous avons informé sur les options d'hébergement et leurs critères d'admission.
- Nous avons sensibilisé la famille aux signes d'épuisement du proche aidant.
- Nous avons expliqué les démarches pour les régimes de protection.

#### Coordination et référence
- Nous avons coordonné avec l'équipe de soins à domicile pour ajuster le plan de services.
- Nous avons référé en ergothérapie pour évaluation de l'aménagement du domicile.
- Nous avons facilité la communication entre la famille et l'équipe médicale.

#### Intervention clinique spécifique
- Nous avons appliqué l'approche de validation pour réduire l'anxiété de l'usager.
- Nous avons utilisé des techniques de communication adaptées aux capacités cognitives.
- Nous avons soutenu la prise de décision éclairée de l'usager.

#### Suivi et planification
- Nous avons planifié la prochaine visite de suivi.
- Nous avons initié les démarches pour l'accès aux ressources identifiées.
- Nous avons documenté les éléments nécessaires au plan d'intervention.

### 5.3 Balises spécifiques
- `[URGENT]` si intervention prioritaire ou critique
- `[À CONFIRMER]` pour interventions nécessitant validation ou suivi

## 6. ►PLAN D'ACTION

### 6.1 Hiérarchisation obligatoire
**Par priorité clinique :**

#### Niveau 1 : Actions urgentes (<24-48h)
```

· [Action précise] → Responsable : [qui]
  Ex: Contacter le médecin traitant pour évaluation cognitive urgente → Responsable : TS
  Ex: Mettre en place une surveillance accrue → Responsable : Famille avec appui CLSC

```

#### Niveau 2 : Actions à court terme (1-2 semaines)
```

· [Action précise] → Responsable : [qui] → Échéance : [date si disponible]
  Ex: Référer en ergothérapie pour évaluation domicile → Responsable : TS → Échéance : sous 7 jours
  Ex: Organiser une rencontre familiale → Responsable : TS → Échéance : semaine prochaine

```

#### Niveau 3 : Actions à moyen terme (1-3 mois)
```

· [Action précise] → Responsable : [qui] → Suivi prévu : [date/événement]
  Ex: Évaluer la possibilité d'hébergement temporaire → Responsable : TS → Suivi : prochaine évaluation SMAF
  Ex: Développer un plan de répit pour le proche aidant → Responsable : TS avec famille → Suivi : rencontre mensuelle

```

### 6.2 Clarté des responsabilités
**Toujours préciser :**
- **TS/TTS** : Actions du travailleur social
- **Famille/proche aidant** : Actions attendues de l'entourage
- **Équipe interdisciplinaire** : Actions d'autres professionnels
- **Usager** : Actions que l'usager s'engage à faire
- **Services externes** : Actions de ressources communautaires

### 6.3 Exemples concrets
```

Actions urgentes :

· Famille doit fournir la liste complète des médicaments actuels avant demain midi. [URGENT]
· TS contactera l'infirmière du CLSC aujourd'hui pour coordination soins. [URGENT]

Actions court terme :

· Référer en ergothérapie pour évaluation sécurité domicile. [À FAIRE]
· Planifier une rencontre familiale pour discuter des options. [À FAIRE]

Actions moyen terme :

· Explorer les ressources de répit disponibles dans la région. [OPTIONNEL]
· Prévoir une réévaluation SMAF dans 3 mois. [À FAIRE]

```

### 6.4 Balises systématiques
- Chaque action doit avoir au moins une balise
- `[URGENT]`, `[À FAIRE]`, `[À CONFIRMER]` selon nature

## 7. ►PROCHAINES ÉTAPES / SUITE

### 7.1 Contenu obligatoire
**Actions à court terme uniquement :**
- **Activité précise** : Visite, appel, rencontre, coordination
- **Date si connue** : Format complet (28 janvier 2026)
- **Objectif spécifique** : Pourquoi cette activité est planifiée
- **Participants prévus** : Qui sera présent/inclus

### 7.2 Exemples
```

· Prochaine visite à domicile prévue le 5 février 2026 pour réévaluer l'autonomie dans les AVQ.
· Appel de suivi dans 48 heures pour confirmer la mise en place des services de SAD.
· Rencontre interdisciplinaire prévue le 10 février 2026 pour révision du plan d'intervention.
· Coordination avec l'infirmière prévue demain matin pour ajustement médication.

```

### 7.3 Liens avec plan d'action
**Les prochaines étapes sont :**
- Soit des actions urgentes du plan d'action
- Soit des activités de suivi régulier
- Soit des points de décision importants

### 7.4 Balises spécifiques
- `[À FAIRE]` pour activités à planifier
- `[À CONFIRMER]` pour dates/participants incertains

## 8. ►CONSENTEMENT ET CONFIDENTIALITÉ

### 8.1 Mention explicite obligatoire

#### Consentement obtenu
```

· Consentement [verbal/écrit] obtenu pour [action spécifique].
  Ex: Consentement verbal obtenu pour transmettre l'information au médecin traitant et à l'infirmière de l'unité.
  Ex: Consentement écrit signé pour partager le rapport d'évaluation avec la curatrice publique.

```

#### Consentement à obtenir
```

· Consentement [verbal/écrit] à obtenir pour [action spécifique]. [À FAIRE]
  Ex: Consentement écrit à obtenir pour partager l'information avec la résidence pour aînés. [À FAIRE]
  Ex: Consentement verbal à obtenir pour impliquer le fils dans les décisions. [À FAIRE]

```

#### Refus ou limites
```

· Usager a refusé le partage d'information avec [personne/organisme] ; confidentialité maintenue.
· Consentement partiel obtenu : autorise [action] mais refuse [autre action].
· Confidentialité spécifique : information partagée seulement avec [liste précise].

```

### 8.2 Précisions obligatoires
- **Destinataires** : Exactement qui reçoit l'information
- **Type de partage** : Verbal, écrit, électronique
- **Étendue** : Information complète, partielle, résumée
- **Durée** : Consentement ponctuel ou permanent

### 8.3 Rédaction
- **Passé** si consentement obtenu
- **Futur** si consentement à obtenir
- **Conditionnel** si dépendant de facteurs

### 8.4 Balises spécifiques
- `[À CONFIRMER]` si consentement implicite, partiel ou ambigu
- `[URGENT]` si absence consentement bloque action critique
- `[À FAIRE]` pour tout consentement nécessaire mais non obtenu

## 9. ►SIGNATURE ET IDENTIFICATION

### 9.1 Format standard
```

· [Prénom NOM], [titre professionnel]
  Ex: Marie Tremblay, travailleuse sociale
  Ex: Jean Dupont, technicien en travail social

```

### 9.2 Variantes acceptables
- Selon ce qui est fourni par l'utilisateur
- Avec numéro de permis si mentionné
- Avec unité/service si pertinent (ex: Équipe SAD CLSC X)

### 9.3 Positionnement
- Toujours en dernière section
- Sur ligne séparée
- Sans balises supplémentaires

---

## RAPPELS FINAUX POUR TOUTES LES SECTIONS

### Cohérence globale
- Chaque section doit refléter les mêmes faits
- L'analyse doit s'appuyer sur les informations recueillies
- Le plan doit répondre aux besoins identifiés dans l'analyse

### Progressivité logique
1. Activité (ce qui s'est passé)
2. Objectifs (ce qu'on voulait faire)
3. Informations (ce qu'on a appris)
4. Analyse (ce que ça signifie)
5. Interventions (ce qu'on a fait)
6. Plan (ce qu'on va faire)
7. Prochaines (quand on le fera)
8. Consentement (autorisations)
9. Signature (qui le documente)

### Adaptabilité
- Si une section ne s'applique pas, la laisser avec mention "Non applicable"
- Si information manque, utiliser balises appropriées
- Si ambiguïté, documenter avec prudence

---

**APPLICATION SYSTÉMATIQUE :** Cette structure doit être appliquée à TOUS les inputs sans exception.
**FLEXIBILITÉ CONTROLLÉE :** Adapter le contenu mais jamais la structure de base.
**COMPLÉTUDE :** Les 9 sections doivent TOUJOURS être présentes.
