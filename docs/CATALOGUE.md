# Catalogue Bachelor — projets au choix

Choisissez un verrou technique plutôt qu’un secteur. Comparez deux méthodes sur les mêmes cas et gardez les exemples de test à part. Les nombres indiqués dans les fiches servent à dimensionner votre proposition.

### A2 — Mémoire persistante multi-sessions

**Difficulté : 3/5** · Mots-clés : `memory`, `sessions`, `privacy`, `evaluation`

Concevoir une mémoire explicite qui décide quoi conserver, retrouver, mettre à jour ou oublier entre plusieurs sessions. Contrairement à l'ancien majordome, le domaine importe peu : le verrou est la politique de mémoire et sa mesure.

- **MVP** : journal d'événements, mémoire sémantique persistante, mise à jour des faits contradictoires et commande d'oubli.
- **Réussite** : scénarios multi-sessions reproductibles mesurant rappel utile, faux souvenirs, fraîcheur et suppression effective.
- **Extensions** : mémoire épisodique/sémantique séparée, chiffrement, expiration automatique.
- **Faisabilité** : base locale ou Qdrant ; GPU non requis ; données synthétiques obligatoires ; budget cible inférieur à 5 €. Plan B : embeddings locaux.

**CoursIA** : [Persistent Memory](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/14_Persistent_Memory.ipynb) · [Hands-On Grounding](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/01-Hands-On-Grounding.ipynb) · [Stockage vectoriel](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/05-Stockage-Vectoriel.ipynb)

**Références** : [MemGPT](https://arxiv.org/abs/2310.08560) · [Qdrant — Payload](https://qdrant.tech/documentation/concepts/payload/) · [OWASP — LLM02 Insecure Output Handling](https://genai.owasp.org/llmrisk/llm02-insecure-output-handling/)

### A4 — Mémoire multimodale évaluable

**Difficulté : 4/5** · Mots-clés : `multimodal`, `kernel-memory`, `retrieval`, `grounding`

Indexer un corpus mêlant texte et images, puis répondre à des questions dont certaines exigent les deux modalités. Le projet doit isoler l'apport du retrieval multimodal.

- **MVP** : ingestion multimodale, recherche, réponses sourcées et interface minimale.
- **Réussite** : jeu annoté d'au moins 30 questions unimodales/multimodales, ablations texte seul/image seule/fusion.
- **Extensions** : OCR, tableaux, late fusion, cache d'embeddings.
- **Faisabilité** : Qdrant ou Kernel Memory ; API vision possible ; budget cible inférieur à 15 €. Plan B : embeddings et légendes pré-calculés.

**CoursIA** : [Kernel Memory Multimodal](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/09-KernelMemory-Multimodal.ipynb) · [Kernel Memory In Process](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/06-KernelMemory-InProcess.ipynb) · [Semantic Kernel Multimodal](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/07-SemanticKernel-MultiModal.ipynb)

**Références** : [Microsoft Kernel Memory](https://github.com/microsoft/kernel-memory) · [CLIP](https://arxiv.org/abs/2103.00020) · [Qdrant — Multivectors](https://qdrant.tech/documentation/concepts/vectors/#multivectors)

### A5 — Long contexte contre RAG sous ablation

**Difficulté : 3/5** · Mots-clés : `long-context`, `rag`, `ablation`, `grounding`

Comparer sur un même corpus l'injection du document complet, un RAG simple et un RAG reranké. Le verrou technique est d'isoler l'effet du contexte disponible sans confondre qualité, coût et latence.

- **MVP** : corpus public, 50 questions, trois stratégies et journal des passages réellement fournis au modèle.
- **Réussite** : exactitude, fidélité des citations, coût, latence et performance selon la position de l'information.
- **Extensions** : compression de contexte, cache, questions multi-documents.
- **Faisabilité** : API texte ou modèle local ; budget cible inférieur à 12 €. Plan B : réponses mises en cache et corpus réduit.

**CoursIA** : [Long Context Strategies](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/10c_Long_Context_Strategies.ipynb) · [RAG moderne](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/05_RAG_Modern.ipynb)

**Références** : [Lost in the Middle](https://arxiv.org/abs/2307.03172) · [RAG](https://arxiv.org/abs/2005.11401) · [LongBench](https://arxiv.org/abs/2308.14508)

### A7 — Cohérence interne des documents longs

**Difficulté : 4/5** · Mots-clés : `consistency`, `nli`, `long-context`, `detection`

Construire un détecteur d'incohérences pour des documents générés de plusieurs pages : contradictions entre sections, chiffres divergents, annonces non tenues. Le verrou technique est la détection mesurée sur un corpus dont les incohérences sont connues.

- **MVP** : générateur de documents longs structurés, injecteur de contradictions contrôlées (20 documents, 60 incohérences) et pipeline de détection par paires de passages.
- **Réussite** : précision/rappel par type d'incohérence, fenêtres glissantes contre contexte complet, faux positifs sur textes cohérents.
- **Extensions** : graphe d'affirmations, réécriture corrective, détection pendant la génération.
- **Faisabilité** : API texte ou modèle local ; budget cible inférieur à 10 €. Plan B : corpus annoté fourni sans génération.

**CoursIA** : [Long Context Strategies](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/10c_Long_Context_Strategies.ipynb) · [Evaluating Generated Text](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/22_Evaluating_Generated_Text.ipynb) · [Hands-On Grounding](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/01-Hands-On-Grounding.ipynb)

**Références** : [SummaC](https://arxiv.org/abs/2111.09525) · [AlignScore](https://arxiv.org/abs/2305.16739) · [LongBench](https://arxiv.org/abs/2308.14508)

### B4 — Générateur auto-validant de notebooks

**Difficulté : 4/5** · Mots-clés : `notebooks`, `generation`, `execution`, `validation`

Générer un notebook pédagogique à partir d'un cahier des charges, l'exécuter automatiquement, diagnostiquer ses erreurs puis produire un rapport de conformité. Le succès est l'exécution reproductible, pas la beauté d'un exemple.

- **MVP** : gabarit, génération, exécution isolée, deux boucles de correction maximum et rapport.
- **Réussite** : dix cahiers des charges ; taux d'exécution, conformité structurelle, corrections et coût.
- **Extensions** : plusieurs kernels, rubric pédagogique, sandbox renforcée.
- **Faisabilité** : Jupyter + Semantic Kernel ; exécution limitée et sans accès aux secrets ; budget cible inférieur à 8 €. Plan B : exercices Python sans réseau.

**CoursIA** : [NotebookMaker](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/10-SemanticKernel-NotebookMaker.ipynb) · [NotebookMaker batch paramétré](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/10b-SemanticKernel-NotebookMaker-batch-parameterized.ipynb) · [Code Interpreter](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/07_Code_Interpreter.ipynb)

**Références** : [Jupyter nbclient](https://nbclient.readthedocs.io/) · [nbformat](https://nbformat.readthedocs.io/) · [OWASP — Insecure Output Handling](https://genai.owasp.org/llmrisk/llm052025-improper-output-handling/)

### C5 — Restauration d'images sans invention

**Difficulté : 3/5** · Mots-clés : `restoration`, `super-resolution`, `hallucination`, `benchmark`

Améliorer des images dégradées en contrôlant ce que le modèle invente : le projet oppose des restaureurs génératifs et des méthodes conservatrices sur un protocole où la vérité terrain existe.

- **MVP** : corpus d'images dégradées de façon contrôlée (flou, bruit, compression, basse résolution), deux pipelines de restauration et mesures de fidélité et de perception.
- **Réussite** : PSNR/SSIM contre l'original, distance perceptuelle, mesure de l'invention (détails absents de l'original mais ajoutés par le modèle) et analyse coût–latence.
- **Extensions** : restauration par instruction en langage naturel, cas sans vérité terrain, interface comparative.
- **Faisabilité** : modèles pré-entraînés locaux ou API image ; budget cible inférieur à 12 €. Plan B : corpus d'images dégradées pré-calculé.

**CoursIA** : [Qwen Image Edit](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/01-Foundation/01-5-Qwen-Image-Edit.ipynb) · [Basic Image Operations](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/01-Foundation/01-3-Basic-Image-Operations.ipynb) · [Comparaison multi-modèles](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/03-Orchestration/03-1-Multi-Model-Comparison.ipynb)

**Références** : [Real-ESRGAN](https://arxiv.org/abs/2107.10833) · [SwinIR](https://arxiv.org/abs/2108.10257) · [LPIPS](https://arxiv.org/abs/1801.03924)

### C6 — Images synthétiques pour l'entraînement

**Difficulté : 4/5** · Mots-clés : `synthetic-data`, `vision`, `augmentation`, `ablation`

Générer des images d'entraînement synthétiques pour une tâche de vision pauvre en données et mesurer si elles améliorent réellement un classifieur, seules ou en appoint d'un petit jeu réel.

- **MVP** : tâche de classification bornée (huit classes), jeu réel réduit, générateur contrôlé (prompt, variantes, arrière-plan) et entraînement reproductible.
- **Réussite** : courbes exactitude/taille du jeu réel avec et sans synthèse, ablation des ratios réel/synthétique et analyse de l'écart de distribution.
- **Extensions** : randomisation de domaine, filtrage des images synthétiques, artefacts appris détectés.
- **Faisabilité** : diffusion locale ou API image et petit CNN ; GPU partagé utile mais CPU acceptable ; budget cible inférieur à 12 €. Plan B : jeu d'images synthétiques fourni.

**CoursIA** : [FLUX Advanced Generation](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/02-Advanced/02-2-FLUX-1-Advanced-Generation.ipynb) · [Workflow Orchestration](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/03-Orchestration/03-2-Workflow-Orchestration.ipynb) · [Comparaison multi-modèles](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/03-Orchestration/03-1-Multi-Model-Comparison.ipynb)

**Références** : [Domain Randomization](https://arxiv.org/abs/1703.06907) · [DatasetDM](https://arxiv.org/abs/2308.06160) · [Latent Diffusion](https://arxiv.org/abs/2112.10752)

### D3 — Séparation et restauration de sources audio

**Difficulté : 3/5** · Mots-clés : `source-separation`, `denoising`, `audio`, `benchmark`

Séparer voix, musique et bruit puis restaurer la composante utile sans introduire d'artefacts. Le verrou technique est l'évaluation objective et perceptuelle de la reconstruction.

- **MVP** : corpus de 20 mélanges contrôlés, deux pipelines et interface d'écoute aveugle.
- **Réussite** : SI-SDR, intelligibilité, temps de traitement et préférence humaine.
- **Extensions** : séparation temps réel, plusieurs locuteurs, estimation de confiance.
- **Faisabilité** : Demucs et outils locaux ; GPU facultatif. Plan B : extraits courts pré-calculés.

**CoursIA** : [Demucs Source Separation](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/02-Advanced/02-4-Demucs-Source-Separation.ipynb) · [Basic Audio Operations](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-3-Basic-Audio-Operations.ipynb)

**Références** : [Demucs](https://github.com/facebookresearch/demucs) · [MUSDB18](https://sigsep.github.io/datasets/musdb.html) · [BSS Eval](https://arxiv.org/abs/1811.02508)

### D4 — Synthèse vocale expressive et prosodie

**Difficulté : 3/5** · Mots-clés : `tts`, `prosody`, `emotion`, `evaluation`

Contrôler rythme, pauses, accentuation et émotion d'une voix synthétique sur des textes constants. Le verrou technique est de relier paramètres prosodiques et perception sans cloner une voix non consentie.

- **MVP** : 30 phrases, quatre intentions, deux systèmes et mesures acoustiques.
- **Réussite** : reconnaissance d'intention à l'aveugle, naturalité, durée et coût.
- **Extensions** : SSML, transfert de style consenti, contrôle fin.
- **Faisabilité** : voix synthétiques ou consenties uniquement ; API ou moteur local. Plan B : Kokoro local.

**CoursIA** : [Expressive TTS](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/02-Advanced/02-8-Expressive-TTS.ipynb) · [TTS Voice Benchmark](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/04-Applications/04-Voix/04-7-TTS-Voice-Benchmark.ipynb)

**Références** : [SSML](https://www.w3.org/TR/speech-synthesis11/) · [P.808](https://www.itu.int/rec/P-REC-P.808) · [Kokoro](https://github.com/hexgrad/kokoro)

### D5 — Diarisation et transcription de réunion

**Difficulté : 3/5** · Mots-clés : `asr`, `diarization`, `meetings`, `wer-der`

Transcrire une réunion en séparant qui a dit quoi : le projet mesure à la fois la qualité de transcription (WER) et l'attribution des locuteurs (DER) sur des réunions multi-locuteurs.

- **MVP** : corpus de dix réunions publiques ou enregistrées en conditions réelles, pipeline STT et diarisation, transcription alignée locuteur/temps.
- **Réussite** : WER par locuteur et par condition, DER, erreurs d'attribution typiques, effet d'un glossaire métier et latence de traitement.
- **Extensions** : transcription en flux, empreinte vocale, résumé par locuteur.
- **Faisabilité** : Whisper local ou API ; GPU non requis ; enregistrements consentis uniquement. Plan B : extrait AMI pré-découpé.

**CoursIA** : [OpenAI Whisper STT](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-2-OpenAI-Whisper-STT.ipynb) · [Whisper Local](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-4-Whisper-Local.ipynb) · [Transcription Pipeline](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/04-Applications/04-2-Transcription-Pipeline.ipynb)

**Références** : [Whisper](https://arxiv.org/abs/2212.04356) · [pyannote.audio](https://github.com/pyannote/pyannote-audio) · [AMI Meeting Corpus](https://groups.inf.ed.ac.uk/ami/)

### D6 — Podcast sourcé de bout en bout

**Difficulté : 3/5** · Mots-clés : `podcast`, `pipeline`, `grounding`, `tts`

Produire automatiquement un épisode de podcast parlé à partir d'un sujet et de sources publiques, avec un script dont chaque affirmation reste traçable jusqu'à sa source. Le verrou technique est la fidélité factuelle du script et la qualité d'écoute, pas la seule voix.

- **MVP** : collecte de sources sur un sujet borné, script segmenté et sourcé, narration TTS et épisode de cinq minutes avec notes d'épisode.
- **Réussite** : fidélité des affirmations aux sources (échantillon vérifié), taux de phrases sans source, intelligibilité et naturalité à l'aveugle, coût par épisode.
- **Extensions** : multi-voix, diffusion automatique, veille récurrente hebdomadaire.
- **Faisabilité** : API texte et TTS local ou API ; budget cible inférieur à 12 €. Plan B : sources fournies et narration locale.

**CoursIA** : [Audiobook Pipeline](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/04-Applications/04-Audiobook/04-6-Audiobook-Pipeline.ipynb) · [PDF Web Search](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/06_PDF_Web_Search.ipynb) · [Expressive TTS](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/02-Advanced/02-8-Expressive-TTS.ipynb)

**Références** : [QAGS](https://arxiv.org/abs/2004.04228) · [P.808](https://www.itu.int/rec/P-REC-P.808) · [SSML](https://www.w3.org/TR/speech-synthesis11/)

### E5 — Montage automatique mesuré

**Difficulté : 4/5** · Mots-clés : `auto-editing`, `video-understanding`, `pacing`, `pipeline`

Monter automatiquement des rushes bruts en séquence regardable : sélection des prises, coupes et rythme sous une durée cible. Le verrou technique est la qualité du montage mesurée, pas la génération d'images.

- **MVP** : rushes fournis (20 minutes, scènes connues), détection de plans et de prises, sélection assistée par modèle vision, assemblage et rapport de montage.
- **Réussite** : couverture des points de scénario attendus, durée cible respectée, métriques de rythme et évaluation humaine comparative contre un montage manuel.
- **Extensions** : sous-titres, musique adaptée, multi-caméras.
- **Faisabilité** : FFmpeg/MoviePy et VLM ; GPU inutile ; rushes tournés au téléphone acceptés ; budget cible inférieur à 12 €. Plan B : rushes et détections de plans fournis.

**CoursIA** : [Video Workflow Orchestration](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Video/03-Orchestration/03-2-Video-Workflow-Orchestration.ipynb) · [GPT-5 Video Understanding](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Video/01-Foundation/01-2-GPT-5-Video-Understanding.ipynb) · [Video Operations Basics](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Video/01-Foundation/01-1-Video-Operations-Basics.ipynb)

**Références** : [FFmpeg](https://ffmpeg.org/documentation.html) · [PySceneDetect](https://www.scenedetect.com/) · [P.1203](https://www.itu.int/rec/T-REC-P.1203)

### F3 — Application GenAI observable avec .NET Aspire

**Difficulté : 4/5** · Mots-clés : `aspire`, `observability`, `streaming`, `integration-tests`

Construire une petite application GenAI distribuée dont les appels modèle, outils et erreurs sont visibles dans des traces, métriques et logs corrélés.

- **MVP** : frontend/API, service agent, streaming, télémétrie et tests d'intégration.
- **Réussite** : retrouver automatiquement une requête de bout en bout, mesurer latence/token, détecter trois pannes injectées.
- **Extensions** : multi-provider, circuit breaker, évaluation continue.
- **Faisabilité** : .NET Aspire + conteneurs ; GPU inutile ; budget cible inférieur à 10 €. Plan B : connecteur modèle simulé.

**CoursIA** : [Aspire Observabilité](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/03-Aspire-Observabilite.ipynb) · [Aspire Streaming Agent](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/04-Aspire-Streaming-Agent.ipynb) · [Aspire Tests Integration](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/05-Aspire-Tests-Integration.ipynb)

**Références** : [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire/) · [OpenTelemetry .NET](https://opentelemetry.io/docs/languages/net/) · [Polly](https://www.pollydocs.org/)

### F4 — Routeur multi-fournisseurs avec failover

**Difficulté : 3/5** · Mots-clés : `routing`, `failover`, `multi-provider`, `slo`

Router chaque requête vers un modèle selon ses capacités, son coût et son état, puis basculer proprement en cas d'échec. Le verrou technique est de respecter un SLO sans masquer les différences de comportement entre fournisseurs.

- **MVP** : trois connecteurs, health checks, règles de routage, retries bornés et traces corrélées.
- **Réussite** : 100 requêtes avec pannes injectées ; disponibilité, p95, coût et taux de bascules correctes.
- **Extensions** : circuit breaker, routage appris, cache sémantique.
- **Faisabilité** : APIs à faible volume ou connecteurs simulés ; budget inférieur à 12 €. Plan B : serveur de réponses déterministes.

**CoursIA** : [Model Merging Routing](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-05-ModelMerging-Routing-Python.ipynb) · [SemanticFleet MultiConnector](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/07-Aspire-SemanticFleet-MultiConnector.ipynb)

**Références** : [Azure Architecture — Circuit Breaker](https://learn.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker) · [OpenTelemetry](https://opentelemetry.io/docs/) · [Polly](https://www.pollydocs.org/)

### F5 — Assistant support avec escalade mesurée

**Difficulté : 3/5** · Mots-clés : `support`, `routing`, `escalation`, `oos-detection`

Construire un assistant de support qui répond aux questions couvertes et escalade proprement vers un humain sinon. Le verrou technique est la politique d'escalade : ni sur-escalade de questions résolubles, ni réponses hors périmètre.

- **MVP** : base de connaissances bornée, corpus de 150 tickets étiquetés (dans/hors périmètre/ambigu), décision réponse/escalade et file humaine simulée.
- **Réussite** : taux de résolution correcte, sous-escalade (réponses fausses), sur-escalade (questions résolubles escaladées), latence et matrice de confusion par intention.
- **Extensions** : priorisation de file, apprentissage des frontières d'escalade, tickets ambigus arbitrés.
- **Faisabilité** : corpus public ou tickets synthétiques ; API texte ; budget cible inférieur à 10 €. Plan B : intentions scriptées.

**CoursIA** : [Mesurer la dérive d'un Copilot](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Plateformes-Conversationnelles/AI-Engine-WordPress/03-Functional/03-1-Chatbots/mesurer-la-derive-dun-copilot.ipynb) · [Production Patterns](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/09_Production_Patterns.ipynb) · [Structured Outputs](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Références** : [Banking77](https://huggingface.co/datasets/banking77) · [Rasa — Dialogue Management](https://rasa.com/docs/rasa/dialogue-management/) · [Bot Framework — Human Handoff](https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-handoff-human?view=azure-bot-service-4.0)

### G2 — Garde-fous Roslyn pour code généré

**Difficulté : 4/5** · Mots-clés : `roslyn`, `static-analysis`, `generated-code`, `verification`

Créer des analyseurs Roslyn qui interdisent des motifs dangereux ou non conformes dans du C# généré, puis mesurer leur précision sur un corpus contrôlé.

- **MVP** : quatre règles, diagnostics et code fixes, générateur de cas positifs/négatifs.
- **Réussite** : précision/rappel, zéro faux négatif sur règles critiques, tests unitaires et intégration avant compilation.
- **Extensions** : taint analysis, configuration par politique, boucle de réparation LLM.
- **Faisabilité** : .NET uniquement, API facultative, aucun GPU ; budget cible inférieur à 5 €. Plan B : corpus synthétique versionné.

**CoursIA** : [Roslyn Code Guardrails](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Vibe-Coding/analyzers/Roslyn-Code-Guardrails.ipynb) · [Aspire GardeFous Roslyn](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Integrations-DotNet/Aspire/06-Aspire-GardeFous-Roslyn.ipynb) · [CSharpRepl Live Patching](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Vibe-Coding/docs/CSharpRepl-Live-Patching.ipynb)

**Références** : [Roslyn analyzers](https://learn.microsoft.com/en-us/dotnet/csharp/roslyn-sdk/tutorials/how-to-write-csharp-analyzer-code-fix) · [Microsoft.CodeAnalysis.Testing](https://www.nuget.org/packages/Microsoft.CodeAnalysis.Analyzer.Testing/) · [CWE Top 25](https://cwe.mitre.org/top25/)

### G3 — Pair-programming IA en étude contrôlée

**Difficulté : 3/5** · Mots-clés : `pair-programming`, `experiment`, `productivity`, `quality`

Mesurer l'effet d'un assistant de code sur des tâches comparables, avec et sans assistance. Le verrou technique est un protocole contrôlé qui évite de confondre vitesse, qualité et familiarité.

- **MVP** : huit tâches appariées, participants ou runs croisés, journal du temps et tests cachés.
- **Réussite** : taux de réussite, temps, taille des diffs, défauts et charge perçue avec analyse des biais.
- **Extensions** : novices/experts, types de prompts, maintenance différée.
- **Faisabilité** : petits dépôts jetables et budget de tours borné. Plan B : traces enregistrées complétées par des runs automatisés.

**CoursIA** : [Claude CLI Bases](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Vibe-Coding/Claude-Code/notebooks/01-Claude-CLI-Bases.ipynb) · [Claude CLI Sessions](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Vibe-Coding/Claude-Code/notebooks/02-Claude-CLI-Sessions.ipynb)

**Références** : [METR — Early-2025 AI Coding Study](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/) · [SWE-bench](https://www.swebench.com/) · [SPACE framework](https://queue.acm.org/detail.cfm?id=3454124)

### H4 — Provenance et détection de contenus synthétiques

**Difficulté : 3/5** · Mots-clés : `provenance`, `watermarking`, `detection`, `c2pa`

Comparer métadonnées de provenance, watermarking et classifieurs sur des contenus transformés. Le verrou technique est la robustesse après compression, recadrage ou paraphrase, pas un détecteur présenté sur ses données d'entraînement.

- **MVP** : corpus texte/image, trois transformations, deux méthodes de détection et vérification C2PA.
- **Réussite** : précision/rappel, calibration, robustesse par transformation et taux de faux positifs.
- **Extensions** : chaîne de provenance, attaques adaptatives, interface d'inspection.
- **Faisabilité** : contenus synthétiques et publics uniquement ; GPU non requis. Plan B : caractéristiques pré-calculées.

**CoursIA** : [Production Integration](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/04-Applications/04-3-Production-Integration.ipynb) · [Evaluating Generated Text](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/22_Evaluating_Generated_Text.ipynb)

**Références** : [C2PA Specification](https://c2pa.org/specifications/specifications/2.2/specs/C2PA_Specification.html) · [SynthID](https://deepmind.google/technologies/synthid/) · [NIST GenAI Profile](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence)

### H5 — Constitution IA et coût des refus

**Difficulté : 3/5** · Mots-clés : `constitutional-ai`, `guardrails`, `refusal`, `evaluation`

Définir une politique de réponse, l'appliquer par prompt ou filtre puis mesurer sécurité et sur-refus. Le verrou technique est le compromis entre violations évitées et requêtes légitimes refusées.

- **MVP** : constitution versionnée, 100 scénarios sûrs/limites/dangereux, deux mécanismes et rapport.
- **Réussite** : taux de violation, faux refus, cohérence des explications, coût et latence.
- **Extensions** : critiques multiples, politiques par domaine, tests multilingues.
- **Faisabilité** : outils simulés et API texte ; budget inférieur à 10 €. Plan B : modèle local.

**CoursIA** : [Prompt Security Red Team](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/09b_Prompt_Security_RedTeam.ipynb) · [Production Patterns](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/09_Production_Patterns.ipynb)

**Références** : [Constitutional AI](https://arxiv.org/abs/2212.08073) · [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework) · [OWASP GenAI](https://genai.owasp.org/)

### I1 — QLoRA sans contamination de l'évaluation

**Difficulté : 4/5** · Mots-clés : `qlora`, `fine-tuning`, `data-leakage`, `evaluation`

Adapter un petit modèle à une tâche structurée et prouver que le gain ne vient ni d'une fuite train/test ni d'une mauvaise baseline. Les domaines de biais, recrutement, extraction documentaire et fallacies sont exclus.

- **MVP** : dataset versionné, contrôles de doublons, baseline prompt-only, QLoRA et test tenu à l'écart.
- **Réussite** : métrique adaptée, intervalles de confiance, coût mémoire/temps et analyse d'erreurs.
- **Extensions** : comparaison RAG, quantification, autre taille de modèle.
- **Faisabilité** : Colab ou GPU partagé, petit modèle uniquement ; budget cible inférieur à 10 € ; aucun GPU requis pour la démo si l'adapter est sauvegardé. Plan B : entraînement très réduit.

**CoursIA** : [QLoRA Quantization](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-02-QLoRA-Quantization-Python.ipynb) · [Supervised Fine-Tuning](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-03-Supervised-FineTuning-SFT-Python.ipynb) · [LoRA Fine-Tuning](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/21_LoRA_FineTuning.ipynb)

**Références** : [QLoRA](https://arxiv.org/abs/2305.14314) · [PEFT](https://huggingface.co/docs/peft/) · [Data Contamination in LLMs](https://arxiv.org/abs/2311.04850)

### I2 — Inférence locale .NET face aux API cloud

**Difficulté : 3/5** · Mots-clés : `dotnet`, `local-inference`, `quantization`, `benchmark`

Comparer LLamaSharp, ONNX Runtime GenAI ou TensorSharp à une API cloud sur une tâche contrôlée. Construire une frontière coût–latence–qualité plutôt qu'un simple serveur local.

- **MVP** : deux moteurs locaux ou un local/un cloud, même jeu de 50 requêtes, instrumentation mémoire et tokens.
- **Réussite** : p50/p95, débit, mémoire, qualité, coût projeté et protocole reproductible.
- **Extensions** : quantifications multiples, batching, streaming.
- **Faisabilité** : modèles compacts ; CPU accepté ; budget cloud de comparaison inférieur à 8 €. Plan B : GGUF très quantifié et sous-échantillon.

**CoursIA** : [Inference Mechanics](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/10b_Inference_Mechanics.ipynb) · [Bake-off .NET TensorSharp / ORT GenAI](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/10d_TensorSharp_DotNet_Inference.ipynb) · [Quantization](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/11_Quantization.ipynb)

**Références** : [LLamaSharp](https://github.com/SciSharp/LLamaSharp) · [ONNX Runtime GenAI](https://onnxruntime.ai/docs/genai/) · [llama.cpp](https://github.com/ggml-org/llama.cpp)

### I3 — Frontière coût-précision du test-time compute

**Difficulté : 4/5** · Mots-clés : `reasoning`, `test-time-compute`, `tree-of-thoughts`, `scaling`

Étudier combien de calcul à l'inférence améliore réellement une tâche vérifiable : échantillonnage multiple, vote, Tree of Thoughts et modèle à raisonnement natif.

- **MVP** : deux jeux de problèmes, quatre budgets de calcul, trois stratégies et vérificateur automatique.
- **Réussite** : courbes accuracy/coût/latence, analyse par difficulté et point de rendement décroissant.
- **Extensions** : sélection adaptative du budget, self-consistency pondérée.
- **Faisabilité** : très consommateur de tokens ; budget dur de 20 € et petites séries pilotes. Plan B : modèle local ou résultats mis en cache.

**CoursIA** : [Tree of Thoughts](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/15_Tree_of_Thoughts_Search.ipynb) · [Scaling Test-Time Compute](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/16_Scaling_Test_Time_Compute.ipynb) · [Native Reasoning vs Scaling](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/17_Native_Reasoning_vs_Scaling.ipynb)

**Références** : [Tree of Thoughts](https://arxiv.org/abs/2305.10601) · [Self-Consistency](https://arxiv.org/abs/2203.11171) · [Scaling LLM Test-Time Compute](https://arxiv.org/abs/2408.03314)

### I4 — Fusion et routage de modèles spécialisés

**Difficulté : 5/5** · Mots-clés : `model-merging`, `routing`, `specialization`, `benchmark`

Combiner ou router de petits modèles spécialisés sans perdre leurs compétences propres. Le verrou technique est de démontrer un gain sur un holdout multi-domaines plutôt que sur les données d'adaptation.

- **MVP** : deux spécialistes, une baseline générale, fusion ou routeur et jeu de test tenu à l'écart.
- **Réussite** : qualité par domaine, oubli, mémoire, latence et coût comparés aux spécialistes isolés.
- **Extensions** : plusieurs méthodes de fusion, routeur appris, quantification.
- **Faisabilité** : petits modèles et adapters ; GPU partagé recommandé. Plan B : fusion d'adapters pré-entraînés.

**CoursIA** : [Model Merging Routing](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-05-ModelMerging-Routing-Python.ipynb) · [QLoRA Quantization](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-02-QLoRA-Quantization-Python.ipynb)

**Références** : [MergeKit](https://github.com/arcee-ai/mergekit) · [TIES-Merging](https://arxiv.org/abs/2306.01708) · [PEFT](https://huggingface.co/docs/peft/)

### J2 — Analyste multimodal de données

**Difficulté : 4/5** · Mots-clés : `data-analysis`, `charts`, `multimodal`, `verification`

Répondre à des questions sur tableaux et graphiques en produisant calculs, visualisations et traces vérifiables. Le verrou technique est la correspondance entre réponse narrative, code exécuté et valeurs sources.

- **MVP** : trois jeux publics, 40 questions, génération de code bornée et rapport liant chaque chiffre à son calcul.
- **Réussite** : exactitude numérique, exécution, fidélité des graphiques et taux de réponses non justifiées.
- **Extensions** : images de graphiques, détection d'anomalies, questions interactives.
- **Faisabilité** : Python/pandas en sandbox ; GPU inutile. Plan B : requêtes et graphiques prédéfinis.

**CoursIA** : [Code Interpreter](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/07_Code_Interpreter.ipynb) · [Semantic Kernel Multimodal](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/07-SemanticKernel-MultiModal.ipynb)

**Références** : [Pandas](https://pandas.pydata.org/docs/) · [Vega-Lite](https://vega.github.io/vega-lite/) · [ChartQA](https://arxiv.org/abs/2203.10244)

### J3 — Expériences reproductibles auto-validées

**Difficulté : 4/5** · Mots-clés : `experiments`, `reproducibility`, `code-generation`, `validation`

Transformer une hypothèse et un protocole structuré en expérience exécutable, puis contrôler que résultats et conclusions restent cohérents. Le verrou technique est la validation automatique de la chaîne expérimentale.

- **MVP** : dix protocoles simples, environnement figé, exécution isolée, contrôles statistiques et rapport.
- **Réussite** : taux d'exécution propre, reproductibilité multi-runs, erreurs méthodologiques détectées et conclusions corrigées.
- **Extensions** : seeds multiples, provenance des données, génération de contre-expériences.
- **Faisabilité** : expériences synthétiques courtes ; aucun GPU. Plan B : templates paramétrés sans génération libre.

**CoursIA** : [NotebookMaker](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/10-SemanticKernel-NotebookMaker.ipynb) · [Evaluating Generated Text](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/22_Evaluating_Generated_Text.ipynb)

**Références** : [ACM Artifact Review and Badging](https://www.acm.org/publications/policies/artifact-review-and-badging-current) · [SciPy](https://docs.scipy.org/doc/scipy/) · [Jupyter Reproducible Research](https://jupyter.org/)

### K1 — Confidentialité des données synthétiques

**Difficulté : 4/5** · Mots-clés : `synthetic-data`, `privacy`, `utility`, `membership-inference`

Générer des données tabulaires synthétiques et mesurer simultanément utilité et risque de mémorisation. Le verrou technique est de ne pas déclarer les données privées sans attaque ni métrique.

- **MVP** : dataset public, deux générateurs, tests d'utilité et attaque simple d'inférence d'appartenance.
- **Réussite** : compromis utilité/confidentialité, intervalles de confiance et identification des lignes à risque.
- **Extensions** : confidentialité différentielle, attributs rares, audit par sous-groupes.
- **Faisabilité** : données publiques ou artificielles uniquement ; GPU inutile. Plan B : générateurs statistiques.

**CoursIA** : [Structured Outputs](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb) · [Supervised Fine-Tuning](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/FineTuning/FT-03-Supervised-FineTuning-SFT-Python.ipynb)

**Références** : [NIST Privacy Framework](https://www.nist.gov/privacy-framework) · [Membership Inference Attacks](https://arxiv.org/abs/1610.05820) · [SDMetrics](https://docs.sdv.dev/sdmetrics/)

### L3 — Tuteur adaptatif avec mesure d'apprentissage

**Difficulté : 4/5** · Mots-clés : `education`, `tutoring`, `adaptation`, `learning-gain`

Adapter explications et exercices à un modèle explicite de maîtrise, sans se réduire à générer un quiz. Le verrou technique est la décision pédagogique et la mesure du progrès.

- **MVP** : domaine borné, diagnostic initial, trois niveaux d'aide, journal de maîtrise et évaluation pré/post.
- **Réussite** : gain d'apprentissage sur scénarios ou utilisateurs consentants, calibration du modèle et qualité des feedbacks.
- **Extensions** : oubli espacé, plusieurs stratégies, accessibilité.
- **Faisabilité** : contenu public et données synthétiques ; étude humaine facultative et consentie. Plan B : apprenants simulés.

**CoursIA** : [Educational Content Generation](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Image/04-Applications/04-1-Educational-Content-Generation.ipynb) · [NotebookMaker](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/SemanticKernel/10-SemanticKernel-NotebookMaker.ipynb)

**Références** : [Knowledge Tracing](https://dl.acm.org/doi/10.5555/1161135.1161179) · [UNESCO guidance for generative AI in education](https://unesdoc.unesco.org/ark:/48223/pf0000386693) · [Bloom's taxonomy](https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/)

### BSI-01 — Un sous-titre doit aussi se lire à temps

**Difficulté : 3/5 · audio, segmentation, accessibilité.** À transcription fixée, comment découper la phrase et sélectionner une reformulation assez courte pour rester lisible sans perdre une négation ? Il ne s’agit pas de reconnaître qui parle.

- **MVP** : enregistrer dix phrases fictives, fixer la transcription de référence, comparer découpage à longueur fixe et reformulation contrainte ; exporter en WebVTT.
- **Réussite** : mesurer proportion de segments dépassant le seuil de caractères/seconde choisi, noms et négations préservés, chevauchements temporels. Faire noter en aveugle cinq paires ; rendre un contre-exemple.
- **Extension** : tester débit lent et rapide sur la même phrase. **Plan B** : employer des transcriptions et horodatages préparés, sans GPU.
- **CoursIA** : [Whisper local](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Audio/01-Foundation/01-4-Whisper-Local.ipynb), [sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb). **Références** : [WebVTT](https://www.w3.org/TR/webvtt1/), [WAI : captions](https://www.w3.org/WAI/media/av/captions/), [Whisper](https://arxiv.org/abs/2212.04356).

### BSI-02 — Générer une question qui départage deux interprétations

**Difficulté : 3/5 · dialogue, clarification, décision.** Au lieu de répondre à une demande ambiguë, choisir la question qui élimine le plus de solutions possibles. Ce projet mesure la valeur de la question, pas l’éloquence de la réponse.

- **MVP** : créer 24 demandes fictives de réservation et une table de salles avec contraintes. Comparer une question fixe, une question proposée par modèle et un oracle qui connaît toutes les partitions possibles.
- **Réussite** : compter choix corrects après un échange, demandes qu’on pouvait résoudre sans question et questions inutiles. Conserver huit demandes pour le test final. Comparer aussi au hasard.
- **Extension** : intégrer le coût d’un second échange. **Plan B** : rejouer les propositions générées, versionnées en JSON, et évaluer localement.
- **CoursIA** : [consignes](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/02_PromptEngineering.ipynb), [appels de fonctions](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/04_Function_Calling.ipynb). **Références** : [Qulac](https://arxiv.org/abs/1907.06554), [JSON Schema](https://json-schema.org/), [information mutuelle](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mutual_info_score.html).
