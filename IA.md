
# IA.md — TP4 RAG

## Informations générales

- Étudiante : Nada Marnissi
- Projet : TP4RagTestsMarnissi
- Sujet : RAG avec LangChain4j, Gemini et Tavily

## Utilisation de l'intelligence artificielle

J'ai utilisé ChatGPT comme assistant pour réaliser la première partie du TP4.

### 1. Configuration du projet

- Aide à la configuration Maven et des dépendances LangChain4j.
- Assistance pour résoudre les problèmes de compatibilité sur macOS Intel.
- Aide à la configuration des clés API Gemini et Tavily.

### 2. Réalisation des tests

- **Test 1 :** assistance pour la mise en place du RAG naïf et la lecture du fichier `rag.pdf`.
- **Test 2 :** aide à l'intégration du `CompressingQueryTransformer` et à la comparaison des réponses.
- **Test 3 :** ChatGPT m'a accompagnée dans la mise en place du routage entre deux documents PDF. Il m'a également aidée à créer le fichier `autre.pdf`, contenant des informations sur le système solaire et l'astronomie, afin de tester la sélection de la bonne source.
- **Test 4 :** assistance pour la création d'un routeur personnalisé.
- **Test 5 :** aide à l'intégration de Tavily et à l'amélioration du routage avec `LanguageModelQueryRouter`.

### 3. Débogage et vérification

- Analyse des erreurs de compilation et d'exécution.
- Identification des problèmes liés aux clés API.
- Analyse des réponses et des logs des différents tests.
- Vérification du routage entre le PDF et Tavily.

## Résultats obtenus

Les cinq tests ont été exécutés dans IntelliJ IDEA.

Pour le bonus du Test 5, les logs ont confirmé :
- La sélection du PDF pour une question sur le fine-tuning.
- La sélection de Tavily pour une question sur les actualités scientifiques.

## Responsabilité

J'ai utilisé les propositions de ChatGPT comme aide à la réalisation du TP. J'ai exécuté les tests et vérifié les résultats obtenus.
