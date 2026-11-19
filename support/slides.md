---
theme: default
title: Générer ne suffit pas — le laboratoire Atlas
---

# Générer ne suffit pas

**Le laboratoire Atlas** · Bachelor BSI3 · séance 1

À la fin, vous aurez construit un test qui distingue une réponse plausible d’une réponse prouvée. Papier et crayon suffisent.

<!-- 09:00. Vote à main levée : quel résultat vous ferait changer d’avis sur la fiabilité d’un chatbot ? Garder deux propositions au tableau. -->

---

# Deux réponses ; une seule preuve ?

> « La prolongation est gratuite. »
>
> « Le texte ne donne pas le tarif. »

Sans la source, pouvez-vous départager ces phrases ? Quelle information demander avant de voter ?

<!-- 09:10. Ne pas montrer le règlement avant le vote. Distinguer absence de preuve et preuve de gratuité. -->

---

# Le règlement de l’atelier Atlas

> L’atelier ouvre les mardis et jeudis de 14 h à 18 h. Le prêt d’un capteur dure sept jours. Une prolongation doit être demandée avant l’échéance.

1. Puis-je venir jeudi à 17 h ?
2. Combien coûte la prolongation ?
3. Puisque l’atelier ouvre le samedi, à quelle heure ferme-t-il ?

**En binôme :** écrivez la réponse attendue *avant* de consulter le modèle.

<!-- 09:20. Correction : oui avec citation ; tarif non précisé ; rejeter la prémisse du samedi. Variante hors ligne : distribuer les deux réponses précédentes. -->

---

# Ce que prédit le modèle

« La prolongation est… » → gratuite ? possible ? soumise à autorisation ?

Le modèle produit une distribution sur les prochains **tokens**, pas un vote sur les faits. Un mot fréquent peut être le mauvais mot pour ce règlement.

**Expérience de pensée :** à température basse, une même erreur devient-elle plus rare, ou seulement plus reproductible ?

<!-- 09:35. Faire compléter la phrase par trois personnes. Une réponse stable n’est pas une preuve. Relier à la section température du chapitre VIII. -->

---

# Du texte récupéré à la réponse justifiée

**Question → recherche → passage → génération → contrôle de citation**

| Observation | Où chercher la panne ? |
|---|---|
| La bonne version ne figure pas parmi les passages | Recherche ou index |
| La bonne version est présente, mais la réponse dit « gratuit » | Génération ou consigne |
| La réponse est juste mais la citation parle des horaires | Vérification de la preuve |

<!-- 09:50. Enlever le passage pertinent, puis le réintroduire sans changer le prompt. Demander quel échec peut être réparé par un meilleur moteur de recherche. -->

---

# Un JSON valide peut mentir

```json
{"reponse":"0 €","citation":"avant l’échéance","statut":"prouvé"}
```

Le JSON est lisible. La citation existe. **Justifie-t-elle le tarif ?**

Proposez deux tests distincts : un test automatique de structure et un test de fidélité au texte. Que reste-t-il impossible à décider avec une simple recherche de chaîne ?

<!-- 10:05. Un parseur valide les champs ; une recherche confirme seulement la présence de la citation. Corrigé : statut inconnu, pas de valeur de tarif. Pause avant le travail en binômes. -->

---

# TP court · ne changez qu’une variable

1. Fixez quatre questions : fait explicite, information absente, prémisse fausse, paraphrase.
2. Comparez A : question seule ; B : question + règlement ; C : B + citation ou abstention.
3. Gardez le même modèle et les mêmes questions. Consignez **toutes** les sorties, même décevantes.
4. Échangez vos tests avec un autre binôme. Ajoutez son contre-exemple sans retoucher la méthode.

<!-- 10:30. Prévoir 35 minutes. Sans API : un binôme joue le système, l’autre contrôle les preuves. Ce jeu illustre le protocole, pas la performance d’un modèle. -->

---

# Quatre réussites sur cinq : qu’a-t-on mesuré ?

Exemple fictif : trois questions répondables et deux sans réponse. Le système répond juste à deux des trois et s’abstient correctement sur les deux autres.

- Exactitude globale : **4/5**.
- Questions répondables résolues : **2/3**.
- Abstentions justifiées sur questions impossibles : **2/2**.

Un système qui s’abstient toujours obtient **2/5**. Quel score masquerait le coût de ses refus ?

<!-- 11:05. Faire calculer avant de commenter. Comparer les dénominateurs. Cinq cas illustrent une mesure, ils ne permettent pas de généraliser. -->

---

# Quand deux règlements se contredisent

**Version de septembre** : sept jours. **Version de novembre** : dix jours à partir du 1er novembre.

« J’ai emprunté un capteur le 28 octobre. Combien de temps puis-je le garder ? »

Fixez d’abord la règle d’application. Si le texte ne précise pas le régime transitoire, quelle clarification faut-il demander ? Construisez un cas où la version la plus récente seule ne suffit pas.

<!-- 11:20. Ne pas imposer la date d’emprunt comme règle de droit. Demander un cas non ambigu, puis un cas indécidable ; comparer recherche par pertinence et filtrage par date. -->

---

# De l’expérience au projet

**À rendre au binôme voisin :** une proposition de cinq lignes.

1. Notre hypothèse précise…
2. Notre comparaison sans IA ou plus simple…
3. Le test que nous gardons secret pendant les réglages…
4. Le résultat qui nous ferait abandonner l’hypothèse…
5. Notre démonstration sans réseau…

<!-- 11:40. Tour rapide de relecture croisée ; garder dix minutes pour confronter deux protocoles et cinq pour le ticket de sortie. Fin 12:15. -->

---

# Pour poursuivre

[Chapitre VIII · mécanismes, images, agents et évaluation](https://github.com/jsboige/CoursIA/tree/main/slides/08-ia-generative) · [Notebook : grounding](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/RAG-et-Memoire-Semantique/01-Hands-On-Grounding.ipynb) · [Notebook : sorties structurées](https://github.com/jsboige/CoursIA/blob/main/MyIA.AI.Notebooks/GenAI/Texte/03_Structured_Outputs.ipynb)

**Ticket de sortie :** donnez une affirmation prouvée, une information inconnue et un test qui les distingue.
