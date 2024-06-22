\documentclass{article}
\usepackage{hyperref}

\title{Projet d'Étude : Sélection du Meilleur Modèle Prédictif pour un Contrat d'Assurance Auto}
\author{Paul Vidal \and Gabin Sengel}
\date{}

\begin{document}

\maketitle

\section*{Objectif du Projet}

L'objectif de ce projet est de sélectionner le meilleur modèle prédictif pour estimer l'intérêt des clients d'une assurance santé pour un nouveau contrat auto. Nous disposons d'une base de données comprenant des informations sur plus de 300 000 clients, incluant :

\begin{itemize}
    \item Âge
    \item Sexe
    \item Possession d'un permis de conduire
    \item Statut d'assurance actuelle
    \item Historique de sinistres
    \item Intérêt potentiel pour un contrat d'assurance auto
\end{itemize}

Le but est d'entraîner nos modèles prédictifs avec une partie des données et de les tester sur l'autre afin de sélectionner le modèle le plus performant.

\section*{Contenu du Dépôt}

\begin{itemize}
    \item \texttt{index.html} : Le fichier HTML du rendu fait avec Quarto, disponible au lien : \href{insérer lien}{insérer lien}.
    \item \texttt{code\_quarto} : Le code Quarto pour les slides.
    \item \texttt{rendu.pdf} : Le rendu PDF du projet.
    \item \texttt{code\_rmarkdown} : Le code RMarkdown utilisé pour générer le PDF.
\end{itemize}

\section*{Installation et Utilisation}

\begin{enumerate}
    \item Clonez le dépôt :
    \begin{verbatim}
    git clone [URL du dépôt]
    cd [nom du dépôt]
    \end{verbatim}
    \item Ouvrez et visualisez \texttt{index.html} pour voir le rendu des slides en ligne.
    \item Consultez le code Quarto et RMarkdown pour comprendre la méthodologie et les étapes du projet.
\end{enumerate}

\section*{Méthodologie}

\begin{enumerate}
    \item \textbf{Préparation des Données} :
    \begin{itemize}
        \item Chargement et nettoyage des données.
        \item Exploration et analyse descriptive des variables.
    \end{itemize}
    \item \textbf{Entraînement des Modèles} :
    \begin{itemize}
        \item Séparation des données en ensembles d'entraînement et de test.
        \item Entraînement de plusieurs modèles prédictifs (LDA, QDA, Logit, KNN, Decision Tree, Random Forest, Boosting).
    \end{itemize}
    \item \textbf{Évaluation des Modèles} :
    \begin{itemize}
        \item Utilisation de métriques de performance (Accuracy, Sensibilité, Précision, etc.) pour évaluer les modèles.
        \item Sélection du modèle le plus performant.
    \end{itemize}
\end{enumerate}

\section*{Résultats}

Le projet a permis d'identifier le modèle prédictif le plus adapté pour estimer l'intérêt des clients pour un nouveau contrat d'assurance auto, basé sur les critères de performance définis.

\section*{Contributeurs}

\begin{itemize}
    \item Paul Vidal
    \item Gabin Sengel
\end{itemize}

\section*{Licence}

Ce projet est sous licence [Nom de la Licence]. Voir le fichier \texttt{LICENSE} pour plus de détails.

\end{document}
