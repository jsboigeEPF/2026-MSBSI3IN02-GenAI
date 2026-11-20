# Catalogue Bachelor — 94 projets

Chaque fiche pose une question précise, dit ce qu'il faut construire pour y répondre et comment mesurer le résultat. Choisissez une famille, puis comparez les fiches sur trois points : le verrou technique, le protocole de réussite et le plan B.

Les fiches marquées « hybride CoursIA » partent d'un notebook d'une autre série du dépôt (recherche et contraintes, probabilités, théorie des jeux, IA symbolique, compression, finance quantitative, apprentissage par renforcement) et y ajoutent un modèle génératif. Le principe est toujours le même : le modèle propose, un calcul indépendant vérifie.

Tous les projets tiennent en six semaines et restent démontrables sans API payante ni GPU grâce à leur plan B. Les identifiants existants restent inchangés.

## Index par catégorie

**Texte, mémoire et dialogue** (5)　[A2 : Mémoire persistante multi-sessions](#fiche-a2) · [A4 : Mémoire multimodale évaluable](#fiche-a4) · [A5 : Long contexte contre RAG sous ablation](#fiche-a5) · [A7 : Cohérence interne des documents longs](#fiche-a7) · [BSI-02 : Générer une question qui départage deux interprétations](#fiche-bsi-02)

**Image, audio et vidéo** (8)　[C5 : Restauration d'images sans invention](#fiche-c5) · [C6 : Images synthétiques pour l'entraînement](#fiche-c6) · [D3 : Séparation et restauration de sources audio](#fiche-d3) · [D4 : Synthèse vocale expressive et prosodie](#fiche-d4) · [D5 : Diarisation et transcription de réunion](#fiche-d5) · [D6 : Podcast sourcé de bout en bout](#fiche-d6) · [E5 : Montage automatique mesuré](#fiche-e5) · [BSI-01 : Un sous-titre doit aussi se lire à temps](#fiche-bsi-01)

**Logiciels et services génératifs** (6)　[B4 : Générateur auto-validant de notebooks](#fiche-b4) · [F3 : Application GenAI observable avec .NET Aspire](#fiche-f3) · [F4 : Routeur multi-fournisseurs avec failover](#fiche-f4) · [F5 : Assistant support avec escalade mesurée](#fiche-f5) · [G2 : Garde-fous Roslyn pour code généré](#fiche-g2) · [G3 : Pair-programming IA en étude contrôlée](#fiche-g3)

**Évaluation, données et apprentissage** (6)　[H4 : Provenance et détection de contenus synthétiques](#fiche-h4) · [H5 : Constitution IA et coût des refus](#fiche-h5) · [J2 : Analyste multimodal de données](#fiche-j2) · [J3 : Expériences reproductibles auto-validées](#fiche-j3) · [K1 : Confidentialité des données synthétiques](#fiche-k1) · [L3 : Tuteur adaptatif avec mesure d'apprentissage](#fiche-l3)

**Adaptation et inférence** (4)　[I1 : QLoRA sans contamination de l'évaluation](#fiche-i1) · [I2 : Inférence locale .NET face aux API cloud](#fiche-i2) · [I3 : Frontière coût-précision du test-time compute](#fiche-i3) · [I4 : Fusion et routage de modèles spécialisés](#fiche-i4)

**Génération sous contraintes symboliques** (14)　[M1 : Du cahier des charges au planning certifié](#fiche-m1) · [M2 : Expliquer pourquoi un puzzle est impossible](#fiche-m2) · [M3 : Mots croisés : générer des définitions qui laissent une solution unique](#fiche-m3) · [M4 : Transformer une procédure en machine à états](#fiche-m4) · [M5 : Produire un contre-exemple plutôt qu'un avis](#fiche-m5) · [M6 : Traduire une règle en contraintes de planning](#fiche-m6) · [M7 : Inventer des énigmes à solution unique](#fiche-m7) · [M8 : Sudoku : expliquer le prochain coup, pas la grille](#fiche-m8) · [M9 : Planification : le modèle propose, le planificateur dispose](#fiche-m9) · [M10 : Picross : d'une image générée à une grille à solution unique](#fiche-m10) · [M11 : Niveaux générés, jouabilité prouvée](#fiche-m11) · [M12 : Une heuristique écrite par un LLM est-elle admissible ?](#fiche-m12) · [M13 : Du brief logistique à la tournée optimisée](#fiche-m13) · [M14 : Menus sous contraintes : du besoin en français au plan certifié](#fiche-m14)

**Mesures, causalité et raisonnement quantitatif** (9)　[N1 : Conserver les unités dans un compte rendu](#fiche-n1) · [N2 : Générer un mode d'emploi qui respecte les dépendances](#fiche-n2) · [N3 : Un assistant distingue-t-il observer et intervenir ?](#fiche-n3) · [N4 : Rédiger un bulletin qui respecte l'incertitude](#fiche-n4) · [N5 : Auditer les dénominateurs d'une synthèse](#fiche-n5) · [N6 : Faire réviser une conclusion après une intervention](#fiche-n6) · [N7 : Du récit d'un dilemme au réseau de décision](#fiche-n7) · [N8 : Hypothèses générées, effets estimés](#fiche-n8) · [N9 : Programme probabiliste généré, postérieur vérifié](#fiche-n9)

**Accessibilité et transmission du sens** (4)　[O1 : Adapter un texte sans perdre ses exceptions](#fiche-o1) · [O2 : Restituer un tableau avec un lecteur d'écran](#fiche-o2) · [O3 : Choisir un texte alternatif selon la tâche](#fiche-o3) · [O4 : Écrire une consigne qui survit à la traduction](#fiche-o4)

**Édition, compression et couverture** (8)　[P1 : Publier uniquement les changements utiles](#fiche-p1) · [P2 : Compression : apprendre une recette, certifier son inverse](#fiche-p2) · [P3 : Générer un index de renvois qui reste valide](#fiche-p3) · [P4 : Construire des exemples qui couvrent une règle](#fiche-p4) · [P5 : Fusionner deux corrections éditoriales](#fiche-p5) · [P6 : Prédire, c'est compresser : un modèle de langue comme codec](#fiche-p6) · [P7 : Triage de compression orchestré par Semantic Kernel](#fiche-p7) · [P8 : Tests combinatoires : couvrir toutes les paires](#fiche-p8)

**Jeux, récits et choix collectifs** (8)　[Q1 : Créer un récit dont le lecteur choisit le chemin](#fiche-q1) · [Q2 : Contrepoint : du solveur au rendu audio génératif](#fiche-q2) · [Q3 : Expliquer un désaccord entre scrutins avec un certificat de calcul](#fiche-q3) · [Q4 : Faire deviner une notion sans la nommer](#fiche-q4) · [Q5 : Expliquer deux résultats de vote contradictoires](#fiche-q5) · [Q6 : Un LLM joue-t-il l'équilibre ?](#fiche-q6) · [Q7 : Wordle : le modèle joue-t-il mieux que l'entropie ?](#fiche-q7) · [Q8 : Commenter une partie de Puissance 4 sans se tromper de coup](#fiche-q8)

**Preuve, connaissance et argumentation** (8)　[R1 : Preuves Lean : le modèle propose, le noyau vérifie](#fiche-r1) · [R2 : Graphe ou passages : quelle question demande quoi ?](#fiche-r2) · [R3 : Du texte au graphe de connaissances validé](#fiche-r3) · [R4 : Qui a raison ? Du débat au graphe d'arguments](#fiche-r4) · [R5 : Apprendre une règle depuis des exemples : LLM contre logique inductive](#fiche-r5) · [R6 : Contrats intelligents : audit par LLM, preuve par fuzzing](#fiche-r6) · [R7 : Retrouver une loi à partir de mesures](#fiche-r7) · [R8 : Un LLM peut-il servir d'oracle pour apprendre un automate ?](#fiche-r8)

**Décision, apprentissage par renforcement et marchés** (7)　[S1 : Signaux de marché lus par un LLM : gain réel ou mémoire du futur ?](#fiche-s1) · [S2 : Séries temporelles synthétiques par diffusion : réalistes et utiles ?](#fiche-s2) · [S3 : Une récompense rédigée par un LLM se fait-elle contourner ?](#fiche-s3) · [S4 : Le LLM comme optimiseur d'hyperparamètres](#fiche-s4) · [S5 : Choisir le bon solveur en lisant l'énoncé](#fiche-s5) · [S6 : Planifier avant de coder : la boucle vaut-elle son coût ?](#fiche-s6) · [S7 : Recommander avec des identifiants sémantiques](#fiche-s7)

**Sécurité et confiance des systèmes génératifs** (7)　[T1 : Repérer un jailbreak à sa trajectoire, pas à son texte](#fiche-t1) · [T2 : La propagande est-elle plus compressible que l'information ?](#fiche-t2) · [T3 : Agent par capacités : prouver qu'une donnée ne déclenche aucune action](#fiche-t3) · [T4 : Code cryptographique généré : le tester au lieu de le relire](#fiche-t4) · [T5 : Trouver les exemples empoisonnés par la signature spectrale](#fiche-t5) · [T6 : Une décision tient-elle face à un contre-argument ?](#fiche-t6) · [T7 : Agent d'entreprise : demander l'accord seulement pour l'irréversible](#fiche-t7)

## Texte, mémoire et dialogue

<a id="fiche-a2"></a>

### A2 — Mémoire persistante multi-sessions

**Difficulté : 3/5** · Mots-clés : `memory`, `sessions`, `privacy`, `evaluation`

Concevoir une mémoire explicite qui décide quoi conserver, retrouver, mettre à jour ou oublier entre plusieurs sessions. Contrairement à l'ancien majordome, le domaine importe peu : le verrou est la politique de mémoire et sa mesure.

- **MVP** : journal d'événements, mémoire sémantique persistante, mise à jour des faits contradictoires et commande d'oubli.
- **Réussite** : scénarios multi-sessions reproductibles mesurant rappel utile, faux souvenirs, fraîcheur et suppression effective.
- **Extensions** : mémoire épisodique/sémantique séparée, chiffrement, expiration automatique.
- **Faisabilité** : base locale ou Qdrant ; GPU non requis ; données synthétiques obligatoires ; budget cible inférieur à 5 €. Plan B : embeddings locaux.

**CoursIA** : [Persistent Memory](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/14_Persistent_Memory.ipynb) · [Hands-On Grounding](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/01-Hands-On-Grounding.ipynb) · [Stockage vectoriel](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/05-Stockage-Vectoriel.ipynb)

**Références** : [MemGPT](https://arxiv.org/abs/2310.08560) · [Qdrant — Payload](https://qdrant.tech/documentation/concepts/payload/) · [OWASP — LLM02 Insecure Output Handling](https://genai.owasp.org/llmrisk/llm02-insecure-output-handling/)

<a id="fiche-a4"></a>

### A4 — Mémoire multimodale évaluable

**Difficulté : 4/5** · Mots-clés : `multimodal`, `kernel-memory`, `retrieval`, `grounding`

Indexer un corpus mêlant texte et images, puis répondre à des questions dont certaines exigent les deux modalités. Le projet doit isoler l'apport du retrieval multimodal.

- **MVP** : ingestion multimodale, recherche, réponses sourcées et interface minimale.
- **Réussite** : jeu annoté d'au moins 30 questions unimodales/multimodales, ablations texte seul/image seule/fusion.
- **Extensions** : OCR, tableaux, late fusion, cache d'embeddings.
- **Faisabilité** : Qdrant ou Kernel Memory ; API vision possible ; budget cible inférieur à 15 €. Plan B : embeddings et légendes pré-calculés.

**CoursIA** : [Kernel Memory Multimodal](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/09-KernelMemory-Multimodal.ipynb) · [Kernel Memory In Process](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/06-KernelMemory-InProcess.ipynb) · [Semantic Kernel Multimodal](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/07-SemanticKernel-MultiModal.ipynb)

**Références** : [Microsoft Kernel Memory](https://github.com/microsoft/kernel-memory) · [CLIP](https://arxiv.org/abs/2103.00020) · [Qdrant — Multivectors](https://qdrant.tech/documentation/concepts/vectors/#multivectors)

<a id="fiche-a5"></a>

### A5 — Long contexte contre RAG sous ablation

**Difficulté : 3/5** · Mots-clés : `long-context`, `rag`, `ablation`, `grounding`

Comparer sur un même corpus l'injection du document complet, un RAG simple et un RAG reranké. Le verrou technique est d'isoler l'effet du contexte disponible sans confondre qualité, coût et latence.

- **MVP** : corpus public, 50 questions, trois stratégies et journal des passages réellement fournis au modèle.
- **Réussite** : exactitude, fidélité des citations, coût, latence et performance selon la position de l'information.
- **Extensions** : compression de contexte, cache, questions multi-documents.
- **Faisabilité** : API texte ou modèle local ; budget cible inférieur à 12 €. Plan B : réponses mises en cache et corpus réduit.

**CoursIA** : [Long Context Strategies](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/10c_Long_Context_Strategies.ipynb) · [RAG moderne](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/05_RAG_Modern.ipynb)

**Références** : [Lost in the Middle](https://arxiv.org/abs/2307.03172) · [RAG](https://arxiv.org/abs/2005.11401) · [LongBench](https://arxiv.org/abs/2308.14508)

<a id="fiche-a7"></a>

### A7 — Cohérence interne des documents longs

**Difficulté : 4/5** · Mots-clés : `consistency`, `nli`, `long-context`, `detection`

Construire un détecteur d'incohérences pour des documents générés de plusieurs pages : contradictions entre sections, chiffres divergents, annonces non tenues. Le verrou technique est la détection mesurée sur un corpus dont les incohérences sont connues.

- **MVP** : générateur de documents longs structurés, injecteur de contradictions contrôlées (20 documents, 60 incohérences) et pipeline de détection par paires de passages.
- **Réussite** : précision/rappel par type d'incohérence, fenêtres glissantes contre contexte complet, faux positifs sur textes cohérents.
- **Extensions** : graphe d'affirmations, réécriture corrective, détection pendant la génération.
- **Faisabilité** : API texte ou modèle local ; budget cible inférieur à 10 €. Plan B : corpus annoté fourni sans génération.

**CoursIA** : [Long Context Strategies](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/10c_Long_Context_Strategies.ipynb) · [Evaluating Generated Text](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/22_Evaluating_Generated_Text.ipynb) · [Hands-On Grounding](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/01-Hands-On-Grounding.ipynb)

**Références** : [SummaC](https://arxiv.org/abs/2111.09525) · [AlignScore](https://arxiv.org/abs/2305.16739) · [LongBench](https://arxiv.org/abs/2308.14508)

<a id="fiche-bsi-02"></a>

### BSI-02 — Générer une question qui départage deux interprétations

**Difficulté : 3/5** · Mots-clés : `dialogue`, `clarification`, `décision`, `information`

Devant une demande ambiguë, un assistant peut répondre au hasard ou poser une question. Le projet mesure la valeur de la question posée : la bonne question est celle qui élimine le plus de solutions possibles, pas la plus polie.

- **MVP** : 24 demandes fictives de réservation et une table de salles avec contraintes. Trois stratégies : question fixe, question proposée par le modèle, oracle qui connaît toutes les partitions possibles des solutions.
- **Réussite** : Choix corrects après un seul échange, demandes qui se résolvaient sans question, questions inutiles. Huit demandes sont réservées au test final ; le hasard sert de plancher.
- **Extensions** : Coût d'un second échange ; demandes à trois interprétations ; question à choix fermés contre question ouverte.
- **Faisabilité** : API texte ou modèle local ; GPU inutile ; budget cible inférieur à 5 €. Plan B : propositions du modèle versionnées en JSON et évaluation rejouée localement.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Décisions typées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03b_Typed_Decisions_System1.ipynb)

**Références** : [Qulac](https://arxiv.org/abs/1907.06554) · [CLAM](https://arxiv.org/abs/2212.07769) · [JSON Schema](https://json-schema.org/) · [scikit-learn — information mutuelle](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mutual_info_score.html)

## Image, audio et vidéo

<a id="fiche-c5"></a>

### C5 — Restauration d'images sans invention

**Difficulté : 3/5** · Mots-clés : `restoration`, `super-resolution`, `hallucination`, `benchmark`

Améliorer des images dégradées en contrôlant ce que le modèle invente : le projet oppose des restaureurs génératifs et des méthodes conservatrices sur un protocole où la vérité terrain existe.

- **MVP** : corpus d'images dégradées de façon contrôlée (flou, bruit, compression, basse résolution), deux pipelines de restauration et mesures de fidélité et de perception.
- **Réussite** : PSNR/SSIM contre l'original, distance perceptuelle, mesure de l'invention (détails absents de l'original mais ajoutés par le modèle) et analyse coût–latence.
- **Extensions** : restauration par instruction en langage naturel, cas sans vérité terrain, interface comparative.
- **Faisabilité** : modèles pré-entraînés locaux ou API image ; budget cible inférieur à 12 €. Plan B : corpus d'images dégradées pré-calculé.

**CoursIA** : [Édition guidée par consigne](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/01-Foundation/01-5-Edition-Image-Prompt.ipynb) · [Basic Image Operations](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/01-Foundation/01-3-Basic-Image-Operations.ipynb) · [Comparaison multi-modèles](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/03-Orchestration/03-1-Multi-Model-Comparison.ipynb)

**Références** : [Real-ESRGAN](https://arxiv.org/abs/2107.10833) · [SwinIR](https://arxiv.org/abs/2108.10257) · [LPIPS](https://arxiv.org/abs/1801.03924)

<a id="fiche-c6"></a>

### C6 — Images synthétiques pour l'entraînement

**Difficulté : 4/5** · Mots-clés : `synthetic-data`, `vision`, `augmentation`, `ablation`

Générer des images d'entraînement synthétiques pour une tâche de vision pauvre en données et mesurer si elles améliorent réellement un classifieur, seules ou en appoint d'un petit jeu réel.

- **MVP** : tâche de classification bornée (huit classes), jeu réel réduit, générateur contrôlé (prompt, variantes, arrière-plan) et entraînement reproductible.
- **Réussite** : courbes exactitude/taille du jeu réel avec et sans synthèse, ablation des ratios réel/synthétique et analyse de l'écart de distribution.
- **Extensions** : randomisation de domaine, filtrage des images synthétiques, artefacts appris détectés.
- **Faisabilité** : diffusion locale ou API image et petit CNN ; GPU partagé utile mais CPU acceptable ; budget cible inférieur à 12 €. Plan B : jeu d'images synthétiques fourni.

**CoursIA** : [FLUX Advanced Generation](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/02-Advanced/02-2-FLUX-1-Advanced-Generation.ipynb) · [Workflow Orchestration](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/03-Orchestration/03-2-Workflow-Orchestration.ipynb) · [Comparaison multi-modèles](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/03-Orchestration/03-1-Multi-Model-Comparison.ipynb)

**Références** : [Domain Randomization](https://arxiv.org/abs/1703.06907) · [DatasetDM](https://arxiv.org/abs/2308.06160) · [Latent Diffusion](https://arxiv.org/abs/2112.10752)

<a id="fiche-d3"></a>

### D3 — Séparation et restauration de sources audio

**Difficulté : 3/5** · Mots-clés : `source-separation`, `denoising`, `audio`, `benchmark`

Séparer voix, musique et bruit puis restaurer la composante utile sans introduire d'artefacts. Le verrou technique est l'évaluation objective et perceptuelle de la reconstruction.

- **MVP** : corpus de 20 mélanges contrôlés, deux pipelines et interface d'écoute aveugle.
- **Réussite** : SI-SDR, intelligibilité, temps de traitement et préférence humaine.
- **Extensions** : séparation temps réel, plusieurs locuteurs, estimation de confiance.
- **Faisabilité** : Demucs et outils locaux ; GPU facultatif. Plan B : extraits courts pré-calculés.

**CoursIA** : [Demucs Source Separation](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/02-Advanced/02-4-Demucs-Source-Separation.ipynb) · [Basic Audio Operations](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-3-Basic-Audio-Operations.ipynb)

**Références** : [Demucs](https://github.com/facebookresearch/demucs) · [MUSDB18](https://sigsep.github.io/datasets/musdb.html) · [BSS Eval](https://arxiv.org/abs/1811.02508)

<a id="fiche-d4"></a>

### D4 — Synthèse vocale expressive et prosodie

**Difficulté : 3/5** · Mots-clés : `tts`, `prosody`, `emotion`, `evaluation`

Contrôler rythme, pauses, accentuation et émotion d'une voix synthétique sur des textes constants. Le verrou technique est de relier paramètres prosodiques et perception sans cloner une voix non consentie.

- **MVP** : 30 phrases, quatre intentions, deux systèmes et mesures acoustiques.
- **Réussite** : reconnaissance d'intention à l'aveugle, naturalité, durée et coût.
- **Extensions** : SSML, transfert de style consenti, contrôle fin.
- **Faisabilité** : voix synthétiques ou consenties uniquement ; API ou moteur local. Plan B : Kokoro local.

**CoursIA** : [Expressive TTS](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/02-Advanced/02-8-Expressive-TTS.ipynb) · [TTS Voice Benchmark](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/04-Applications/04-Voix/04-7-TTS-Voice-Benchmark.ipynb)

**Références** : [SSML](https://www.w3.org/TR/speech-synthesis11/) · [P.808](https://www.itu.int/rec/P-REC-P.808) · [Kokoro](https://github.com/hexgrad/kokoro)

<a id="fiche-d5"></a>

### D5 — Diarisation et transcription de réunion

**Difficulté : 3/5** · Mots-clés : `asr`, `diarization`, `meetings`, `wer-der`

Transcrire une réunion en séparant qui a dit quoi : le projet mesure à la fois la qualité de transcription (WER) et l'attribution des locuteurs (DER) sur des réunions multi-locuteurs.

- **MVP** : corpus de dix réunions publiques ou enregistrées en conditions réelles, pipeline STT et diarisation, transcription alignée locuteur/temps.
- **Réussite** : WER par locuteur et par condition, DER, erreurs d'attribution typiques, effet d'un glossaire métier et latence de traitement.
- **Extensions** : transcription en flux, empreinte vocale, résumé par locuteur.
- **Faisabilité** : Whisper local ou API ; GPU non requis ; enregistrements consentis uniquement. Plan B : extrait AMI pré-découpé.

**CoursIA** : [OpenAI Whisper STT](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-2-OpenAI-Whisper-STT.ipynb) · [Whisper Local](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-4-Whisper-Local.ipynb) · [Transcription Pipeline](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/04-Applications/04-2-Transcription-Pipeline.ipynb)

**Références** : [Whisper](https://arxiv.org/abs/2212.04356) · [pyannote.audio](https://github.com/pyannote/pyannote-audio) · [AMI Meeting Corpus](https://groups.inf.ed.ac.uk/ami/)

<a id="fiche-d6"></a>

### D6 — Podcast sourcé de bout en bout

**Difficulté : 3/5** · Mots-clés : `podcast`, `pipeline`, `grounding`, `tts`

Produire automatiquement un épisode de podcast parlé à partir d'un sujet et de sources publiques, avec un script dont chaque affirmation reste traçable jusqu'à sa source. Le verrou technique est la fidélité factuelle du script et la qualité d'écoute, pas la seule voix.

- **MVP** : collecte de sources sur un sujet borné, script segmenté et sourcé, narration TTS et épisode de cinq minutes avec notes d'épisode.
- **Réussite** : fidélité des affirmations aux sources (échantillon vérifié), taux de phrases sans source, intelligibilité et naturalité à l'aveugle, coût par épisode.
- **Extensions** : multi-voix, diffusion automatique, veille récurrente hebdomadaire.
- **Faisabilité** : API texte et TTS local ou API ; budget cible inférieur à 12 €. Plan B : sources fournies et narration locale.

**CoursIA** : [Audiobook Pipeline](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/04-Applications/04-Audiobook/04-6-Audiobook-Pipeline.ipynb) · [PDF Web Search](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/06_PDF_Web_Search.ipynb) · [Expressive TTS](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/02-Advanced/02-8-Expressive-TTS.ipynb)

**Références** : [QAGS](https://arxiv.org/abs/2004.04228) · [P.808](https://www.itu.int/rec/P-REC-P.808) · [SSML](https://www.w3.org/TR/speech-synthesis11/)

<a id="fiche-e5"></a>

### E5 — Montage automatique mesuré

**Difficulté : 4/5** · Mots-clés : `auto-editing`, `video-understanding`, `pacing`, `pipeline`

Monter automatiquement des rushes bruts en séquence regardable : sélection des prises, coupes et rythme sous une durée cible. Le verrou technique est la qualité du montage mesurée, pas la génération d'images.

- **MVP** : rushes fournis (20 minutes, scènes connues), détection de plans et de prises, sélection assistée par modèle vision, assemblage et rapport de montage.
- **Réussite** : couverture des points de scénario attendus, durée cible respectée, métriques de rythme et évaluation humaine comparative contre un montage manuel.
- **Extensions** : sous-titres, musique adaptée, multi-caméras.
- **Faisabilité** : FFmpeg/MoviePy et VLM ; GPU inutile ; rushes tournés au téléphone acceptés ; budget cible inférieur à 12 €. Plan B : rushes et détections de plans fournis.

**CoursIA** : [Video Workflow Orchestration](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Video/03-Orchestration/03-2-Video-Workflow-Orchestration.ipynb) · [GPT-5 Video Understanding](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Video/01-Foundation/01-2-GPT-5-Video-Understanding.ipynb) · [Video Operations Basics](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Video/01-Foundation/01-1-Video-Operations-Basics.ipynb)

**Références** : [FFmpeg](https://ffmpeg.org/documentation.html) · [PySceneDetect](https://www.scenedetect.com/) · [P.1203](https://www.itu.int/rec/T-REC-P.1203)

<a id="fiche-bsi-01"></a>

### BSI-01 — Un sous-titre doit aussi se lire à temps

**Difficulté : 3/5** · Mots-clés : `audio`, `segmentation`, `accessibilité`, `reformulation`

Une transcription exacte peut donner un sous-titre illisible : trop long, coupé au mauvais endroit, affiché trop peu de temps. À transcription fixée, le projet cherche le découpage et la reformulation qui restent lisibles sans perdre une négation ni un nom propre. Reconnaître qui parle n'est pas le sujet.

- **MVP** : Dix phrases enregistrées, transcription de référence fixée, export WebVTT. Deux stratégies comparées : découpage à longueur fixe et reformulation contrainte par un débit maximal en caractères par seconde.
- **Réussite** : Proportion de segments au-dessus du seuil de débit, noms et négations préservés, chevauchements temporels. Cinq paires notées en aveugle ; un contre-exemple documenté où la reformulation change le sens.
- **Extensions** : Débit lent et rapide sur la même phrase ; coupe aux frontières syntaxiques ; deux lignes par segment.
- **Faisabilité** : Whisper local sur CPU pour de courts extraits ; budget cible inférieur à 3 €. Plan B : transcriptions et horodatages préparés, sans GPU ni API.

**CoursIA** : [Whisper local](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-4-Whisper-Local.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Opérations audio de base](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-3-Basic-Audio-Operations.ipynb)

**Références** : [WebVTT](https://www.w3.org/TR/webvtt1/) · [W3C WAI — Captions](https://www.w3.org/WAI/media/av/captions/) · [Whisper](https://arxiv.org/abs/2212.04356) · [BBC — Subtitle Guidelines](https://www.bbc.co.uk/accessibility/forproducts/guides/subtitles/)

## Logiciels et services génératifs

<a id="fiche-b4"></a>

### B4 — Générateur auto-validant de notebooks

**Difficulté : 4/5** · Mots-clés : `notebooks`, `generation`, `execution`, `validation`

Générer un notebook pédagogique à partir d'un cahier des charges, l'exécuter automatiquement, diagnostiquer ses erreurs puis produire un rapport de conformité. Le succès est l'exécution reproductible, pas la beauté d'un exemple.

- **MVP** : gabarit, génération, exécution isolée, deux boucles de correction maximum et rapport.
- **Réussite** : dix cahiers des charges ; taux d'exécution, conformité structurelle, corrections et coût.
- **Extensions** : plusieurs kernels, rubric pédagogique, sandbox renforcée.
- **Faisabilité** : Jupyter + Semantic Kernel ; exécution limitée et sans accès aux secrets ; budget cible inférieur à 8 €. Plan B : exercices Python sans réseau.

**CoursIA** : [NotebookMaker](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/10-SemanticKernel-NotebookMaker.ipynb) · [NotebookMaker batch paramétré](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/10b-SemanticKernel-NotebookMaker-batch-parameterized.ipynb) · [Code Interpreter](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/07_Code_Interpreter.ipynb)

**Références** : [Jupyter nbclient](https://nbclient.readthedocs.io/) · [nbformat](https://nbformat.readthedocs.io/) · [OWASP — Insecure Output Handling](https://genai.owasp.org/llmrisk/llm052025-improper-output-handling/)

<a id="fiche-f3"></a>

### F3 — Application GenAI observable avec .NET Aspire

**Difficulté : 4/5** · Mots-clés : `aspire`, `observability`, `streaming`, `integration-tests`

Construire une petite application GenAI distribuée dont les appels modèle, outils et erreurs sont visibles dans des traces, métriques et logs corrélés.

- **MVP** : frontend/API, service agent, streaming, télémétrie et tests d'intégration.
- **Réussite** : retrouver automatiquement une requête de bout en bout, mesurer latence/token, détecter trois pannes injectées.
- **Extensions** : multi-provider, circuit breaker, évaluation continue.
- **Faisabilité** : .NET Aspire + conteneurs ; GPU inutile ; budget cible inférieur à 10 €. Plan B : connecteur modèle simulé.

**CoursIA** : [Aspire Observabilité](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/03-Aspire-Observabilite.ipynb) · [Aspire Streaming Agent](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/04-Aspire-Streaming-Agent.ipynb) · [Aspire Tests Integration](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/05-Aspire-Tests-Integration.ipynb)

**Références** : [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire/) · [OpenTelemetry .NET](https://opentelemetry.io/docs/languages/net/) · [Polly](https://www.pollydocs.org/)

<a id="fiche-f4"></a>

### F4 — Routeur multi-fournisseurs avec failover

**Difficulté : 3/5** · Mots-clés : `routing`, `failover`, `multi-provider`, `slo`

Router chaque requête vers un modèle selon ses capacités, son coût et son état, puis basculer proprement en cas d'échec. Le verrou technique est de respecter un SLO sans masquer les différences de comportement entre fournisseurs.

- **MVP** : trois connecteurs, health checks, règles de routage, retries bornés et traces corrélées.
- **Réussite** : 100 requêtes avec pannes injectées ; disponibilité, p95, coût et taux de bascules correctes.
- **Extensions** : circuit breaker, routage appris, cache sémantique.
- **Faisabilité** : APIs à faible volume ou connecteurs simulés ; budget inférieur à 12 €. Plan B : serveur de réponses déterministes.

**CoursIA** : [Model Merging Routing](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-05-ModelMerging-Routing-Python.ipynb) · [SemanticFleet MultiConnector](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/07-Aspire-SemanticFleet-MultiConnector.ipynb)

**Références** : [Azure Architecture — Circuit Breaker](https://learn.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker) · [OpenTelemetry](https://opentelemetry.io/docs/) · [Polly](https://www.pollydocs.org/)

<a id="fiche-f5"></a>

### F5 — Assistant support avec escalade mesurée

**Difficulté : 3/5** · Mots-clés : `support`, `routing`, `escalation`, `oos-detection`

Construire un assistant de support qui répond aux questions couvertes et escalade proprement vers un humain sinon. Le verrou technique est la politique d'escalade : ni sur-escalade de questions résolubles, ni réponses hors périmètre.

- **MVP** : base de connaissances bornée, corpus de 150 tickets étiquetés (dans/hors périmètre/ambigu), décision réponse/escalade et file humaine simulée.
- **Réussite** : taux de résolution correcte, sous-escalade (réponses fausses), sur-escalade (questions résolubles escaladées), latence et matrice de confusion par intention.
- **Extensions** : priorisation de file, apprentissage des frontières d'escalade, tickets ambigus arbitrés.
- **Faisabilité** : corpus public ou tickets synthétiques ; API texte ; budget cible inférieur à 10 €. Plan B : intentions scriptées.

**CoursIA** : [Mesurer la dérive d'un Copilot](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Plateformes-Conversationnelles/AI-Engine-WordPress/03-Functional/03-1-Chatbots/mesurer-la-derive-dun-copilot.ipynb) · [Production Patterns](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/09_Production_Patterns.ipynb) · [Structured Outputs](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Banking77](https://huggingface.co/datasets/PolyAI/banking77) · [Rasa — Fallback and Human Handoff](https://legacy-docs-oss.rasa.com/docs/rasa/fallback-handoff/) · [Bot Framework — Human Handoff](https://learn.microsoft.com/en-us/azure/bot-service/bot-service-design-pattern-handoff-human)

<a id="fiche-g2"></a>

### G2 — Garde-fous Roslyn pour code généré

**Difficulté : 4/5** · Mots-clés : `roslyn`, `static-analysis`, `generated-code`, `verification`

Créer des analyseurs Roslyn qui interdisent des motifs dangereux ou non conformes dans du C# généré, puis mesurer leur précision sur un corpus contrôlé.

- **MVP** : quatre règles, diagnostics et code fixes, générateur de cas positifs/négatifs.
- **Réussite** : précision/rappel, zéro faux négatif sur règles critiques, tests unitaires et intégration avant compilation.
- **Extensions** : taint analysis, configuration par politique, boucle de réparation LLM.
- **Faisabilité** : .NET uniquement, API facultative, aucun GPU ; budget cible inférieur à 5 €. Plan B : corpus synthétique versionné.

**CoursIA** : [Roslyn Code Guardrails](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Vibe-Coding/analyzers/Roslyn-Code-Guardrails.ipynb) · [Aspire GardeFous Roslyn](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/06-Aspire-GardeFous-Roslyn.ipynb) · [CSharpRepl Live Patching](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Vibe-Coding/docs/CSharpRepl-Live-Patching.ipynb)

**Références** : [Roslyn analyzers](https://learn.microsoft.com/en-us/dotnet/csharp/roslyn-sdk/tutorials/how-to-write-csharp-analyzer-code-fix) · [Microsoft.CodeAnalysis.Testing](https://www.nuget.org/packages/Microsoft.CodeAnalysis.Analyzer.Testing/) · [CWE Top 25](https://cwe.mitre.org/top25/)

<a id="fiche-g3"></a>

### G3 — Pair-programming IA en étude contrôlée

**Difficulté : 3/5** · Mots-clés : `pair-programming`, `experiment`, `productivity`, `quality`

Mesurer l'effet d'un assistant de code sur des tâches comparables, avec et sans assistance. Le verrou technique est un protocole contrôlé qui évite de confondre vitesse, qualité et familiarité.

- **MVP** : huit tâches appariées, participants ou runs croisés, journal du temps et tests cachés.
- **Réussite** : taux de réussite, temps, taille des diffs, défauts et charge perçue avec analyse des biais.
- **Extensions** : novices/experts, types de prompts, maintenance différée.
- **Faisabilité** : petits dépôts jetables et budget de tours borné. Plan B : traces enregistrées complétées par des runs automatisés.

**CoursIA** : [Claude CLI Bases](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Vibe-Coding/Claude-Code/notebooks/01-Claude-CLI-Bases.ipynb) · [Claude CLI Sessions](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Vibe-Coding/Claude-Code/notebooks/02-Claude-CLI-Sessions.ipynb)

**Références** : [METR — Early-2025 AI Coding Study](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/) · [SWE-bench](https://www.swebench.com/) · [SPACE framework](https://queue.acm.org/detail.cfm?id=3454124)

## Évaluation, données et apprentissage

<a id="fiche-h4"></a>

### H4 — Provenance et détection de contenus synthétiques

**Difficulté : 3/5** · Mots-clés : `provenance`, `watermarking`, `detection`, `c2pa`

Comparer métadonnées de provenance, watermarking et classifieurs sur des contenus transformés. Le verrou technique est la robustesse après compression, recadrage ou paraphrase, pas un détecteur présenté sur ses données d'entraînement.

- **MVP** : corpus texte/image, trois transformations, deux méthodes de détection et vérification C2PA.
- **Réussite** : précision/rappel, calibration, robustesse par transformation et taux de faux positifs.
- **Extensions** : chaîne de provenance, attaques adaptatives, interface d'inspection.
- **Faisabilité** : contenus synthétiques et publics uniquement ; GPU non requis. Plan B : caractéristiques pré-calculées.

**CoursIA** : [Production Integration](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/04-Applications/04-3-Production-Integration.ipynb) · [Evaluating Generated Text](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/22_Evaluating_Generated_Text.ipynb)

**Références** : [C2PA Specification](https://c2pa.org/specifications/specifications/2.2/specs/C2PA_Specification.html) · [SynthID](https://deepmind.google/technologies/synthid/) · [NIST GenAI Profile](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence)

<a id="fiche-h5"></a>

### H5 — Constitution IA et coût des refus

**Difficulté : 3/5** · Mots-clés : `constitutional-ai`, `guardrails`, `refusal`, `evaluation`

Définir une politique de réponse, l'appliquer par prompt ou filtre puis mesurer sécurité et sur-refus. Le verrou technique est le compromis entre violations évitées et requêtes légitimes refusées.

- **MVP** : constitution versionnée, 100 scénarios sûrs/limites/dangereux, deux mécanismes et rapport.
- **Réussite** : taux de violation, faux refus, cohérence des explications, coût et latence.
- **Extensions** : critiques multiples, politiques par domaine, tests multilingues.
- **Faisabilité** : outils simulés et API texte ; budget inférieur à 10 €. Plan B : modèle local.

**CoursIA** : [Prompt Security Red Team](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/09b_Prompt_Security_RedTeam.ipynb) · [Production Patterns](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/09_Production_Patterns.ipynb)

**Références** : [Constitutional AI](https://arxiv.org/abs/2212.08073) · [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework) · [OWASP GenAI](https://genai.owasp.org/)

<a id="fiche-j2"></a>

### J2 — Analyste multimodal de données

**Difficulté : 4/5** · Mots-clés : `data-analysis`, `charts`, `multimodal`, `verification`

Répondre à des questions sur tableaux et graphiques en produisant calculs, visualisations et traces vérifiables. Le verrou technique est la correspondance entre réponse narrative, code exécuté et valeurs sources.

- **MVP** : trois jeux publics, 40 questions, génération de code bornée et rapport liant chaque chiffre à son calcul.
- **Réussite** : exactitude numérique, exécution, fidélité des graphiques et taux de réponses non justifiées.
- **Extensions** : images de graphiques, détection d'anomalies, questions interactives.
- **Faisabilité** : Python/pandas en sandbox ; GPU inutile. Plan B : requêtes et graphiques prédéfinis.

**CoursIA** : [Code Interpreter](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/07_Code_Interpreter.ipynb) · [Semantic Kernel Multimodal](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/07-SemanticKernel-MultiModal.ipynb)

**Références** : [Pandas](https://pandas.pydata.org/docs/) · [Vega-Lite](https://vega.github.io/vega-lite/) · [ChartQA](https://arxiv.org/abs/2203.10244)

<a id="fiche-j3"></a>

### J3 — Expériences reproductibles auto-validées

**Difficulté : 4/5** · Mots-clés : `experiments`, `reproducibility`, `code-generation`, `validation`

Transformer une hypothèse et un protocole structuré en expérience exécutable, puis contrôler que résultats et conclusions restent cohérents. Le verrou technique est la validation automatique de la chaîne expérimentale.

- **MVP** : dix protocoles simples, environnement figé, exécution isolée, contrôles statistiques et rapport.
- **Réussite** : taux d'exécution propre, reproductibilité multi-runs, erreurs méthodologiques détectées et conclusions corrigées.
- **Extensions** : seeds multiples, provenance des données, génération de contre-expériences.
- **Faisabilité** : expériences synthétiques courtes ; aucun GPU. Plan B : templates paramétrés sans génération libre.

**CoursIA** : [NotebookMaker](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/10-SemanticKernel-NotebookMaker.ipynb) · [Evaluating Generated Text](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/22_Evaluating_Generated_Text.ipynb)

**Références** : [ACM Artifact Review and Badging](https://www.acm.org/publications/policies/artifact-review-and-badging-current) · [SciPy](https://docs.scipy.org/doc/scipy/) · [Jupyter Reproducible Research](https://jupyter.org/)

<a id="fiche-k1"></a>

### K1 — Confidentialité des données synthétiques

**Difficulté : 4/5** · Mots-clés : `synthetic-data`, `privacy`, `utility`, `membership-inference`

Générer des données tabulaires synthétiques et mesurer simultanément utilité et risque de mémorisation. Le verrou technique est de ne pas déclarer les données privées sans attaque ni métrique.

- **MVP** : dataset public, deux générateurs, tests d'utilité et attaque simple d'inférence d'appartenance.
- **Réussite** : compromis utilité/confidentialité, intervalles de confiance et identification des lignes à risque.
- **Extensions** : confidentialité différentielle, attributs rares, audit par sous-groupes.
- **Faisabilité** : données publiques ou artificielles uniquement ; GPU inutile. Plan B : générateurs statistiques.

**CoursIA** : [Structured Outputs](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Supervised Fine-Tuning](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-03-Supervised-FineTuning-SFT-Python.ipynb)

**Références** : [NIST Privacy Framework](https://www.nist.gov/privacy-framework) · [Membership Inference Attacks](https://arxiv.org/abs/1610.05820) · [SDMetrics](https://docs.sdv.dev/sdmetrics/)

<a id="fiche-l3"></a>

### L3 — Tuteur adaptatif avec mesure d'apprentissage

**Difficulté : 4/5** · Mots-clés : `education`, `tutoring`, `adaptation`, `learning-gain`

Adapter explications et exercices à un modèle explicite de maîtrise, sans se réduire à générer un quiz. Le verrou technique est la décision pédagogique et la mesure du progrès.

- **MVP** : domaine borné, diagnostic initial, trois niveaux d'aide, journal de maîtrise et évaluation pré/post.
- **Réussite** : gain d'apprentissage sur scénarios ou utilisateurs consentants, calibration du modèle et qualité des feedbacks.
- **Extensions** : oubli espacé, plusieurs stratégies, accessibilité.
- **Faisabilité** : contenu public et données synthétiques ; étude humaine facultative et consentie. Plan B : apprenants simulés.

**CoursIA** : [Educational Content Generation](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/04-Applications/04-1-Educational-Content-Generation.ipynb) · [NotebookMaker](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/10-SemanticKernel-NotebookMaker.ipynb)

**Références** : [Knowledge Tracing](https://dl.acm.org/doi/10.5555/1161135.1161179) · [UNESCO guidance for generative AI in education](https://unesdoc.unesco.org/ark:/48223/pf0000386693) · [Bloom's taxonomy](https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/)

## Adaptation et inférence

<a id="fiche-i1"></a>

### I1 — QLoRA sans contamination de l'évaluation

**Difficulté : 4/5** · Mots-clés : `qlora`, `fine-tuning`, `data-leakage`, `evaluation`

Adapter un petit modèle à une tâche structurée et prouver que le gain ne vient ni d'une fuite train/test ni d'une mauvaise baseline. Les domaines de biais, recrutement, extraction documentaire et fallacies sont exclus.

- **MVP** : dataset versionné, contrôles de doublons, baseline prompt-only, QLoRA et test tenu à l'écart.
- **Réussite** : métrique adaptée, intervalles de confiance, coût mémoire/temps et analyse d'erreurs.
- **Extensions** : comparaison RAG, quantification, autre taille de modèle.
- **Faisabilité** : Colab ou GPU partagé, petit modèle uniquement ; budget cible inférieur à 10 € ; aucun GPU requis pour la démo si l'adapter est sauvegardé. Plan B : entraînement très réduit.

**CoursIA** : [QLoRA Quantization](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-02-QLoRA-Quantization-Python.ipynb) · [Supervised Fine-Tuning](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-03-Supervised-FineTuning-SFT-Python.ipynb) · [LoRA Fine-Tuning](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/21_LoRA_FineTuning.ipynb)

**Références** : [QLoRA](https://arxiv.org/abs/2305.14314) · [PEFT](https://huggingface.co/docs/peft/) · [Data Contamination in LLMs](https://arxiv.org/abs/2311.04850)

<a id="fiche-i2"></a>

### I2 — Inférence locale .NET face aux API cloud

**Difficulté : 3/5** · Mots-clés : `dotnet`, `local-inference`, `quantization`, `benchmark`

Comparer LLamaSharp, ONNX Runtime GenAI ou TensorSharp à une API cloud sur une tâche contrôlée. Construire une frontière coût–latence–qualité plutôt qu'un simple serveur local.

- **MVP** : deux moteurs locaux ou un local/un cloud, même jeu de 50 requêtes, instrumentation mémoire et tokens.
- **Réussite** : p50/p95, débit, mémoire, qualité, coût projeté et protocole reproductible.
- **Extensions** : quantifications multiples, batching, streaming.
- **Faisabilité** : modèles compacts ; CPU accepté ; budget cloud de comparaison inférieur à 8 €. Plan B : GGUF très quantifié et sous-échantillon.

**CoursIA** : [Inference Mechanics](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/10b_Inference_Mechanics.ipynb) · [Bake-off .NET TensorSharp / ORT GenAI](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/10d_TensorSharp_DotNet_Inference.ipynb) · [Quantization](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/11_Quantization.ipynb)

**Références** : [LLamaSharp](https://github.com/SciSharp/LLamaSharp) · [ONNX Runtime GenAI](https://onnxruntime.ai/docs/genai/) · [llama.cpp](https://github.com/ggml-org/llama.cpp)

<a id="fiche-i3"></a>

### I3 — Frontière coût-précision du test-time compute

**Difficulté : 4/5** · Mots-clés : `reasoning`, `test-time-compute`, `tree-of-thoughts`, `scaling`

Étudier combien de calcul à l'inférence améliore réellement une tâche vérifiable : échantillonnage multiple, vote, Tree of Thoughts et modèle à raisonnement natif.

- **MVP** : deux jeux de problèmes, quatre budgets de calcul, trois stratégies et vérificateur automatique.
- **Réussite** : courbes accuracy/coût/latence, analyse par difficulté et point de rendement décroissant.
- **Extensions** : sélection adaptative du budget, self-consistency pondérée.
- **Faisabilité** : très consommateur de tokens ; budget dur de 20 € et petites séries pilotes. Plan B : modèle local ou résultats mis en cache.

**CoursIA** : [Tree of Thoughts](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/15_Tree_of_Thoughts_Search.ipynb) · [Scaling Test-Time Compute](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/16_Scaling_Test_Time_Compute.ipynb) · [Native Reasoning vs Scaling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/17_Native_Reasoning_vs_Scaling.ipynb)

**Références** : [Tree of Thoughts](https://arxiv.org/abs/2305.10601) · [Self-Consistency](https://arxiv.org/abs/2203.11171) · [Scaling LLM Test-Time Compute](https://arxiv.org/abs/2408.03314)

<a id="fiche-i4"></a>

### I4 — Fusion et routage de modèles spécialisés

**Difficulté : 5/5** · Mots-clés : `model-merging`, `routing`, `specialization`, `benchmark`

Combiner ou router de petits modèles spécialisés sans perdre leurs compétences propres. Le verrou technique est de démontrer un gain sur un holdout multi-domaines plutôt que sur les données d'adaptation.

- **MVP** : deux spécialistes, une baseline générale, fusion ou routeur et jeu de test tenu à l'écart.
- **Réussite** : qualité par domaine, oubli, mémoire, latence et coût comparés aux spécialistes isolés.
- **Extensions** : plusieurs méthodes de fusion, routeur appris, quantification.
- **Faisabilité** : petits modèles et adapters ; GPU partagé recommandé. Plan B : fusion d'adapters pré-entraînés.

**CoursIA** : [Model Merging Routing](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-05-ModelMerging-Routing-Python.ipynb) · [QLoRA Quantization](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-02-QLoRA-Quantization-Python.ipynb)

**Références** : [MergeKit](https://github.com/arcee-ai/mergekit) · [TIES-Merging](https://arxiv.org/abs/2306.01708) · [PEFT](https://huggingface.co/docs/peft/)

## Génération sous contraintes symboliques

<a id="fiche-m1"></a>

### M1 — Du cahier des charges au planning certifié

**Difficulté : 4/5** · Mots-clés : `job-shop`, `extraction`, `cp-sat`, `certificat` · hybride CoursIA

Un atelier reçoit ses commandes en texte libre : machines, durées, ordre des opérations. Le modèle les traduit vers un schéma typé, un solveur calcule le planning. Le verrou est de séparer deux erreurs que l'on confond : mal traduire la commande, ou mal planifier une commande bien traduite.

- **MVP** : Extraction des machines, durées et précédences vers un schéma validé ; refus explicite quand un paramètre manque, au lieu de l'inventer ; résolution par CP-SAT et vérificateur indépendant du planning.
- **Réussite** : Champs exacts, collisions, précédences respectées, écart de durée totale par rapport à la solution calculée sur les données exactes. Trois stratégies : règles, LLM seul, LLM puis solveur. Reformulations et instances infaisables tenues à part.
- **Extensions** : Dates de livraison et pénalités de retard ; commande modifiée en cours de route ; explication du goulot d'étranglement.
- **Faisabilité** : OR-Tools sur CPU ; API texte ou modèle local ; budget cible inférieur à 8 €. Plan B : propositions du modèle figées, solveur et vérificateur exécutables sans réseau.

**CoursIA** : [Job-shop scheduling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-04-JobShopScheduling-Python.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [CSP et ordonnancement](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part2-CSP/CSP-4-Scheduling.ipynb)

**Références** : [OR-Tools — Job shop](https://developers.google.com/optimization/scheduling/job_shop) · [NL4Opt](https://arxiv.org/abs/2303.08233) · [OptiMUS](https://arxiv.org/abs/2310.06116)

<a id="fiche-m2"></a>

### M2 — Expliquer pourquoi un puzzle est impossible

**Difficulté : 4/5** · Mots-clés : `unsat-core`, `explication`, `carrés latins`, `certificat` · hybride CoursIA

Dire qu'une grille n'a pas de solution est facile ; dire pourquoi, en citant le plus petit groupe de contraintes qui se contredisent, l'est beaucoup moins. Le modèle rédige l'explication, un solveur vérifie que les contraintes citées suffisent réellement à l'incohérence.

- **MVP** : Générateur de carrés latins contradictoires ; explication en français produite par le modèle ; vérification que le sous-ensemble cité est insatisfaisable ; comparaison à la liste complète des contraintes et à un noyau minimal calculé.
- **Réussite** : Taux d'explications dont le sous-ensemble cité est réellement contradictoire, taille médiane de l'explication rapportée au noyau minimal, contraintes citées à tort.
- **Extensions** : Explication pas à pas ; grilles de Sudoku ; plusieurs noyaux pour la même grille.
- **Faisabilité** : Z3 sur CPU ; grilles 4×4 à 6×6 ; budget cible inférieur à 5 €. Plan B : lot de sorties figées livré avec les entrées et le vérificateur.

**CoursIA** : [Z3 — Unsat cores](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SMT/Z3-API/Z3-13-UnsatCores-Python.ipynb) · [Z3 — Noyaux minimaux](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SMT/Z3-API/Z3-13b-UnsatCores-MUS-Python.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Z3 Guide](https://microsoft.github.io/z3guide/) · [Explications pas à pas de CSP](https://arxiv.org/abs/2006.06343) · [Calcul de sous-ensembles minimaux insatisfaisables](https://doi.org/10.1007/s10817-007-9084-z)

<a id="fiche-m3"></a>

### M3 — Mots croisés : générer des définitions qui laissent une solution unique

**Difficulté : 4/5** · Mots-clés : `mots croisés`, `csp`, `unicité`, `définitions` · hybride CoursIA

Une bonne définition de mots croisés désigne un mot sans le donner. Sur un lexique fermé, le modèle écrit les définitions ; un solveur remplit la grille à partir des seuls mots qu'un lecteur juge compatibles. Une grille unique grâce aux croisements ne prouve pas que les définitions sont bonnes : c'est ce qu'il faut démêler.

- **MVP** : Lexique fermé, grille 5×5 à 7×7, définitions générées, domaine de chaque case construit depuis les réponses jugées compatibles, comptage des remplissages par énumération.
- **Réussite** : Unicité du remplissage, acceptabilité des définitions notée en aveugle, temps de résolution. Trois sources comparées : dictionnaire, génération libre, révision quand deux remplissages restent possibles. Des grilles entières sont tenues hors mise au point.
- **Extensions** : Niveaux de difficulté ; définitions à double sens ; grille générée en même temps que les définitions.
- **Faisabilité** : CP-SAT sur CPU ; lexique libre de droits ; budget cible inférieur à 8 €. Plan B : définitions figées et solveur local.

**CoursIA** : [Mots croisés en CSP](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-16-Crossword-CSP-Python.ipynb) · [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Automated Crossword Solving](https://arxiv.org/abs/2205.09665) · [Dr.Fill](https://arxiv.org/abs/1401.4597) · [OR-Tools — CP-SAT](https://developers.google.com/optimization/cp/cp_solver)

<a id="fiche-m4"></a>

### M4 — Transformer une procédure en machine à états

**Difficulté : 4/5** · Mots-clés : `automates`, `transitions`, `génération typée`, `vérification`

Un règlement de prêt de matériel décrit des états et des transitions sans jamais les nommer. Le modèle doit en tirer une machine à états typée. Le verrou est la vérification exhaustive : sur toutes les séquences courtes, la machine accepte-t-elle exactement ce que le règlement autorise ?

- **MVP** : Règles de prêt traduites en transitions typées ; deux stratégies : prompt direct, génération guidée par des exemples de traces ; interpréteur de référence écrit à la main.
- **Réussite** : Traces acceptées à tort et refus injustifiés sur toutes les séquences jusqu'à quatre événements ; états inatteignables ; transitions oubliées par rapport à la référence.
- **Extensions** : Apprentissage actif de l'automate par requêtes ; export SCXML ; gardes portant sur des données.
- **Faisabilité** : Python pur ; API texte ou modèle local ; budget cible inférieur à 5 €. Plan B : sorties figées et vérificateur local.

**CoursIA** : [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Décodage contraint](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03c_Constrained_Decoding_Python.ipynb) · [Apprentissage actif d'automates](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SymbolicLearning/SL-10-ActiveAutomataLearning.ipynb)

**Références** : [W3C — SCXML](https://www.w3.org/TR/scxml/) · [Génération guidée efficace](https://arxiv.org/abs/2307.09702) · [Stately — XState](https://stately.ai/docs)

<a id="fiche-m5"></a>

### M5 — Produire un contre-exemple plutôt qu'un avis

**Difficulté : 3/5** · Mots-clés : `contre-exemple`, `tests`, `règles`, `vérification`

Deux règles tarifaires semblent équivalentes. Au lieu de demander au modèle si elles le sont, on lui demande un panier sur lequel elles divergent ; un interpréteur tranche. Le projet mesure si le modèle trouve mieux que le hasard, et plus petit qu'un solveur.

- **MVP** : Dix paires de règles, dont certaines réellement équivalentes ; paniers proposés par le modèle ; interpréteur des deux règles ; tirage aléatoire comme plancher.
- **Réussite** : Divergences vérifiées par proposition, valeur minimale des paniers trouvés, affirmations d'équivalence fausses. Même budget de propositions pour le modèle et pour le hasard.
- **Extensions** : Recherche du contre-exemple par Z3 ; règles à seuils ; réduction automatique du contre-exemple.
- **Faisabilité** : Python pur ; GPU inutile ; budget cible inférieur à 5 €. Plan B : lot de propositions figées, interpréteur local.

**CoursIA** : [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Z3 — Introduction](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SMT/Z3-API/Z3-01-Introduction-Python.ipynb)

**Références** : [Hypothesis](https://hypothesis.readthedocs.io/) · [QuickCheck](https://doi.org/10.1145/351240.351266) · [Z3 Guide](https://microsoft.github.io/z3guide/)

<a id="fiche-m6"></a>

### M6 — Traduire une règle en contraintes de planning

**Difficulté : 3/5** · Mots-clés : `emploi du temps`, `grammaire`, `contraintes`, `généralisation` · hybride CoursIA

Douze règlements fictifs décrivent qui peut occuper quel créneau. Le modèle les traduit en contraintes ; on vérifie la traduction sur des plannings qu'il n'a jamais vus. Le verrou est la forme de la sortie : texte libre, grammaire limitée ou appel direct au solveur ne se trompent pas de la même façon.

- **MVP** : Douze règlements, six créneaux, trois formes de sortie comparées, solveur exhaustif comme référence.
- **Réussite** : Violations sur des plannings jamais vus, problèmes déclarés possibles à tort, règles ambiguës signalées plutôt que tranchées en silence.
- **Extensions** : Préférences en plus des interdictions ; règlements contradictoires ; passage à une semaine entière.
- **Faisabilité** : CP-SAT ou énumération en Python ; budget cible inférieur à 5 €. Plan B : sorties figées et vérificateur local.

**CoursIA** : [Emplois du temps](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-05-Timetabling-Python.ipynb) · [Planning infirmier](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-03-NurseScheduling-Python.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [OR-Tools — Employee scheduling](https://developers.google.com/optimization/scheduling/employee_scheduling) · [Logic-LM](https://arxiv.org/abs/2305.12295) · [NL4Opt](https://arxiv.org/abs/2303.08233)

<a id="fiche-m7"></a>

### M7 — Inventer des énigmes à solution unique

**Difficulté : 3/5** · Mots-clés : `énigmes`, `déduction`, `unicité`, `indices` · hybride CoursIA

Une énigme de déduction à quatre personnages n'est réussie que si ses indices désignent une seule solution, sans indice inutile. Le modèle écrit les indices ; un énumérateur indépendant compte les solutions. Résoudre l'énigme ne prouve rien : il faut compter.

- **MVP** : Générateur d'indices pour quatre personnages et trois attributs ; énumérateur de solutions ; deux stratégies : génération directe, révision après comptage.
- **Réussite** : Sur trente tirages : énigmes à solution unique, indices superflus (retirables sans perdre l'unicité), énigmes sans solution.
- **Extensions** : Difficulté mesurée par le nombre d'étapes de déduction ; indices négatifs ; énigme d'Einstein complète.
- **Faisabilité** : Python ou Z3 sur CPU ; budget cible inférieur à 5 €. Plan B : lot d'indices figés et énumérateur local.

**CoursIA** : [Z3 — Énigme d'Einstein](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SMT/Z3-API/Z3-09-Enigme-Einstein-Python.ipynb) · [CSP — Fondamentaux](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part2-CSP/CSP-1-Fundamentals.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [SatLM](https://arxiv.org/abs/2305.09656) · [Logic-LM](https://arxiv.org/abs/2305.12295) · [Z3 Guide](https://microsoft.github.io/z3guide/)

<a id="fiche-m8"></a>

### M8 — Sudoku : expliquer le prochain coup, pas la grille

**Difficulté : 4/5** · Mots-clés : `sudoku`, `explication`, `stratégies humaines`, `vérification` · hybride CoursIA

Un solveur remplit une grille en quelques millisecondes mais n'apprend rien à un joueur. Le projet demande au modèle de justifier un seul coup avec une technique nommée (candidat unique, paire nue). Un moteur de stratégies humaines vérifie que la technique citée s'applique vraiment à cette case.

- **MVP** : Lot de grilles par niveau ; explication structurée : case, valeur, technique, cases invoquées ; vérification par le moteur de stratégies ; comparaison au modèle seul sans vérification.
- **Réussite** : Coups corrects, techniques citées qui s'appliquent réellement, explications justes pour une mauvaise raison. Résultats séparés par niveau de difficulté.
- **Extensions** : Choix du coup le plus simple à expliquer ; tutorat adaptatif ; comparaison à un modèle de raisonnement.
- **Faisabilité** : Moteur de stratégies sur CPU ; budget cible inférieur à 8 €. Plan B : explications figées et moteur local.

**CoursIA** : [Sudoku par LLM](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Sudoku/Sudoku-17-LLM-Python.ipynb) · [Stratégies humaines](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Sudoku/Sudoku-08-HumanStrategies-Python.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Norvig — Solving Every Sudoku Puzzle](https://norvig.com/sudoku.html) · [Explications pas à pas de CSP](https://arxiv.org/abs/2006.06343) · [Recurrent Relational Networks](https://arxiv.org/abs/1711.08028)

<a id="fiche-m9"></a>

### M9 — Planification : le modèle propose, le planificateur dispose

**Difficulté : 4/5** · Mots-clés : `pddl`, `planification`, `neuro-symbolique`, `validation` · hybride CoursIA

Un LLM écrit volontiers un plan plausible et faux. Deux façons de l'employer s'opposent : lui faire écrire le plan, ou lui faire écrire le problème en PDDL et laisser un planificateur chercher. Le projet mesure laquelle tient quand le problème grossit.

- **MVP** : Deux domaines classiques (logistique, monde des blocs) ; trois stratégies : plan direct, traduction en PDDL puis planificateur, LLM qui réduit l'espace de recherche ; validateur de plans indépendant.
- **Réussite** : Plans valides, plans optimaux, erreurs de traduction PDDL. Courbes selon la taille du problème ; noms d'objets permutés pour écarter la mémorisation.
- **Extensions** : Boucle de réparation avec le message du validateur ; domaine inventé pour le projet ; planification temporelle.
- **Faisabilité** : Planificateur classique sur CPU ; budget cible inférieur à 10 €. Plan B : sorties du modèle figées, planificateur et validateur locaux.

**CoursIA** : [Planification par LLM](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/Planners/04-NeuroSymbolic/Planners-10-LLM-Planning-Python.ipynb) · [LLM réducteur d'espace](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/Planners/04-NeuroSymbolic/Planners-10b-LLM-Space-Reducer-Python.ipynb) · [Bases de PDDL](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/Planners/01-Foundation/Planners-02-PDDL-Basics-Python.ipynb)

**Références** : [LLM+P](https://arxiv.org/abs/2304.11477) · [PlanBench](https://arxiv.org/abs/2206.10498) · [LLM-Modulo](https://arxiv.org/abs/2402.01817) · [Fast Downward](https://www.fast-downward.org/)

<a id="fiche-m10"></a>

### M10 — Picross : d'une image générée à une grille à solution unique

**Difficulté : 4/5** · Mots-clés : `génération d’image`, `picross`, `unicité`, `binarisation` · hybride CoursIA

Un picross est une image cachée derrière des indices. On part d'un prompt, on génère une image, on la réduit en grille noir et blanc : le puzzle obtenu a-t-il une seule solution, et reconnaît-on encore le sujet ? Le verrou est ce double critère, que ni le générateur ni le solveur ne garantit seul.

- **MVP** : Chaîne prompt, image, grille 15×15, indices ; solveur qui compte les solutions ; réparation minimale des grilles ambiguës en changeant le moins de cases possible.
- **Réussite** : Grilles à solution unique avant et après réparation, nombre de cases modifiées, sujet reconnu en aveugle par des lecteurs. Comparaison de deux méthodes de binarisation.
- **Extensions** : Picross en couleurs ; difficulté mesurée par les techniques nécessaires ; série thématique cohérente.
- **Faisabilité** : Génération par API ou modèle local léger ; budget cible inférieur à 10 €. Plan B : banque d'images libres déjà générées, solveur local.

**CoursIA** : [Picross](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-11-Picross-Python.ipynb) · [SDXL Turbo](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/01-Foundation/01-4-Forge-SD-XL-Turbo.ipynb) · [Opérations d'image de base](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/01-Foundation/01-3-Basic-Image-Operations.ipynb)

**Références** : [Survey of Paint-by-Number Puzzle Solvers](https://webpbn.com/survey/) · [Latent Diffusion Models](https://arxiv.org/abs/2112.10752) · [scikit-image — Thresholding](https://scikit-image.org/docs/stable/auto_examples/segmentation/plot_thresholding.html)

<a id="fiche-m11"></a>

### M11 — Niveaux générés, jouabilité prouvée

**Difficulté : 4/5** · Mots-clés : `génération procédurale`, `wfc`, `jouabilité`, `a*` · hybride CoursIA

Un niveau généré peut être joli et impossible à finir. Le projet combine une génération par motifs (Wave Function Collapse) guidée par une consigne en français, et un solveur qui prouve que le niveau se termine et en combien de coups au minimum.

- **MVP** : Jeu de tuiles simple ; consigne traduite en contraintes de génération ; solveur A* qui certifie la jouabilité et la longueur minimale ; rejet ou réparation des niveaux injouables.
- **Réussite** : Niveaux jouables, respect de la consigne (difficulté demandée contre longueur minimale mesurée), diversité des niveaux. Comparaison à une génération sans consigne.
- **Extensions** : Courbe de difficulté sur dix niveaux ; récit qui relie les niveaux ; test par des joueurs.
- **Faisabilité** : Python sur CPU ; budget cible inférieur à 5 €. Plan B : consignes déjà traduites en paramètres, génération et preuve locales.

**CoursIA** : [Génération procédurale WFC](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-19-ProceduralGeneration-WFC-Python.ipynb) · [Rush Hour et A*](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-33-RushHour-Admissible-Astar-Python.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) · [PCGML](https://arxiv.org/abs/1702.00539) · [Level Generation Through LLMs](https://arxiv.org/abs/2302.05817) · [MarioGPT](https://arxiv.org/abs/2302.05981)

<a id="fiche-m12"></a>

### M12 — Une heuristique écrite par un LLM est-elle admissible ?

**Difficulté : 4/5** · Mots-clés : `a*`, `heuristique`, `admissibilité`, `génération de code` · hybride CoursIA

A* ne garantit le plus court chemin que si son heuristique ne surestime jamais. Un modèle peut écrire une heuristique en dix lignes ; rien ne dit qu'elle est admissible. Le projet la soumet à un audit : comparaison aux distances exactes sur de petites instances, puis mesure du gain réel.

- **MVP** : Taquin et Rush Hour ; heuristiques générées en code ; exécution en bac à sable ; audit d'admissibilité sur toutes les positions à faible profondeur ; comparaison à la distance de Manhattan.
- **Réussite** : Heuristiques admissibles, nœuds développés, solutions optimales perdues quand l'heuristique surestime. Une heuristique plus rapide et fausse est comptée comme un échec.
- **Extensions** : Boucle d'amélioration à partir des contre-exemples ; bases de motifs ; recherche évolutionnaire de programmes.
- **Faisabilité** : Python sur CPU ; budget cible inférieur à 8 €. Plan B : heuristiques générées figées, audit local.

**CoursIA** : [Taquin et A* admissible](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-34-15Puzzle-Admissible-Astar-Python.ipynb) · [Rush Hour et A* admissible](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-33-RushHour-Admissible-Astar-Python.ipynb) · [Code interpreter](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/07_Code_Interpreter.ipynb)

**Références** : [FunSearch](https://doi.org/10.1038/s41586-023-06924-6) · [Evolution of Heuristics](https://arxiv.org/abs/2401.02051) · [AIMA](https://aima.cs.berkeley.edu/)

<a id="fiche-m13"></a>

### M13 — Du brief logistique à la tournée optimisée

**Difficulté : 4/5** · Mots-clés : `tournées`, `vrp`, `extraction`, `optimisation` · hybride CoursIA

Un responsable décrit ses livraisons par message : adresses, créneaux, capacité du camion. Le modèle en tire un problème de tournées, un solveur le résout. Le verrou est la contrainte implicite : celle que le texte sous-entend et que le modèle oublie ou invente.

- **MVP** : Vingt briefs fictifs avec contraintes annotées ; extraction vers un schéma ; résolution par OR-Tools ; compte rendu en français qui cite les contraintes prises en compte.
- **Réussite** : Contraintes extraites à tort ou oubliées, tournées réalisables, surcoût par rapport à la solution sur les données exactes, briefs incomplets correctement refusés.
- **Extensions** : Fenêtres horaires ; modification en cours de journée ; comparaison à une métaheuristique.
- **Faisabilité** : OR-Tools sur CPU ; distances synthétiques ; budget cible inférieur à 8 €. Plan B : extractions figées, solveur local.

**CoursIA** : [Tournées de véhicules](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-17-VRP-Logistics-Python.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [OR-Tools — Vehicle routing](https://developers.google.com/optimization/routing/vrp) · [NL4Opt](https://arxiv.org/abs/2303.08233) · [Attention, Learn to Solve Routing Problems!](https://arxiv.org/abs/1803.08475)

<a id="fiche-m14"></a>

### M14 — Menus sous contraintes : du besoin en français au plan certifié

**Difficulté : 3/5** · Mots-clés : `smt`, `contraintes`, `nutrition`, `traduction` · hybride CoursIA

« Sans gluten, moins de 2 000 kcal, pas deux fois le même plat dans la semaine. » Le modèle traduit ces demandes en contraintes sur une table d'aliments fictive, Z3 trouve un menu ou prouve qu'il n'en existe pas. Le verrou est la demande impossible : le système doit la reconnaître et dire quelle exigence relâcher.

- **MVP** : Table d'aliments fictive ; trente demandes dont dix infaisables ; traduction en contraintes ; menu ou noyau de contraintes contradictoires restitué en français.
- **Réussite** : Demandes correctement traduites, menus qui respectent toutes les contraintes, infaisabilités reconnues, exigence à relâcher correctement désignée.
- **Extensions** : Optimisation du coût ; préférences pondérées ; dialogue de relâchement en plusieurs tours.
- **Faisabilité** : Z3 sur CPU ; données fictives uniquement, aucun conseil médical ; budget cible inférieur à 5 €. Plan B : traductions figées, solveur local.

**CoursIA** : [Z3 — Meal planner](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SMT/Z3-API/Z3-16-Meal-Planner-Python.ipynb) · [Z3 — Capstone patient](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SMT/Z3-API/Z3-16c-Meal-Planner-Patient-Capstone-Python.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb)

**Références** : [Z3 Guide](https://microsoft.github.io/z3guide/) · [SatLM](https://arxiv.org/abs/2305.09656) · [Logic-LM](https://arxiv.org/abs/2305.12295)

## Mesures, causalité et raisonnement quantitatif

<a id="fiche-n1"></a>

### N1 — Conserver les unités dans un compte rendu

**Difficulté : 3/5** · Mots-clés : `unités`, `calcul outillé`, `conversion`, `cohérence`

Un compte rendu de mesures mélange mètres et pieds, minutes et heures. Le modèle doit convertir puis rédiger. Le verrou est la cohérence entre le chiffre et la phrase qui le commente : un calcul juste suivi d'un commentaire faux reste une erreur.

- **MVP** : Vingt jeux de mesures fictives de longueur et de durée ; deux stratégies : rédaction directe, calcul par outil puis rédaction ; vérificateur d'unités.
- **Réussite** : Erreur relative, unité finale correcte, contradictions entre chiffre et commentaire (« en hausse » pour une valeur en baisse). Vingt changements d'unités testés.
- **Extensions** : Unités composées (km/h, kWh) ; chiffres significatifs ; tableaux à unités mixtes.
- **Faisabilité** : Python avec Pint ; API texte ou modèle local ; budget cible inférieur à 3 €. Plan B : sorties figées et vérificateur local.

**CoursIA** : [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Code interpreter](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/07_Code_Interpreter.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Pint](https://pint.readthedocs.io/) · [BIPM — Brochure SI](https://www.bipm.org/en/publications/si-brochure) · [PAL](https://arxiv.org/abs/2211.10435)

<a id="fiche-n2"></a>

### N2 — Générer un mode d'emploi qui respecte les dépendances

**Difficulté : 3/5** · Mots-clés : `graphe`, `ordre topologique`, `notice`, `verbalisation`

Une notice d'assemblage est un ordre partiel mis en phrases : on ne visse pas un panneau avant d'avoir posé son support. Le projet compare un modèle qui rédige directement depuis le graphe des pièces et un modèle qui verbalise un ordre calculé.

- **MVP** : Dix graphes de pièces ; deux stratégies : génération directe, tri topologique puis verbalisation ; analyseur qui retrouve l'ordre des étapes dans le texte produit.
- **Réussite** : Étapes prématurées, pièces jamais introduites, étapes inventées. Test répété après permutation des identifiants pour écarter les ordres mémorisés.
- **Extensions** : Étapes parallélisables pour deux personnes ; outils requis ; notice illustrée.
- **Faisabilité** : Python avec NetworkX ; budget cible inférieur à 3 €. Plan B : sorties figées et analyseur local.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Bases de PDDL](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/Planners/01-Foundation/Planners-02-PDDL-Basics-Python.ipynb)

**Références** : [NetworkX — DAG](https://networkx.org/documentation/stable/reference/algorithms/dag.html) · [proScript](https://arxiv.org/abs/2104.08251) · [Python — graphlib](https://docs.python.org/3/library/graphlib.html)

<a id="fiche-n3"></a>

### N3 — Un assistant distingue-t-il observer et intervenir ?

**Difficulté : 4/5** · Mots-clés : `causalité`, `do-calcul`, `outils`, `abstention` · hybride CoursIA

« Les clients qui ont reçu la remise achètent plus » ne dit pas ce qui arrive si l'on donne la remise à tous. Sur des graphes causaux fictifs, le modèle doit reconnaître si la question porte sur une observation ou sur une intervention, puis appeler le bon calcul.

- **MVP** : Deux graphes causaux sur des variables fictives ; moteur qui calcule les deux quantités ; trois stratégies : réponse directe, appel d'outil libre, appel avec contrôle des arguments.
- **Réussite** : Choix correct de l'opération, erreur sur l'effet, abstention quand le graphe ne permet pas de conclure. Le facteur de confusion varie sans que le texte de la question change.
- **Extensions** : Questions contrefactuelles ; graphe à découvrir ; explication du biais en une phrase vérifiable.
- **Faisabilité** : DoWhy ou PyMC sur CPU ; budget cible inférieur à 8 €. Plan B : réponses figées, moteur causal local.

**CoursIA** : [Inférence causale avec PyMC](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/PyMC/PyMC-05-Causal-Inference.ipynb) · [Calcul do](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/Causalite/Causalite-01-Calcul-Do-Python.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb)

**Références** : [CLadder](https://arxiv.org/abs/2312.04350) · [Corr2Cause](https://arxiv.org/abs/2306.05836) · [DoWhy](https://www.pywhy.org/dowhy/)

<a id="fiche-n4"></a>

### N4 — Rédiger un bulletin qui respecte l'incertitude

**Difficulté : 3/5** · Mots-clés : `incertitude`, `intervalles`, `rédaction`, `calibration`

Un bulletin de prévision transforme des intervalles en phrases. « La fréquentation va augmenter » est faux si l'intervalle contient zéro. Le projet mesure si le texte généré dit exactement ce que les chiffres permettent de dire.

- **MVP** : Trente séries fictives avec intervalles ; trois stratégies : gabarit, rédaction libre, consigne avec bornes explicites ; extracteur des affirmations de tendance.
- **Réussite** : Affirmations de hausse ou de baisse certaine quand les scénarios se contredisent, intervalles cités correctement, vocabulaire de probabilité cohérent avec une échelle fixée à l'avance.
- **Extensions** : Échelle verbale du GIEC ; lecteurs testés sur leur compréhension ; prévisions conformes.
- **Faisabilité** : Python sur CPU ; budget cible inférieur à 3 €. Plan B : bulletins figés et extracteur local.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Séries temporelles](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/ML/ML.Net/ML-05-TimeSeries-Python.ipynb)

**Références** : [Teaching Models to Express Their Uncertainty in Words](https://arxiv.org/abs/2205.14334) · [Just Ask for Calibration](https://arxiv.org/abs/2305.14975) · [Introduction à la prédiction conforme](https://arxiv.org/abs/2107.07511)

<a id="fiche-n5"></a>

### N5 — Auditer les dénominateurs d'une synthèse

**Difficulté : 3/5** · Mots-clés : `simpson`, `sous-populations`, `synthèse`, `audit`

Une synthèse de tableau compare des taux sans dire sur combien de personnes ils portent. Quand les groupes sont de tailles inégales, la tendance globale peut s'inverser dans chaque sous-groupe. Le projet fabrique ces cas et mesure si le modèle les voit.

- **MVP** : Générateur de tableaux à sous-populations inégales, dont des cas de paradoxe de Simpson ; synthèses générées ; vérificateur qui recalcule chaque comparaison citée.
- **Réussite** : Comparaisons qui nomment la bonne population, comparaisons qui restent vraies après inversion des tailles de groupes, paradoxes signalés.
- **Extensions** : Recommandation d'une stratification ; données réelles publiques ; graphique associé.
- **Faisabilité** : pandas sur CPU ; budget cible inférieur à 3 €. Plan B : synthèses figées et vérificateur local.

**CoursIA** : [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Échelle de Pearl](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/Causalite/Causalite-00-Echelle-de-Pearl-Intro-Python.ipynb)

**Références** : [Stanford Encyclopedia — Simpson's Paradox](https://plato.stanford.edu/entries/paradox-simpson/) · [TabFact](https://arxiv.org/abs/1909.02164) · [pandas — Group by](https://pandas.pydata.org/docs/user_guide/groupby.html)

<a id="fiche-n6"></a>

### N6 — Faire réviser une conclusion après une intervention

**Difficulté : 4/5** · Mots-clés : `simulation`, `files d’attente`, `révision`, `intervention` · hybride CoursIA

Dans un petit simulateur de files d'attente, le modèle prédit l'effet d'un changement (ouvrir un guichet, allonger le service), puis voit le résultat. Révise-t-il sa conclusion pour la bonne raison ? Le projet oppose ce que l'on apprend en observant et ce que l'on apprend en modifiant un paramètre.

- **MVP** : Simulateur à événements discrets ; scénarios où observation et intervention donnent des réponses différentes ; prédiction, résultat, révision demandée au modèle.
- **Réussite** : Sur des scénarios tenus à part : signe correct de l'effet, révisions justifiées par une raison compatible avec le simulateur, révisions inutiles quand la première réponse était juste.
- **Extensions** : Deux paramètres modifiés à la fois ; effet non monotone près de la saturation ; question du type « et si on n'avait rien changé ».
- **Faisabilité** : SimPy sur CPU ; budget cible inférieur à 5 €. Plan B : réponses figées et simulateur local.

**CoursIA** : [Échelle de Pearl](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/Causalite/Causalite-00-Echelle-de-Pearl-Intro-Python.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb)

**Références** : [SimPy](https://simpy.readthedocs.io/) · [Causal Reasoning and Large Language Models](https://arxiv.org/abs/2305.00050) · [CLadder](https://arxiv.org/abs/2312.04350)

<a id="fiche-n7"></a>

### N7 — Du récit d'un dilemme au réseau de décision

**Difficulté : 4/5** · Mots-clés : `théorie de la décision`, `élicitation`, `utilité`, `valeur de l’information` · hybride CoursIA

Une personne raconte un choix difficile : accepter une offre, attendre une information, payer pour un test. Le modèle interroge, puis construit un réseau de décision avec probabilités et utilités ; un moteur calcule la meilleure action. Le verrou est l'élicitation : la décision calculée change-t-elle quand on reformule le même récit ?

- **MVP** : Quinze dilemmes fictifs avec modèle de référence ; dialogue d'élicitation ; réseau produit dans un schéma typé ; calcul de l'utilité espérée et de la valeur d'une information supplémentaire.
- **Réussite** : Structure correcte du réseau, décision identique à la référence, stabilité sous reformulation du récit, sensibilité aux utilités annoncées.
- **Extensions** : Attitude face au risque ; décision séquentielle ; explication de la valeur de l'information en français.
- **Faisabilité** : PyMC ou calcul direct sur CPU ; cas fictifs uniquement ; budget cible inférieur à 8 €. Plan B : réseaux figés, moteur local.

**CoursIA** : [Réseaux de décision](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/DecisionTheory/DecPyMC/DecPyMC-04-Decision-Networks.ipynb) · [Valeur de l'information](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/DecisionTheory/DecPyMC/DecPyMC-05-Value-Information.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Eliciting Human Preferences with Language Models](https://arxiv.org/abs/2310.11589) · [Stanford Encyclopedia — Decision Theory](https://plato.stanford.edu/entries/decision-theory/) · [PyMC](https://www.pymc.io/)

<a id="fiche-n8"></a>

### N8 — Hypothèses générées, effets estimés

**Difficulté : 5/5** · Mots-clés : `causalité`, `simulation`, `hypothèses`, `science automatisée` · hybride CoursIA

Un modèle propose une hypothèse causale sur une situation sociale simulée (une négociation, une enchère), conçoit l'expérience, puis l'effet est estimé sur les données produites. Le verrou est d'éviter le raisonnement circulaire : l'hypothèse doit pouvoir échouer.

- **MVP** : Un scénario simulé avec agents ; hypothèses formulées comme graphe causal ; plan d'expérience ; estimation de l'effet avec intervalle ; hypothèses préenregistrées avant l'exécution.
- **Réussite** : Hypothèses réfutées, effets retrouvés quand ils sont injectés à la main, effets annoncés à tort sur un scénario nul.
- **Extensions** : Second scénario ; comparaison à des hypothèses humaines ; analyse de sensibilité à un facteur de confusion.
- **Faisabilité** : DoWhy sur CPU ; simulations courtes ; budget cible inférieur à 15 €. Plan B : transcriptions de simulation figées, estimation locale.

**CoursIA** : [Science sociale automatisée](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/Causalite/Causalite-10-Science-Sociale-Automatisee-Python.ipynb) · [DoWhy — Estimand et intervention](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/Causalite/Causalite-02-DoWhy-Estimand-Intervention-Python.ipynb) · [Agents génératifs](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/24_Generative_Agents_MiniMonde.ipynb)

**Références** : [Automated Social Science](https://arxiv.org/abs/2404.11794) · [DoWhy](https://www.pywhy.org/dowhy/) · [Generative Agents](https://arxiv.org/abs/2304.03442)

<a id="fiche-n9"></a>

### N9 — Programme probabiliste généré, postérieur vérifié

**Difficulté : 4/5** · Mots-clés : `programmation probabiliste`, `pymc`, `génération de code`, `diagnostics` · hybride CoursIA

Décrire un problème en français et obtenir le modèle bayésien correspondant : la promesse est forte. Le code généré s'exécute souvent, et calcule parfois autre chose que ce qui était demandé. Le projet vérifie le postérieur lui-même, sur des données simulées dont on connaît les paramètres.

- **MVP** : Douze énoncés (mélange, régression hiérarchique, point de rupture) ; code PyMC généré ; exécution bornée ; contrôle des diagnostics et récupération des paramètres simulés.
- **Réussite** : Modèles qui s'exécutent, diagnostics de convergence corrects, paramètres vrais dans l'intervalle de crédibilité, modèles valides mais différents de l'énoncé.
- **Extensions** : Boucle de correction à partir des diagnostics ; choix des lois a priori justifié ; comparaison de modèles.
- **Faisabilité** : PyMC sur CPU, modèles de petite taille ; budget cible inférieur à 8 €. Plan B : programmes générés figés, échantillonnage local.

**CoursIA** : [Réseaux bayésiens avec PyMC](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/PyMC/PyMC-04-Bayesian-Networks.ipynb) · [Débogage PyMC](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/PyMC/PyMC-02b-Debugging-Python.ipynb) · [Code interpreter](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/07_Code_Interpreter.ipynb)

**Références** : [From Word Models to World Models](https://arxiv.org/abs/2306.12672) · [Bayesian Workflow](https://arxiv.org/abs/2011.01808) · [ArviZ](https://python.arviz.org/)

## Accessibilité et transmission du sens

<a id="fiche-o1"></a>

### O1 — Adapter un texte sans perdre ses exceptions

**Difficulté : 3/5** · Mots-clés : `simplification`, `facile à lire`, `exceptions`, `fidélité`

Réécrire une consigne en langage facile à lire raccourcit les phrases et efface parfois le « sauf si » qui changeait la décision. Le projet mesure séparément la lisibilité gagnée et les décisions conservées.

- **MVP** : Vingt consignes fictives dont l'exception change la décision ; deux stratégies : simplification libre, réécriture contrôlée par des cas de test ; questions de décision posées sur le texte simplifié.
- **Réussite** : Longueur des phrases, décisions conservées, exceptions effacées. Les deux mesures sont rapportées séparément, jamais fusionnées en un score.
- **Extensions** : Relecture par des lecteurs ; pictogrammes ; consignes à exceptions emboîtées.
- **Faisabilité** : API texte ou modèle local ; budget cible inférieur à 3 €. Plan B : réécritures figées, évaluation locale.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Évaluer un texte généré](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/22_Evaluating_Generated_Text.ipynb)

**Références** : [Inclusion Europe — Easy-to-read](https://www.inclusion-europe.eu/easy-to-read/) · [SARI](https://aclanthology.org/Q16-1029/) · [Evaluating Factuality in Text Simplification](https://arxiv.org/abs/2204.07562)

<a id="fiche-o2"></a>

### O2 — Restituer un tableau avec un lecteur d'écran

**Difficulté : 3/5** · Mots-clés : `accessibilité`, `tableaux`, `linéarisation`, `lecteur d’écran`

Un lecteur d'écran lit un tableau case après case. Avec des en-têtes imbriqués, l'auditeur perd vite le fil. Le projet génère une description linéaire et mesure si l'on peut répondre à des questions sans voir le tableau.

- **MVP** : Dix tableaux à en-têtes imbriqués ; deux stratégies : lecture ligne à ligne, description guidée par les relations entre cellule et en-têtes ; dix questions par tableau.
- **Réussite** : Exactitude des réponses sans accès à l'original, confusions de ligne ou de colonne, longueur de la description.
- **Extensions** : Synthèse vocale et test d'écoute ; cellules fusionnées ; résumé avant le détail.
- **Faisabilité** : API texte ou modèle local ; budget cible inférieur à 3 €. Plan B : descriptions figées, questionnaire local.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Synthèse vocale locale](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-5-Kokoro-TTS-Local.ipynb)

**Références** : [W3C WAI — Tables Tutorial](https://www.w3.org/WAI/tutorials/tables/) · [ToTTo](https://arxiv.org/abs/2004.14373) · [WCAG 2.2](https://www.w3.org/TR/WCAG22/)

<a id="fiche-o3"></a>

### O3 — Choisir un texte alternatif selon la tâche

**Difficulté : 3/5** · Mots-clés : `texte alternatif`, `graphiques`, `accessibilité`, `vision`

La bonne description d'un graphique dépend de ce que le lecteur veut en faire : repérer un maximum ou comparer deux tendances. Le projet génère une description par tâche et la compare à une légende unique, sans récompenser la simple longueur.

- **MVP** : Douze graphiques synthétiques dont les données sont connues ; deux descriptions par graphique ; lecteurs ou modèle juge qui répondent sans voir le graphique.
- **Réussite** : Réponses retrouvées par tâche, à longueur de description égale ; erreurs factuelles par rapport aux données sources.
- **Extensions** : Description à plusieurs niveaux de détail ; graphiques réels ; modèle de vision comparé à la génération depuis les données.
- **Faisabilité** : API vision ou génération depuis les données ; budget cible inférieur à 8 €. Plan B : descriptions figées produites depuis les données.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Semantic Kernel multimodal](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/07-SemanticKernel-MultiModal.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [W3C WAI — Alt Decision Tree](https://www.w3.org/WAI/tutorials/images/decision-tree/) · [VisText](https://arxiv.org/abs/2307.05356) · [Four-Level Model of Semantic Content](https://arxiv.org/abs/2110.04406)

<a id="fiche-o4"></a>

### O4 — Écrire une consigne qui survit à la traduction

**Difficulté : 3/5** · Mots-clés : `traduction`, `lexique imposé`, `exécution`, `ambiguïté`

Une consigne spatiale (« avance de deux cases, puis à gauche ») se vérifie en l'exécutant. Le projet traduit des consignes avec un lexique bilingue fictif, puis les exécute sur une grille : la position finale dit si la traduction a gardé le sens.

- **MVP** : Lexique bilingue fictif ; quarante consignes ; deux stratégies : traduction directe, traduction avec lexique imposé ; interpréteur de consignes sur grille.
- **Réussite** : Position finale correcte, axes inversés, commandes ambiguës signalées. Les scores de ressemblance au texte de référence sont rapportés à côté, pour montrer ce qu'ils ne voient pas.
- **Extensions** : Aller-retour par une troisième langue ; consignes relatives à un repère ; écriture d'une consigne robuste dès le départ.
- **Faisabilité** : API texte ou modèle local ; budget cible inférieur à 3 €. Plan B : traductions figées, interpréteur local.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Décodage contraint](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03c_Constrained_Decoding_Python.ipynb)

**Références** : [BLEU](https://aclanthology.org/P02-1040/) · [COMET](https://arxiv.org/abs/2009.09025) · [Décodage à contraintes lexicales](https://arxiv.org/abs/1804.06609)

## Édition, compression et couverture

<a id="fiche-p1"></a>

### P1 — Publier uniquement les changements utiles

**Difficulté : 3/5** · Mots-clés : `notes de version`, `diff`, `classification`, `précision`

Entre deux versions d'un règlement, certaines lignes bougent sans rien changer et une seule virgule peut changer un droit. Le projet génère des notes de version et mesure si elles distinguent le renommage sans effet du changement réel.

- **MVP** : Quinze paires de versions annotées ; deux stratégies : résumé des deux versions, verbalisation d'un diff structuré ; classement de chaque changement.
- **Réussite** : Précision et rappel sur trois classes : renommage sans effet, changement réel, règle inchangée. Changements réels passés sous silence comptés à part.
- **Extensions** : Format Keep a Changelog ; changements qui cassent la compatibilité ; notes pour deux publics.
- **Faisabilité** : Python avec difflib ; budget cible inférieur à 3 €. Plan B : notes figées, évaluation locale.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Évaluer un texte généré](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/22_Evaluating_Generated_Text.ipynb)

**Références** : [Keep a Changelog](https://keepachangelog.com/) · [Semantic Versioning](https://semver.org/) · [Python — difflib](https://docs.python.org/3/library/difflib.html)

<a id="fiche-p2"></a>

### P2 — Compression : apprendre une recette, certifier son inverse

**Difficulté : 4/5** · Mots-clés : `compression`, `recette`, `neuro-symbolique`, `sans perte` · hybride CoursIA

Devant un fichier, un LLM propose une recette : une suite de transformations choisies dans une liste autorisée, jamais du code libre. Le décodeur applique l'inverse sans consulter le modèle. Le verrou est comptable : la recette, le dictionnaire et le résidu comptent dans la taille finale, et toute recette qui ne reconstruit pas le fichier octet pour octet est rejetée.

- **MVP** : Jeu de primitives inversibles ; recettes proposées par le modèle ; décodeur indépendant ; comparaison à un codec fixe et à une recherche exhaustive à petit budget, sur textes, enregistrements structurés et octets aléatoires.
- **Réussite** : Taux de reconstruction exacte, octets nets par famille de fichiers, temps de choix et de décodage. Découpage par famille de fichiers, pas par fragments d'un même fichier. Cas où la recette coûte plus cher que les données isolés.
- **Extensions** : Recette apprise par famille ; primitives ajoutées par l'équipe ; frontière de Pareto taille contre temps.
- **Faisabilité** : Python sur CPU ; budget cible inférieur à 8 €. Plan B : recettes figées, décodeur et mesures exécutables sans réseau.

**CoursIA** : [Recette neuro-symbolique](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Compression/Compression-05b-NeuroSymbolic-Recipe-Python.ipynb) · [Triage par LLM](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Compression/Compression-07-Triage-LLM-Operations-Reelles-Python.ipynb) · [Codecs et Pareto](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Compression/Compression-04b-CodecsSOTA-Pareto-Python.ipynb)

**Références** : [Language Modeling Is Compression](https://arxiv.org/abs/2309.10668) · [Zstandard](https://meta.github.io/zstd/) · [Data Compression Explained](https://mattmahoney.net/dc/dce.html)

<a id="fiche-p3"></a>

### P3 — Générer un index de renvois qui reste valide

**Difficulté : 3/5** · Mots-clés : `renvois`, `liens`, `recherche`, `maintenance`

Dans une documentation, un renvoi peut rester cliquable et pointer vers le mauvais passage après une réorganisation. Le projet déplace et scinde des sections, puis fait réparer les renvois : par titre, ou par contenu.

- **MVP** : Trente notices courtes avec renvois croisés ; transformations contrôlées (déplacement, scission, renommage) ; deux stratégies de réparation ; vérité terrain fixée avant les transformations.
- **Réussite** : Liens valides qui pointent vers le mauvais passage, liens cassés, réparations correctes. Un lien qui répond n'est pas compté comme juste.
- **Extensions** : Ancres stables générées ; détection des renvois devenus inutiles ; documentation réelle sous licence libre.
- **Faisabilité** : BM25 ou embeddings locaux ; budget cible inférieur à 5 €. Plan B : réparations figées, vérification locale.

**CoursIA** : [RAG moderne](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/05_RAG_Modern.ipynb) · [Recherche d'information TF-IDF et BM25](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/NLP/06-Recherche-Information-TFIDF-BM25.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [W3C — Cool URIs don't change](https://www.w3.org/Provider/Style/URI) · [Dense Passage Retrieval](https://arxiv.org/abs/2004.04906) · [Sphinx — Cross-references](https://www.sphinx-doc.org/en/master/usage/referencing.html)

<a id="fiche-p4"></a>

### P4 — Construire des exemples qui couvrent une règle

**Difficulté : 3/5** · Mots-clés : `tests`, `grammaire`, `couverture`, `cas limites`

Pour tester un analyseur de dates, il faut des exemples qui passent par toutes ses branches. Un modèle en propose volontiers de très semblables. Le projet compare ses exemples à un tirage aléatoire, à budget égal, en mesurant la couverture réelle du code.

- **MVP** : Grammaire de dates fictive et son analyseur ; exemples générés par le modèle ; tirage aléatoire de chaînes acceptables ; mesure de couverture des branches.
- **Réussite** : Branches couvertes, cas aux frontières atteints, chaînes valides rejetées par erreur, à nombre d'exemples égal.
- **Extensions** : Exemples invalides ciblés ; génération guidée par la couverture manquante ; seconde grammaire jamais vue.
- **Faisabilité** : Python avec coverage.py ; budget cible inférieur à 3 €. Plan B : exemples figés, mesure locale.

**CoursIA** : [Décodage contraint](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03c_Constrained_Decoding_Python.ipynb) · [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Grammaires et analyse CYK](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/NLP/04_PCFG_CYK_Parsing.ipynb)

**Références** : [The Fuzzing Book](https://www.fuzzingbook.org/) · [Coverage.py](https://coverage.readthedocs.io/) · [Hypothesis](https://hypothesis.readthedocs.io/)

<a id="fiche-p5"></a>

### P5 — Fusionner deux corrections éditoriales

**Difficulté : 4/5** · Mots-clés : `fusion`, `conflits`, `édition`, `contraintes`

Deux relecteurs corrigent le même paragraphe chacun de leur côté. Fusionner à la main est fastidieux ; fusionner par modèle peut effacer une correction en silence. Le projet mesure ce qui est conservé des deux côtés et si les vrais conflits sont signalés.

- **MVP** : Vingt triplets : texte d'origine et deux corrections indépendantes ; deux stratégies : fusion textuelle à trois voies, génération guidée par la liste des corrections à conserver ; vérificateur de présence de chaque correction.
- **Réussite** : Corrections conservées de chaque côté, conflits réels signalés, conflits inventés, modifications que personne n'a demandées.
- **Extensions** : Trois relecteurs ; corrections de fond contre corrections de forme ; restitution sous forme de suivi des modifications.
- **Faisabilité** : Python avec difflib ; budget cible inférieur à 3 €. Plan B : fusions figées, vérificateur local.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Évaluer un texte généré](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/22_Evaluating_Generated_Text.ipynb)

**Références** : [A Formal Investigation of Diff3](https://doi.org/10.1007/978-3-540-77050-3_40) · [MergeBERT](https://arxiv.org/abs/2109.00084) · [Git — git-merge](https://git-scm.com/docs/git-merge)

<a id="fiche-p6"></a>

### P6 — Prédire, c'est compresser : un modèle de langue comme codec

**Difficulté : 4/5** · Mots-clés : `compression`, `modèle de langue`, `codage entropique`, `mesure` · hybride CoursIA

Un modèle qui prédit bien le prochain symbole permet de le coder en peu de bits. Le projet branche un petit modèle de langue sur un codeur entropique et mesure le résultat honnêtement : la taille du modèle fait partie de la facture, et le décodeur doit retrouver le texte exact.

- **MVP** : Codeur entropique branché sur trois prédicteurs : n-grammes, petit modèle local, modèle plus gros ; décodage vérifié octet pour octet ; comparaison à gzip et zstd.
- **Réussite** : Bits par caractère, taux de reconstruction exacte, temps de codage, taille totale modèle compris. Textes de test hors des données connues du modèle autant qu'on peut l'établir.
- **Extensions** : Textes dans plusieurs langues ; effet de la quantification du modèle ; données non textuelles.
- **Faisabilité** : Petit modèle local sur CPU ou GPU modeste ; budget nul possible. Plan B : probabilités précalculées et codeur local.

**CoursIA** : [Compression par apprentissage](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Compression/Compression-05-MLCompression-Python.ipynb) · [Codage ANS](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Compression/Compression-04-ANS-Python.ipynb) · [N-grammes et modèles de langue](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/NLP/02_NGrammes_Modeles_De_Langue.ipynb)

**Références** : [Language Modeling Is Compression](https://arxiv.org/abs/2309.10668) · [LLMZip](https://arxiv.org/abs/2306.04050) · [Asymmetric Numeral Systems](https://arxiv.org/abs/1311.2540) · [Hutter Prize](http://prize.hutter1.net/)

<a id="fiche-p7"></a>

### P7 — Triage de compression orchestré par Semantic Kernel

**Difficulté : 4/5** · Mots-clés : `semantic kernel`, `orchestration`, `compression`, `outils` · hybride CoursIA

Devant un lot de fichiers hétérogènes, un agent choisit pour chacun le codec et ses réglages en appelant de vrais outils. Le projet mesure ce que l'agent ajoute par rapport à une règle simple fondée sur l'extension, et ce qu'il coûte en temps et en tokens.

- **MVP** : Plugins Semantic Kernel pour sonder un fichier et lancer un codec ; lot de fichiers de familles variées ; trois politiques : règle par extension, essai de tous les codecs, agent.
- **Réussite** : Octets économisés, temps total, tokens consommés, décisions de l'agent qui battent la règle. Reconstruction exacte obligatoire pour chaque fichier.
- **Extensions** : Budget de temps imposé ; apprentissage à partir des décisions passées ; fichiers trompeurs (extension fausse).
- **Faisabilité** : Python ou .NET ; codecs libres ; budget cible inférieur à 8 €. Plan B : décisions de l'agent figées, mesures rejouées localement.

**CoursIA** : [Triage par LLM avec Semantic Kernel](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Compression/Compression-07b-Triage-LLM-Semantic-Kernel-Python.ipynb) · [Codecs et Pareto](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Compression/Compression-04b-CodecsSOTA-Pareto-Python.ipynb) · [Plugins Semantic Kernel](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/18_Semantic_Kernel_Plugins.ipynb)

**Références** : [Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/overview/) · [Zstandard](https://meta.github.io/zstd/) · [RFC 1951 — DEFLATE](https://www.rfc-editor.org/rfc/rfc1951) · [Large Text Compression Benchmark](https://mattmahoney.net/dc/text.html)

<a id="fiche-p8"></a>

### P8 — Tests combinatoires : couvrir toutes les paires

**Difficulté : 4/5** · Mots-clés : `tests`, `tableaux couvrants`, `couverture`, `génération` · hybride CoursIA

Une application à dix options ne peut pas être testée dans toutes ses combinaisons, mais la plupart des défauts apparaissent dès que deux options se rencontrent. Le projet compare des plans de test écrits par un modèle à un tableau couvrant calculé, puis fait rédiger par le modèle les scénarios lisibles correspondants.

- **MVP** : Description d'une application fictive et de ses options ; plan de test du modèle ; tableau couvrant calculé ; audit de la couverture des paires ; scénarios rédigés depuis le tableau.
- **Réussite** : Paires couvertes à nombre de tests égal, défauts injectés retrouvés, scénarios rédigés qui correspondent réellement à la ligne du tableau.
- **Extensions** : Couverture des triplets ; contraintes entre options ; priorisation par risque.
- **Faisabilité** : Python sur CPU ; budget cible inférieur à 5 €. Plan B : plans du modèle figés, audit local.

**CoursIA** : [Tableaux couvrants](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part5-Frontieres/Frontieres-05-CoveringArrays-Guarantee-Audit-Python.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb)

**Références** : [NIST — Combinatorial Testing](https://csrc.nist.gov/projects/automated-combinatorial-testing-for-software) · [Pairwise Testing](https://www.pairwise.org/) · [Hypothesis](https://hypothesis.readthedocs.io/)

## Jeux, récits et choix collectifs

<a id="fiche-q1"></a>

### Q1 — Créer un récit dont le lecteur choisit le chemin

**Difficulté : 4/5** · Mots-clés : `récit interactif`, `automate`, `cohérence`, `énumération`

Un récit à embranchements est un graphe : chaque choix change ce que le héros possède et sait. Un modèle qui écrit librement fait utiliser une clé avant qu'elle soit trouvée. Le projet fait rédiger chaque passage depuis un état explicite et vérifie tous les chemins courts.

- **MVP** : Automate de personnages et d'objets ; deux stratégies : génération libre du récit entier, rédaction passage par passage depuis l'état ; export jouable dans un format de fiction interactive.
- **Réussite** : Sur tous les chemins jusqu'à une longueur fixée : objets utilisés avant d'être acquis, fins inaccessibles, culs-de-sac. Trois chemins relus en aveugle pour la qualité du récit.
- **Extensions** : Illustration par passage ; fin cachée atteignable par un seul chemin ; personnage non joueur avec mémoire.
- **Faisabilité** : API texte ou modèle local ; budget cible inférieur à 8 €. Plan B : passages figés, vérificateur de chemins local.

**CoursIA** : [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Espace d'états](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/Planners/01-Foundation/Planners-03-State-Space-Python.ipynb)

**Références** : [Twine](https://twinery.org/) · [Ink](https://www.inklestudios.com/ink/) · [Narrative Planning: Balancing Plot and Character](https://doi.org/10.1613/jair.2989)

<a id="fiche-q2"></a>

### Q2 — Contrepoint : du solveur au rendu audio génératif

**Difficulté : 4/5** · Mots-clés : `musique`, `conduite de voix`, `rendu audio`, `écoute aveugle` · hybride CoursIA

Un solveur écrit deux conduites de voix sur la même basse : l'une respecte les règles du contrepoint, l'autre contient un croisement de voix volontaire. Chaque partition est rendue par un synthétiseur puis par un modèle génératif. Le verrou est de séparer deux jugements : la partition est-elle correcte, et le rendu lui est-il fidèle ?

- **MVP** : Deux partitions par basse ; tempo et tonalité fixés ; rendu au synthétiseur et rendu génératif ; comparaison des classes de hauteurs attendues et du chromagramme mesuré.
- **Réussite** : Matrice des erreurs partition contre rendu, écoute aveugle sur des phrases nouvelles, et au moins un cas documenté où le timbre masque une faute d'écriture.
- **Extensions** : Quatre voix ; styles de rendu ; détection automatique de la faute depuis l'audio seul.
- **Faisabilité** : Solveur sur CPU ; rendu génératif sur GPU modeste ou par API ; budget cible inférieur à 10 €. Plan B : audios figés, analyse locale.

**CoursIA** : [Conduite de voix](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-21-VoiceLeading-Python.ipynb) · [Rendu GenAI de la conduite de voix](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/04-Applications/04-14-VoiceLeading-Rendu-GenAI.ipynb) · [MusicGen](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/02-Advanced/02-3-MusicGen-Generation.ipynb)

**Références** : [music21](https://www.music21.org/music21docs/) · [librosa](https://librosa.org/doc/latest/index.html) · [MusicGen](https://arxiv.org/abs/2306.05284)

<a id="fiche-q3"></a>

### Q3 — Expliquer un désaccord entre scrutins avec un certificat de calcul

**Difficulté : 4/5** · Mots-clés : `choix social`, `scrutins`, `trace typée`, `certificat` · hybride CoursIA

Avec les mêmes bulletins, deux modes de scrutin peuvent élire deux candidats différents. Le modèle doit expliquer pourquoi en citant les étapes du dépouillement ; chaque étape citée est recalculée indépendamment. Une explication convaincante avec un total faux est un échec.

- **MVP** : Générateur de profils fictifs où deux scrutins divergent ; deux stratégies : explication libre, rédaction depuis une trace typée du dépouillement ; vérificateur de chaque total cité.
- **Réussite** : Exactitude des totaux, cohérence quand on permute les noms ou qu'on duplique tous les bulletins, comportement sur les égalités et les cycles.
- **Extensions** : Troisième scrutin ; profil minimal qui produit le désaccord ; explication pour un public de collégiens.
- **Faisabilité** : Python sur CPU ; budget cible inférieur à 5 €. Plan B : explications figées, dépouillement et vérification locaux.

**CoursIA** : [Méthodes de vote](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GameTheory/SocialChoice/ChoixSocial-03-Voting-Methods-Python.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Stanford Encyclopedia — Voting Methods](https://plato.stanford.edu/entries/voting-methods/) · [pref_voting](https://pref-voting.readthedocs.io/) · [Stanford Encyclopedia — Arrow's Theorem](https://plato.stanford.edu/entries/arrows-theorem/)

<a id="fiche-q4"></a>

### Q4 — Faire deviner une notion sans la nommer

**Difficulté : 3/5** · Mots-clés : `jeu de mots`, `pragmatique`, `embeddings`, `mots interdits` · hybride CoursIA

Faire deviner « volcan » sans dire « lave », « éruption » ni « montagne » : un bon indice écarte les voisins proches sans utiliser les mots interdits. Le projet mesure l'indice par ce qu'il élimine, puis par ce que des lecteurs devinent réellement.

- **MVP** : Vocabulaire fermé avec voisins sémantiques ; liste de mots interdits par notion ; deux stratégies : premier indice, indice révisé après un test de devinette.
- **Réussite** : Mots interdits utilisés, nombre de candidats encore compatibles avec l'indice, taux de résolution par des lecteurs indépendants.
- **Extensions** : Indice pour deux notions à la fois ; modèle de locuteur pragmatique ; devineur artificiel comparé aux lecteurs.
- **Faisabilité** : Embeddings locaux sur CPU ; budget cible inférieur à 3 €. Plan B : indices figés, mesures locales.

**CoursIA** : [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Word2Vec](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/NLP/08-Word2Vec-CBOW-SkipGram.ipynb) · [Rational Speech Acts](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Probas/Applications/Pyro_RSA_Hyperbole.ipynb)

**Références** : [Word2Vec](https://arxiv.org/abs/1301.3781) · [Playing Codenames with Language Graphs and Word Embeddings](https://arxiv.org/abs/2105.05885) · [Probabilistic Language Understanding](https://www.problang.org/)

<a id="fiche-q5"></a>

### Q5 — Expliquer deux résultats de vote contradictoires

**Difficulté : 3/5** · Mots-clés : `vote`, `critères`, `neutralité`, `explication` · hybride CoursIA

Quand deux scrutins se contredisent, l'explication utile nomme la propriété en jeu : l'un garantit le vainqueur de Condorcet, l'autre non. Le projet demande cette explication et teste sa neutralité : elle ne doit pas changer quand on échange les noms des candidats.

- **MVP** : Profils fictifs de préférences ; calcul de deux méthodes ; deux stratégies : explication directe, rédaction après calcul vérifié ; test de permutation des noms.
- **Réussite** : Totaux et comparaisons cités corrects, propriété correctement nommée, explications équivalentes après permutation des noms.
- **Extensions** : Noms connotés contre noms neutres ; classement de compromis de Kemeny ; cas sans vainqueur de Condorcet.
- **Faisabilité** : Python sur CPU ; budget cible inférieur à 3 €. Plan B : explications figées, calcul local.

**CoursIA** : [Kemeny, paires classées, Dodgson](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GameTheory/SocialChoice/ChoixSocial-08-Kemeny-RankedPairs-Dodgson-Python.ipynb) · [Méthodes de vote](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GameTheory/SocialChoice/ChoixSocial-03-Voting-Methods-Python.ipynb) · [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb)

**Références** : [Stanford Encyclopedia — Voting Methods](https://plato.stanford.edu/entries/voting-methods/) · [Stanford Encyclopedia — Social Choice Theory](https://plato.stanford.edu/entries/social-choice/) · [pref_voting](https://pref-voting.readthedocs.io/)

<a id="fiche-q6"></a>

### Q6 — Un LLM joue-t-il l'équilibre ?

**Difficulté : 4/5** · Mots-clés : `théorie des jeux`, `équilibre`, `coopération`, `agents` · hybride CoursIA

Dans un dilemme du prisonnier répété ou un jeu de coordination, la théorie dit ce qu'un joueur rationnel devrait faire. Un LLM joue autrement : il coopère trop, punit trop longtemps, ou change d'avis selon la façon dont le jeu est raconté. Le projet mesure cet écart et sa sensibilité à l'habillage.

- **MVP** : Trois jeux à deux joueurs ; équilibres calculés ; parties répétées entre le modèle et des stratégies fixes ; même jeu présenté sous deux habillages.
- **Réussite** : Écart à l'équilibre, taux de coopération, exploitabilité par une stratégie simple, variation due au seul habillage.
- **Extensions** : Population de modèles ; communication avant de jouer ; jeu à ressource commune.
- **Faisabilité** : API texte ou modèle local ; parties courtes ; budget cible inférieur à 10 €. Plan B : parties enregistrées, analyse locale.

**CoursIA** : [Joueurs LLM](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GameTheory/GameTheory-16d-LLM-Players-Othman-Sandholm-Python.ipynb) · [Coopération entre LLM](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GameTheory/GameTheory-16h-Cooperation-LLM-Python.ipynb) · [Joueur LLM en dynamique](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GameTheory/Dynamics/Dynamics-10-Joueur-LLM-Python.ipynb)

**Références** : [Playing repeated games with Large Language Models](https://arxiv.org/abs/2305.16867) · [Cooperate or Collapse](https://arxiv.org/abs/2404.16698) · [Nashpy](https://nashpy.readthedocs.io/) · [OpenSpiel](https://arxiv.org/abs/1908.09453)

<a id="fiche-q7"></a>

### Q7 — Wordle : le modèle joue-t-il mieux que l'entropie ?

**Difficulté : 3/5** · Mots-clés : `wordle`, `entropie`, `stratégie`, `jeu` · hybride CoursIA

Au Wordle, le meilleur coup est celui qui réduit le plus l'ensemble des mots possibles. Un solveur le calcule ; un LLM joue à l'intuition et propose parfois un mot déjà exclu par les indices. Le projet compare les deux et teste un mode hybride où le modèle choisit parmi les coups valides.

- **MVP** : Lexique fermé ; solveur par entropie ; trois joueurs : LLM seul, LLM avec la liste des mots encore possibles, solveur ; parties sur un lot de mots tenus à part.
- **Réussite** : Nombre moyen de coups, coups incompatibles avec les indices déjà reçus, parties perdues, information gagnée par coup.
- **Extensions** : Mode difficile ; explication du coup en français ; variante à six lettres.
- **Faisabilité** : Python sur CPU ; budget cible inférieur à 5 €. Plan B : parties du modèle enregistrées, solveur local.

**CoursIA** : [Wordle](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-07-Wordle-Python.ipynb) · [Prompt engineering](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Wordle is NP-hard](https://arxiv.org/abs/2203.16713) · [A Mathematical Theory of Communication](https://doi.org/10.1002/j.1538-7305.1948.tb01338.x) · [Python — collections.Counter](https://docs.python.org/3/library/collections.html#collections.Counter)

<a id="fiche-q8"></a>

### Q8 — Commenter une partie de Puissance 4 sans se tromper de coup

**Difficulté : 3/5** · Mots-clés : `jeu`, `commentaire`, `minimax`, `synthèse vocale` · hybride CoursIA

Un commentateur sportif dit ce qui vient de se passer et ce qui menace. Sur une partie de Puissance 4, un moteur de recherche connaît la valeur exacte de chaque coup. Le modèle rédige le commentaire à partir de cette analyse ; on vérifie que ce qu'il annonce (menace, coup forcé, erreur) est vrai sur le plateau.

- **MVP** : Moteur minimax avec élagage ; analyse typée de chaque coup ; deux stratégies : commentaire depuis le plateau brut, commentaire depuis l'analyse ; lecture par synthèse vocale.
- **Réussite** : Affirmations vérifiables justes (menace réelle, coup gagnant, erreur), affirmations inventées, intérêt du commentaire noté en aveugle.
- **Extensions** : Commentaire en direct sous contrainte de temps ; niveau débutant ou expert ; autre jeu.
- **Faisabilité** : Moteur sur CPU ; synthèse vocale locale ; budget cible inférieur à 5 €. Plan B : commentaires figés, vérification locale.

**CoursIA** : [Puissance 4 et recherche adverse](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-14-ConnectFour-Adversarial-Python.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Synthèse vocale locale](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-5-Kokoro-TTS-Local.ipynb)

**Références** : [John's Connect Four Playground](https://tromp.github.io/c4/c4.html) · [AlphaZero](https://arxiv.org/abs/1712.01815) · [Learning to Generate Move-by-Move Commentary for Chess Games](https://aclanthology.org/P18-1154/)

## Preuve, connaissance et argumentation

<a id="fiche-r1"></a>

### R1 — Preuves Lean : le modèle propose, le noyau vérifie

**Difficulté : 5/5** · Mots-clés : `lean`, `preuve formelle`, `boucle de réparation`, `vérification` · hybride CoursIA

Une preuve écrite par un LLM a l'air juste jusqu'à ce qu'un assistant de preuve la refuse. Lean ne laisse rien passer : la preuve compile ou non. Le projet mesure ce que rapporte une boucle où le modèle lit le message d'erreur et corrige, par rapport à un seul essai.

- **MVP** : Trente énoncés élémentaires (arithmétique, logique, listes) ; trois stratégies : un essai, plusieurs essais indépendants, boucle de réparation avec le message d'erreur ; compilation Lean comme seul juge.
- **Réussite** : Énoncés prouvés à budget d'appels égal, nombre de tours nécessaires, preuves obtenues en affaiblissant l'énoncé (comptées comme échecs).
- **Extensions** : Recherche de lemmes dans la bibliothèque ; esquisse en français puis formalisation ; énoncés d'un niveau supérieur.
- **Faisabilité** : Lean 4 sur CPU ; installation à prévoir dès la première semaine ; budget cible inférieur à 10 €. Plan B : tentatives du modèle figées, compilation locale.

**CoursIA** : [Lean et LLM](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/Lean/Lean-07-LLM-Integration-Lean-Python.ipynb) · [Preuve agentique](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/Lean/Lean-08-Agentic-Proving-Python.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb)

**Références** : [LeanDojo](https://arxiv.org/abs/2306.15626) · [miniF2F](https://arxiv.org/abs/2109.00110) · [Draft, Sketch, and Prove](https://arxiv.org/abs/2210.12283) · [Lean](https://lean-lang.org/)

<a id="fiche-r2"></a>

### R2 — Graphe ou passages : quelle question demande quoi ?

**Difficulté : 4/5** · Mots-clés : `graphe de connaissances`, `sparql`, `rag`, `multi-sauts` · hybride CoursIA

Une question comme « quels auteurs ont travaillé avec un lauréat né la même année qu'eux ? » traverse plusieurs faits ; un RAG par passages s'y perd, une requête sur un graphe y répond exactement. Le projet construit les deux sur le même corpus et cherche la frontière : pour quelles questions le graphe vaut-il son coût de construction ?

- **MVP** : Petit corpus et son graphe RDF ; quarante questions classées par nombre de sauts ; trois stratégies : RAG par passages, requête SPARQL générée, combinaison des deux.
- **Réussite** : Exactitude par nombre de sauts, requêtes générées invalides ou vides, coût de construction du graphe rapporté au gain.
- **Extensions** : Graphe extrait automatiquement du texte ; questions d'agrégation ; réponses avec chemin de preuve affiché.
- **Faisabilité** : rdflib et embeddings locaux sur CPU ; budget cible inférieur à 8 €. Plan B : requêtes générées figées, exécution locale.

**CoursIA** : [GraphRAG](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SemanticWeb/SW-12-GraphRAG-Python.ipynb) · [SPARQL](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SemanticWeb/SW-04-SPARQL-Python.ipynb) · [RAG moderne](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/05_RAG_Modern.ipynb)

**Références** : [From Local to Global: A Graph RAG Approach](https://arxiv.org/abs/2404.16130) · [W3C — SPARQL 1.1](https://www.w3.org/TR/sparql11-query/) · [HotpotQA](https://arxiv.org/abs/1809.09600)

<a id="fiche-r3"></a>

### R3 — Du texte au graphe de connaissances validé

**Difficulté : 3/5** · Mots-clés : `rdf`, `shacl`, `extraction`, `validation` · hybride CoursIA

Extraire des faits d'un texte vers un graphe est facile à faire mal : une date dans le champ du lieu, une personne sans nom. SHACL décrit la forme que le graphe doit avoir et refuse le reste. Le projet mesure ce que cette validation attrape, et ce qu'elle laisse passer : un fait bien formé peut rester faux.

- **MVP** : Vingt notices fictives annotées ; extraction vers RDF ; formes SHACL écrites par l'équipe ; boucle de correction à partir du rapport de validation.
- **Réussite** : Triplets exacts, violations de forme avant et après correction, faits bien formés mais faux que la validation ne voit pas.
- **Extensions** : Formes SHACL proposées par le modèle ; alignement sur un vocabulaire public ; fusion de deux notices sur la même entité.
- **Faisabilité** : rdflib et pySHACL sur CPU ; budget cible inférieur à 5 €. Plan B : extractions figées, validation locale.

**CoursIA** : [SHACL](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SemanticWeb/SW-08-SHACL-Python.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [SPARQL](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SemanticWeb/SW-04-SPARQL-Python.ipynb)

**Références** : [W3C — SHACL](https://www.w3.org/TR/shacl/) · [W3C — RDF 1.1 Primer](https://www.w3.org/TR/rdf11-primer/) · [pySHACL](https://github.com/RDFLib/pySHACL) · [LLMs for Knowledge Graph Construction and Reasoning](https://arxiv.org/abs/2305.13168)

<a id="fiche-r4"></a>

### R4 — Qui a raison ? Du débat au graphe d'arguments

**Difficulté : 4/5** · Mots-clés : `argumentation`, `dung`, `extraction`, `sémantiques` · hybride CoursIA

Dans un débat, chaque argument en attaque d'autres. Une fois le graphe des attaques posé, la théorie de l'argumentation calcule quels arguments tiennent ensemble. Le modèle extrait le graphe d'un débat écrit ; un solveur calcule les arguments acceptables. Le verrou est la sensibilité : une seule attaque mal extraite peut renverser la conclusion.

- **MVP** : Quinze débats fictifs annotés ; extraction des arguments et des attaques dans un schéma typé ; calcul des extensions par un solveur ; restitution en français de ce qui tient et pourquoi.
- **Réussite** : Attaques correctement extraites, extensions identiques à la référence, conclusions renversées par une seule erreur d'extraction.
- **Extensions** : Repérage des sophismes ; arguments pondérés ; débat à trois camps.
- **Faisabilité** : Solveur sur CPU ; débats fictifs sur des sujets non sensibles ; budget cible inférieur à 8 €. Plan B : extractions figées, solveur local.

**CoursIA** : [Cadres de Dung](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/ArgumentAnalysis/Argumentation-03-Dung-AF-Semantics-Python.ipynb) · [Dialogues entre agents](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/Tweety/Tweety-08-Agent-Dialogues-Python.ipynb) · [Taxonomie des sophismes](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FallacyDetection/01_taxonomy_intro.ipynb)

**Références** : [On the acceptability of arguments](https://doi.org/10.1016/0004-3702(94)00041-X) · [Argument Mining: A Survey](https://doi.org/10.1162/coli_a_00364) · [TweetyProject](https://tweetyproject.org/) · [Logical Fallacy Detection](https://arxiv.org/abs/2202.13758)

<a id="fiche-r5"></a>

### R5 — Apprendre une règle depuis des exemples : LLM contre logique inductive

**Difficulté : 4/5** · Mots-clés : `induction`, `ilp`, `règles`, `généralisation` · hybride CoursIA

À partir de quelques exemples de liens de parenté, trouver la règle « grand-parent ». La programmation logique inductive la trouve et peut la prouver cohérente avec les exemples ; un LLM propose une règle en langage naturel, souvent juste, parfois trop large. Le projet compare les deux quand les exemples deviennent rares ou bruités.

- **MVP** : Six concepts relationnels ; exemples positifs et négatifs ; trois apprenants : système de logique inductive, LLM seul, LLM dont chaque règle est testée sur les exemples avant d'être acceptée.
- **Réussite** : Exactitude sur des exemples jamais vus, règles trop générales, tenue face à des exemples mal étiquetés. Noms de relations inventés pour écarter la mémorisation.
- **Extensions** : Règles récursives ; invention de prédicats ; explication de la règle apprise.
- **Faisabilité** : Prolog ou Python sur CPU ; budget cible inférieur à 5 €. Plan B : hypothèses du modèle figées, test local.

**CoursIA** : [LLM et apprentissage symbolique](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SymbolicLearning/SL-9-LLM-SymbolicLearning.ipynb) · [Programmation logique inductive](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SymbolicLearning/SL-4-InductiveLogicProgramming.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Hypothesis Search](https://arxiv.org/abs/2309.05660) · [Learning programs by learning from failures](https://arxiv.org/abs/2005.02259) · [Inductive logic programming at 30](https://arxiv.org/abs/2102.10556)

<a id="fiche-r6"></a>

### R6 — Contrats intelligents : audit par LLM, preuve par fuzzing

**Difficulté : 4/5** · Mots-clés : `smart contracts`, `audit`, `fuzzing`, `invariants` · hybride CoursIA

Un LLM lit un contrat Solidity et signale des failles ; beaucoup sont fausses, quelques-unes sont réelles. Le projet lui demande, pour chaque faille annoncée, l'invariant qu'elle viole, puis laisse un outil de fuzzing chercher la transaction qui le casse. Une alerte ne compte que si elle est reproduite.

- **MVP** : Douze contrats courts dont huit portent une faille connue ; alertes du modèle avec invariant associé ; campagne de fuzzing par invariant ; comparaison à un analyseur statique.
- **Réussite** : Failles réelles retrouvées, fausses alertes, alertes confirmées par une transaction, failles manquées par le modèle et trouvées par l'outil.
- **Extensions** : Correctif proposé et re-testé ; contrats plus longs ; invariants écrits sans l'aide du modèle.
- **Faisabilité** : Foundry sur CPU, réseau local de test uniquement, aucun déploiement réel ; budget cible inférieur à 8 €. Plan B : alertes figées, fuzzing local.

**CoursIA** : [Solidity assisté par LLM](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SmartContracts/02-Solidity-Advanced/SC-11-LLM-Assisted-Python.ipynb) · [Fuzzing et invariants](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SmartContracts/03-Foundry-Testing/SC-13-Fuzz-Invariants-Python.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Solidity](https://docs.soliditylang.org/) · [Foundry Book](https://book.getfoundry.sh/) · [Slither](https://github.com/crytic/slither) · [Do you still need a manual smart contract audit?](https://arxiv.org/abs/2306.12338)

<a id="fiche-r7"></a>

### R7 — Retrouver une loi à partir de mesures

**Difficulté : 4/5** · Mots-clés : `régression symbolique`, `équations`, `découverte`, `extrapolation` · hybride CoursIA

Devant un tableau de mesures, trouver la formule qui les relie. La régression symbolique explore les formules par recherche ; un LLM en propose par analogie avec la physique qu'il connaît, ce qui l'aide et le trompe. Le projet compare les deux sur des lois déguisées, dont les variables ont été renommées.

- **MVP** : Dix lois avec données simulées et bruit ; trois méthodes : régression symbolique, LLM seul, LLM qui propose des formes ajustées ensuite numériquement ; variables renommées.
- **Réussite** : Formules exactes retrouvées, erreur hors de la plage d'entraînement, complexité de la formule, effet du renommage des variables.
- **Extensions** : Contrôle des unités ; lois inventées qui n'existent dans aucun manuel ; bruit croissant.
- **Faisabilité** : PySR ou recherche maison sur CPU ; budget cible inférieur à 8 €. Plan B : propositions du modèle figées, ajustement local.

**CoursIA** : [AI Feynman](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SymbolicLearning/SL-14-AIFeynman-Discover-Equations.ipynb) · [Code interpreter](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/07_Code_Interpreter.ipynb) · [LLM et apprentissage symbolique](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SymbolicLearning/SL-9-LLM-SymbolicLearning.ipynb)

**Références** : [AI Feynman](https://arxiv.org/abs/1905.11481) · [LLM-SR](https://arxiv.org/abs/2404.18400) · [PySR](https://arxiv.org/abs/2305.01582)

<a id="fiche-r8"></a>

### R8 — Un LLM peut-il servir d'oracle pour apprendre un automate ?

**Difficulté : 4/5** · Mots-clés : `automates`, `apprentissage actif`, `oracle`, `erreurs` · hybride CoursIA

L'algorithme L* apprend un automate en posant des questions : « ce mot est-il accepté ? ». Il suppose un professeur qui ne se trompe jamais. Le projet met un LLM à cette place, avec une règle décrite en français, et mesure ce que quelques réponses fausses font à l'automate appris.

- **MVP** : Huit langages réguliers décrits en français ; LLM comme oracle d'appartenance ; apprentissage par L* ; automate de référence pour mesurer l'écart.
- **Réussite** : Taux d'erreur de l'oracle, distance entre automate appris et référence, nombre de questions posées, effet d'un vote sur plusieurs réponses.
- **Extensions** : Oracle qui s'abstient ; description ambiguë ; apprentissage du comportement d'un petit assistant conversationnel.
- **Faisabilité** : AALpy sur CPU ; budget cible inférieur à 8 €, à borner par le nombre de questions. Plan B : réponses de l'oracle mises en cache, apprentissage local.

**CoursIA** : [Apprentissage actif d'automates](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SymbolicLearning/SL-10-ActiveAutomataLearning.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Décodage contraint](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03c_Constrained_Decoding_Python.ipynb)

**Références** : [Learning regular sets from queries and counterexamples](https://doi.org/10.1016/0890-5401(87)90052-6) · [AALpy](https://github.com/DES-Lab/AALpy) · [LearnLib](https://learnlib.de/)

## Décision, apprentissage par renforcement et marchés

<a id="fiche-s1"></a>

### S1 — Signaux de marché lus par un LLM : gain réel ou mémoire du futur ?

**Difficulté : 4/5** · Mots-clés : `finance`, `backtest`, `fuite temporelle`, `sentiment` · hybride CoursIA

Un LLM classe des titres de presse en bonnes ou mauvaises nouvelles et le backtest affiche un gain. Mais le modèle a peut-être lu la suite de l'histoire pendant son entraînement. Le projet construit le backtest, puis cherche cette fuite : mêmes titres avec noms d'entreprises masqués, et période postérieure à la date de coupure du modèle.

- **MVP** : Jeu public de titres datés ; signal par LLM et par modèle de sentiment classique ; backtest avec frais ; version anonymisée des titres.
- **Réussite** : Performance avant et après anonymisation, avant et après la date de coupure, comparaison à une stratégie passive. Aucun argent réel, aucun conseil d'investissement.
- **Extensions** : Agent à plusieurs rôles ; signaux combinés à des indicateurs de prix ; intervalle de confiance par rééchantillonnage.
- **Faisabilité** : Données publiques et backtest local ; budget cible inférieur à 10 €. Plan B : signaux figés, backtest rejoué sans réseau.

**CoursIA** : [Signaux de trading par LLM](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/QuantConnect/Python/QC-Py-26-LLM-Trading-Signals.ipynb) · [Agent de trading multi-LLM](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/QuantConnect/Python/QC-Py-44-Agent-Trading-Multi-LLM.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [FinBERT](https://arxiv.org/abs/1908.10063) · [Can ChatGPT Forecast Stock Price Movements?](https://arxiv.org/abs/2304.07619) · [QuantConnect — Documentation](https://www.quantconnect.com/docs/v2)

<a id="fiche-s2"></a>

### S2 — Séries temporelles synthétiques par diffusion : réalistes et utiles ?

**Difficulté : 4/5** · Mots-clés : `diffusion`, `séries temporelles`, `données synthétiques`, `évaluation` · hybride CoursIA

Les modèles de diffusion ne produisent pas que des images : ils peuvent générer des séries de prix ou de mesures. Une série synthétique peut paraître réaliste et ne servir à rien, ou recopier les données d'entraînement. Le projet évalue les deux risques sur un petit modèle.

- **MVP** : Petit modèle de diffusion sur des séries courtes ; comparaison à un rééchantillonnage par blocs ; trois mesures : statistiques, classifieur réel contre synthétique, modèle entraîné sur le synthétique et testé sur le réel.
- **Réussite** : Écart sur les statistiques usuelles, score du classifieur discriminant, performance en entraînant sur le synthétique, distance au plus proche voisin réel pour détecter la copie.
- **Extensions** : Génération conditionnée par un régime ; séries à plusieurs variables ; comparaison à un modèle antagoniste.
- **Faisabilité** : Entraînement court sur GPU modeste ou CPU pour des séries très courtes ; budget nul possible. Plan B : séries générées figées, évaluation locale.

**CoursIA** : [Séries synthétiques par diffusion](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/QuantConnect/Python/QC-Py-43-Diffusion-Series-Synthetiques.ipynb) · [Séries temporelles](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/ML/ML.Net/ML-05-TimeSeries-Python.ipynb) · [Séries temporelles classiques](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/ML/ML.Net/ML-05b-Series-Temporelles-Classiques-Python.ipynb)

**Références** : [DDPM](https://arxiv.org/abs/2006.11239) · [TimeGrad](https://arxiv.org/abs/2101.12072) · [Diffusion-TS](https://arxiv.org/abs/2403.01742) · [TimeGAN](https://papers.nips.cc/paper/2019/hash/c9efe5f26cd17ba6216bbe2a7d26d490-Abstract.html)

<a id="fiche-s3"></a>

### S3 — Une récompense rédigée par un LLM se fait-elle contourner ?

**Difficulté : 4/5** · Mots-clés : `apprentissage par renforcement`, `récompense`, `contournement`, `audit` · hybride CoursIA

Écrire la fonction de récompense d'un agent est délicat : l'agent optimise ce qui est écrit, pas ce qui était voulu. Un LLM peut rédiger cette fonction à partir d'une consigne en français. Le projet entraîne un agent avec, puis vérifie avec une mesure indépendante si la tâche est réellement accomplie.

- **MVP** : Deux environnements simples ; récompenses rédigées par le modèle depuis une consigne ; entraînement court ; mesure du but réel distincte de la récompense ; récompense écrite à la main comme référence.
- **Réussite** : Écart entre récompense obtenue et but réel atteint, cas de contournement décrits et rejoués, gain après une itération de correction.
- **Extensions** : Boucle d'amélioration automatique de la récompense ; curriculum ; détection du contournement par un second modèle.
- **Faisabilité** : Gymnasium et Stable-Baselines3 sur CPU ; budget cible inférieur à 5 €. Plan B : récompenses générées figées, entraînement local.

**CoursIA** : [Façonnage de récompense et curriculum](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/RL/RL-10-Reward-Shaping-Curriculum-Python.ipynb) · [Falsification de récompense](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/RL/RL-17-Reward-Tampering-Python.ipynb) · [Reward hacking](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/RL/PostTraining/RLPT-03-Reward-Hacking-Python.ipynb)

**Références** : [Eureka](https://arxiv.org/abs/2310.12931) · [Reward Tampering Problems and Solutions](https://arxiv.org/abs/1908.04734) · [Concrete Problems in AI Safety](https://arxiv.org/abs/1606.06565) · [Gymnasium](https://gymnasium.farama.org/)

<a id="fiche-s4"></a>

### S4 — Le LLM comme optimiseur d'hyperparamètres

**Difficulté : 3/5** · Mots-clés : `hyperparamètres`, `optimisation bayésienne`, `budget`, `comparaison` · hybride CoursIA

Régler un modèle, c'est chercher dans un espace de paramètres avec peu d'essais. Un LLM peut jouer l'optimiseur : il lit l'historique des essais et propose le suivant. Le projet le compare, à budget d'essais égal, à la recherche aléatoire et à l'optimisation bayésienne.

- **MVP** : Trois tâches d'apprentissage légères ; trois optimiseurs : aléatoire, Optuna, LLM qui lit l'historique ; même nombre d'essais et plusieurs graines pour chacun.
- **Réussite** : Meilleur score selon le nombre d'essais, variance entre graines, propositions hors de l'espace autorisé. Le jeu de test n'est jamais montré à l'optimiseur.
- **Extensions** : Départ à froid depuis la description de la tâche ; arrêt anticipé ; coût en tokens rapporté au temps de calcul gagné.
- **Faisabilité** : scikit-learn sur CPU ; budget cible inférieur à 5 €. Plan B : propositions du modèle figées, entraînements locaux.

**CoursIA** : [Réglage d'hyperparamètres](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-18-HyperparameterTuning-Python.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Optuna](https://arxiv.org/abs/1907.10902) · [Using Large Language Models for Hyperparameter Optimization](https://arxiv.org/abs/2312.04528) · [LLAMBO](https://arxiv.org/abs/2402.03921)

<a id="fiche-s5"></a>

### S5 — Choisir le bon solveur en lisant l'énoncé

**Difficulté : 4/5** · Mots-clés : `sélection d’algorithmes`, `portefeuille`, `solveurs`, `prédiction` · hybride CoursIA

Aucun solveur n'est le meilleur partout : selon l'instance, la recherche locale bat la programmation par contraintes ou l'inverse. La sélection d'algorithmes apprend à choisir à partir de caractéristiques de l'instance. Le projet compare un sélecteur classique à un LLM qui lit la description du problème.

- **MVP** : Deux familles de problèmes ; trois solveurs ; table des performances mesurées ; sélecteur appris sur caractéristiques contre choix du LLM ; instances de test tenues à part.
- **Réussite** : Temps total rapporté au meilleur solveur unique et au choix parfait, choix catastrophiques, stabilité du choix sous reformulation de la description.
- **Extensions** : Ordonnancement de plusieurs solveurs ; choix des paramètres ; justification du choix confrontée aux mesures.
- **Faisabilité** : Solveurs libres sur CPU ; limite de temps courte par instance ; budget cible inférieur à 5 €. Plan B : table de performances et choix figés.

**CoursIA** : [Sélection d'algorithmes](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part3-Cas-pratiques/App-22-AlgorithmSelection-Python.ipynb) · [Sélection d'algorithmes en métaheuristiques](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/Search/Part4-Metaheuristics/MGS-16-AlgorithmSelection.ipynb) · [Sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Algorithm Selection for Combinatorial Search Problems: A Survey](https://arxiv.org/abs/1210.7959) · [ASlib](https://arxiv.org/abs/1506.02465) · [SATzilla](https://arxiv.org/abs/1111.2249)

<a id="fiche-s6"></a>

### S6 — Planifier avant de coder : la boucle vaut-elle son coût ?

**Difficulté : 4/5** · Mots-clés : `agents`, `analyse de données`, `boucle planificateur-codeur`, `ablation` · hybride CoursIA

Un agent d'analyse de données enchaîne plan, code, exécution, vérification et recommence. Chaque étage coûte des tokens et du temps. À la différence de la fiche J2, la question n'est pas la fidélité du rapport, mais ce que chaque étage rapporte : on les retire un par un et on mesure.

- **MVP** : Trente questions sur des tables publiques avec réponse calculée à l'avance ; quatre variantes : code en un coup, plan puis code, ajout de la vérification, boucle complète ; exécution en bac à sable.
- **Réussite** : Réponses exactes, coût en tokens et en temps par bonne réponse, erreurs que la boucle corrige et erreurs qu'elle introduit.
- **Extensions** : Budget d'itérations appris ; questions à plusieurs tables ; critère d'arrêt fondé sur la confiance.
- **Faisabilité** : pandas en bac à sable sur CPU ; budget cible inférieur à 10 €. Plan B : traces d'exécution figées, mesures rejouées localement.

**CoursIA** : [Agent d'analyse de données](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/ML/DataScienceWithAgents/06-Data-Agents/Day3-Data-Agents/Labs/Lab7-Data-Analysis-Agent/Lab7-Data-Analysis-Agent.ipynb) · [Boucle planificateur-codeur](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/ML/DataScienceWithAgents/07-Agent-Orchestration/Day5-DS-Star/Lab11-Planner-Coder-Loop.ipynb) · [Code interpreter](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/07_Code_Interpreter.ipynb)

**Références** : [Data Interpreter](https://arxiv.org/abs/2402.18679) · [DS-1000](https://arxiv.org/abs/2211.11501) · [InfiAgent-DABench](https://arxiv.org/abs/2401.05507)

<a id="fiche-s7"></a>

### S7 — Recommander avec des identifiants sémantiques

**Difficulté : 4/5** · Mots-clés : `recommandation`, `identifiants sémantiques`, `génération`, `démarrage à froid` · hybride CoursIA

Un recommandeur classique donne à chaque film un numéro arbitraire. Une approche générative lui donne un code court dérivé de sa description : deux films proches partagent le début de leur code, et recommander revient à générer le code suivant. Le projet teste la promesse principale : mieux recommander un film nouveau, jamais vu à l'entraînement.

- **MVP** : Jeu MovieLens réduit ; identifiants sémantiques par quantification des embeddings de descriptions ; petit modèle séquentiel ; comparaison à un modèle à identifiants arbitraires et à la popularité.
- **Réussite** : Rappel dans les dix premiers sur les films connus et sur les films nouveaux, collisions de codes, codes générés qui ne correspondent à aucun film.
- **Extensions** : Longueur du code ; descriptions enrichies par un LLM ; diversité des recommandations.
- **Faisabilité** : Entraînement court sur CPU ou GPU modeste ; budget nul possible. Plan B : embeddings et codes précalculés, évaluation locale.

**CoursIA** : [Identifiants sémantiques](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/ML/ML.Net/ML-07b-SemanticIDs-Recommandation-Python.ipynb) · [Embeddings depuis zéro](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/03-Embeddings-From-Scratch.ipynb) · [Stockage vectoriel](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/05-Stockage-Vectoriel.ipynb)

**Références** : [TIGER](https://arxiv.org/abs/2305.05065) · [Differentiable Search Index](https://arxiv.org/abs/2202.06991) · [MovieLens](https://grouplens.org/datasets/movielens/)

## Sécurité et confiance des systèmes génératifs

<a id="fiche-t1"></a>

### T1 — Repérer un jailbreak à sa trajectoire, pas à son texte

**Difficulté : 5/5** · Mots-clés : `jailbreak`, `multi-tours`, `trajectoire`, `garde-fou`, `pré-enregistrement` · hybride CoursIA

Un jailbreak en plusieurs tours ne contient souvent aucune phrase interdite : il fait basculer le modèle, tour après tour, du refus vers l'acceptation. Une hypothèse de CoursIA propose de lire ce basculement comme une trajectoire à sens unique, mesurée par une irréversibilité et une compressibilité. Sur trois modèles, le banc de CoursIA l'a réfutée tel quel : la séparation existe, le critère temporel échoue. Le projet confronte cette lecture à un garde-fou classique sur des conversations réelles, avec un protocole écrit avant la mesure.

- **MVP** : Trente conversations d'attaque en plusieurs tours et trente conversations bénignes qui se durcissent sans attaque ; un classifieur de modération et une sonde sur la direction du refus comme références ; un détecteur de trajectoire sur l'état du modèle à chaque tour ; protocole et seuils déposés avant de lancer la campagne.
- **Réussite** : Détection par tour (rappel, faux positifs sur les conversations bénignes), tour de l'alerte comparé au tour du basculement, test contre des trajectoires mélangées. Un résultat négatif documenté vaut un résultat positif.
- **Extensions** : Attaques adaptatives qui connaissent le détecteur ; combinaison des deux signaux ; coût de calcul par tour.
- **Faisabilité** : Modèle local de moins de 2 milliards de paramètres sur CPU, conversations publiques ou synthétiques ; aucune API payante. Plan B : états du modèle pré-extraits, seule la détection tourne en direct.

**CoursIA** : [Trajectoires de croyances](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/IIT/ICT-Series/ICT-Argumentation-BeliefTrajectories-Python.ipynb) · [Direction du refus](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Security/Control/Control-Refusal-Direction.ipynb) · [Red team au-delà de l’injection](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Security/RedTeam/RedTeam-Beyond-Injection.ipynb) · [Sécurité des prompts](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/09b_Prompt_Security_RedTeam.ipynb)

**Références** : [JailbreakBench](https://arxiv.org/abs/2404.01318) · [Llama Guard](https://arxiv.org/abs/2312.06674) · [Refusal in Language Models Is Mediated by a Single Direction](https://arxiv.org/abs/2406.11717) · [Crescendo multi-turn jailbreak](https://arxiv.org/abs/2404.01833)

<a id="fiche-t2"></a>

### T2 — La propagande est-elle plus compressible que l'information ?

**Difficulté : 4/5** · Mots-clés : `désinformation`, `compression`, `MDL`, `distance de compression`, `détection` · hybride CoursIA

Une intuition circule : le slogan et la propagande se répètent, donc se compressent mieux qu'un texte informatif. Elle se teste sans réseau de neurones : un compresseur standard donne une distance entre textes, et un code à deux parties mesure ce qu'un texte apporte au-delà de son modèle. Le projet confronte ce signal à un détecteur appris sur des corpus annotés, et cherche ce que la compression capte vraiment : la propagande, ou seulement la longueur et le genre.

- **MVP** : Deux corpus publics annotés (techniques de propagande, affirmations vérifiées) ; classifieur par distance de compression ; mesure à deux parties du gain d'information ; référence par modèle de langue affiné ou zéro-shot ; contrôle à longueur et source égales.
- **Réussite** : F1 et calibration des trois approches sur un découpage par source, écart avant et après contrôle de longueur, analyse des erreurs sur quarante exemples relus.
- **Extensions** : Textes générés par LLM imitant chaque style ; flux multilingue ; explication par segments les plus compressibles.
- **Faisabilité** : Compression et classification sur CPU, corpus publics ; budget inférieur à 5 € si une API sert de référence. Plan B : référence par modèle local, corpus réduit.

**CoursIA** : [Code MDL à deux parties](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/IIT/ICT-Series/ICT-16-MDLTwoPartCode-Python.ipynb) · [Détection de sophismes](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/ArgumentAnalysis/Argumentation-02-Fallacies-Detection-Python.ipynb) · [Synthèse argumentation et ICT](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/IIT/ICT-Series/ICT-Argumentation-Capstone-Python.ipynb)

**Références** : [Less is More: Parameter-Free Text Classification with Gzip](https://arxiv.org/abs/2212.09410) · [SemEval-2020 Task 11: Detection of Propaganda Techniques](https://arxiv.org/abs/2009.02696) · [LIAR dataset](https://arxiv.org/abs/1705.00648) · [Clustering by compression](https://doi.org/10.1109/TIT.2005.844059)

<a id="fiche-t3"></a>

### T3 — Agent par capacités : prouver qu'une donnée ne déclenche aucune action

**Difficulté : 5/5** · Mots-clés : `agents`, `injection indirecte`, `capacités`, `flux de données`, `MCP` · hybride CoursIA

Filtrer les injections de prompt revient à deviner l'intention d'un texte. Une autre voie sépare deux rôles : un modèle de confiance écrit le plan à partir de la seule demande de l'utilisateur, un modèle isolé lit les données sans pouvoir appeler d'outil, et chaque valeur porte l'étiquette de sa provenance. Le projet construit cet agent et montre, par la trace d'exécution, qu'aucune valeur venue d'un document ou d'un outil n'a choisi une action. Le verrou est la garantie par construction, pas le score d'un filtre.

- **MVP** : Agent courriel et fichiers avec quatre outils locaux ; interpréteur qui étiquette chaque valeur et refuse un appel dont un argument sensible provient d'une donnée non fiable ; vingt tâches utiles et vingt injections indirectes rejouées.
- **Réussite** : Taux de succès des injections et taux de tâches réussies, comparés à un agent ReAct simple avec et sans filtre ; chaque refus expliqué par la chaîne de provenance.
- **Extensions** : Politiques par outil ; serveur MCP hostile dont la description change ; coût en appels de modèle.
- **Faisabilité** : Outils simulés en local, API texte ou modèle local ; budget inférieur à 8 €. Plan B : plans figés, interpréteur et politiques testés seuls.

**CoursIA** : [Surface d’attaque des outils MCP](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Security/Tooling/Tooling-MCP-Attack-Surface.ipynb) · [Red team au-delà de l’injection](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Security/RedTeam/RedTeam-Beyond-Injection.ipynb) · [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Sécurité des prompts](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/09b_Prompt_Security_RedTeam.ipynb)

**Références** : [Defeating Prompt Injections by Design (CaMeL)](https://arxiv.org/abs/2503.18813) · [AgentDojo](https://arxiv.org/abs/2406.13352) · [Indirect prompt injection](https://arxiv.org/abs/2302.12173) · [Model Context Protocol specification](https://modelcontextprotocol.io/specification)

<a id="fiche-t4"></a>

### T4 — Code cryptographique généré : le tester au lieu de le relire

**Difficulté : 4/5** · Mots-clés : `cryptographie`, `code généré`, `tests de propriétés`, `mauvais usage`, `sécurité` · hybride CoursIA

Un assistant de code écrit volontiers un chiffrement qui fonctionne et qui est faux : vecteur d'initialisation fixe, mode sans authentification, mot de passe haché sans sel. Le code passe ses tests, l'erreur ne se voit pas à l'œil. Le projet fait écrire des fonctions de chiffrement, de signature et de stockage de mots de passe, puis les soumet à des tests de propriétés : deux chiffrements du même message diffèrent, un octet modifié fait échouer le déchiffrement, deux mots de passe identiques donnent deux empreintes différentes.

- **MVP** : Quinze tâches cryptographiques courtes en Python ; trois manières de demander (consigne nue, consigne de sécurité, bibliothèque imposée) ; batterie de tests de propriétés par tâche ; analyseur statique comme second avis.
- **Réussite** : Taux de mauvais usages par manière de demander, désaccords entre tests et analyseur statique, failles trouvées par un seul des deux.
- **Extensions** : Boucle de réparation guidée par le test qui échoue ; même étude en C# ; tâches de dérivation de clé et d'échange de clés.
- **Faisabilité** : Bibliothèque cryptography en local, aucun secret réel, API texte ou modèle local ; budget inférieur à 6 €. Plan B : sorties de modèle figées, batterie de tests seule.

**CoursIA** : [Garde-fous Roslyn](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Vibe-Coding/analyzers/Roslyn-Code-Guardrails.ipynb) · [Chiffrement homomorphe](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SmartContracts/04-Privacy-Cryptography/SC-16-Homomorphic-Encryption-Python.ipynb) · [Preuves à divulgation nulle](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/SmartContracts/04-Privacy-Cryptography/SC-15-Zero-Knowledge-Proofs-Python.ipynb)

**Références** : [Asleep at the Keyboard? Copilot code security](https://arxiv.org/abs/2108.09293) · [CyberSecEval](https://arxiv.org/abs/2312.04724) · [NIST SP 800-38D (GCM)](https://doi.org/10.6028/NIST.SP.800-38D) · [pyca/cryptography](https://cryptography.io/en/latest/)

<a id="fiche-t5"></a>

### T5 — Trouver les exemples empoisonnés par la signature spectrale

**Difficulté : 4/5** · Mots-clés : `empoisonnement`, `porte dérobée`, `SVD`, `activations`, `défense`

Quelques exemples d'entraînement porteurs d'un déclencheur suffisent à installer une porte dérobée dans un classifieur. Dans l'espace des activations, ces exemples tirent souvent la même direction : la première composante singulière de leur classe les isole. Le projet empoisonne un petit modèle de texte, applique cette détection spectrale et une détection par regroupement, puis réentraîne sans les exemples signalés.

- **MVP** : Classifieur de sentiment affiné sur un corpus public ; trois taux d'empoisonnement ; scores spectraux et regroupement des activations par classe ; réentraînement après retrait des exemples suspects.
- **Réussite** : Exemples empoisonnés retrouvés et exemples sains écartés à tort, taux de succès de l'attaque avant et après nettoyage, précision sur les données saines.
- **Extensions** : Déclencheur paraphrasé plus discret ; modèle génératif de code ; comparaison avec une sonde sur les poids.
- **Faisabilité** : Petit modèle de type DistilBERT sur CPU, corpus public ; aucune API. Plan B : activations pré-calculées, seule la détection tourne.

**CoursIA** : [Neurones dormants](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Security/Oversight/Backdoor-Dormant-Neurons.ipynb) · [Red team au-delà de l’injection](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Security/RedTeam/RedTeam-Beyond-Injection.ipynb) · [Porte dérobée dans du code](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Security/Oversight/Backdoor-Code-From-Scratch.ipynb)

**Références** : [Spectral Signatures in Backdoor Attacks](https://arxiv.org/abs/1811.00636) · [BadNets](https://arxiv.org/abs/1708.06733) · [Activation Clustering](https://arxiv.org/abs/1811.03728) · [Sleeper Agents](https://arxiv.org/abs/2401.05566)

<a id="fiche-t6"></a>

### T6 — Une décision tient-elle face à un contre-argument ?

**Difficulté : 4/5** · Mots-clés : `complaisance`, `révision de croyances`, `contre-argument`, `audit`, `décision` · hybride CoursIA

Dans un domaine régulé, une réponse ne vaut que si elle change pour une bonne raison et résiste à une mauvaise. Un modèle complaisant cède à « êtes-vous sûr ? » autant qu'à un fait nouveau. Le projet suit chaque décision comme un système de maintien de la vérité : la conclusion dépend de prémisses, et elle ne doit tomber que si l'une d'elles tombe. Il oppose des contre-arguments valides, des pressions sans contenu et des affirmations fausses.

- **MVP** : Soixante cas de décision bornée (éligibilité, conformité) avec leurs règles ; pour chaque cas, trois relances : fait nouveau qui doit changer la réponse, pression sociale, fausse affirmation ; graphe de justification extrait de la réponse.
- **Réussite** : Changements justifiés, changements injustifiés, refus de changer à tort ; accord entre le graphe extrait et les règles du cas.
- **Extensions** : Rapport d'audit par décision ; débat entre deux modèles ; effet d'un raisonnement explicite avant réponse.
- **Faisabilité** : API texte ou modèle local, cas synthétiques ; budget inférieur à 8 €. Plan B : réponses figées, analyse des graphes en local.

**CoursIA** : [Maintien de la vérité et ICT](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/IIT/ICT-Series/ICT-Argumentation-TruthMaintenance-Python.ipynb) · [JTMS](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/ArgumentAnalysis/Argumentation-06-JTMS-Python.ipynb) · [Débat et sûreté](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/SymbolicAI/ArgumentAnalysis/Argumentation-11-Debate-Protocol-Safety-Python.ipynb)

**Références** : [Towards Understanding Sycophancy in Language Models](https://arxiv.org/abs/2310.13548) · [Are You Sure? The FlipFlop Experiment](https://arxiv.org/abs/2311.08596) · [Discovering Language Model Behaviors with Model-Written Evaluations](https://arxiv.org/abs/2212.09251)

<a id="fiche-t7"></a>

### T7 — Agent d'entreprise : demander l'accord seulement pour l'irréversible

**Difficulté : 4/5** · Mots-clés : `agents`, `réversibilité`, `validation humaine`, `bac à sable`, `sûreté` · hybride CoursIA

Un agent qui demande confirmation à chaque geste n'est pas utilisé ; un agent qui n'en demande jamais finit par supprimer, payer ou envoyer à tort. Le projet classe chaque action par sa réversibilité (lecture, brouillon annulable, envoi, paiement, suppression) à partir de l'état du bac à sable, pas du texte du modèle, et ne réclame l'accord humain que pour ce qui ne se défait pas. Le verrou est le compromis entre dégâts évités et sollicitations de l'humain.

- **MVP** : Bac à sable d'entreprise (courriels, fichiers, factures) avec annulation ; quarante tâches dont dix pièges ambigus ; trois politiques : jamais d'accord, accord systématique, accord sur l'irréversible.
- **Réussite** : Actions irréversibles fautives exécutées, nombre de sollicitations humaines, tâches réussies ; tableau des trois politiques.
- **Extensions** : Budget de risque par session ; explication présentée à l'humain ; journal d'audit rejouable.
- **Faisabilité** : Outils simulés en local, API texte ou modèle local ; budget inférieur à 8 €. Plan B : traces d'agent figées, politique rejouée seule.

**CoursIA** : [Function calling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb) · [Surface d’attaque des outils MCP](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Security/Tooling/Tooling-MCP-Attack-Surface.ipynb) · [Red team au-delà de l’injection](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Security/RedTeam/RedTeam-Beyond-Injection.ipynb)

**Références** : [ToolEmu: Identifying the Risks of LM Agents](https://arxiv.org/abs/2309.15817) · [τ-bench](https://arxiv.org/abs/2406.12045) · [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
