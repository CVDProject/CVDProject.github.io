---
title: Logica Proposizionale
categories: [Logica]
tags: [Logica]
math: true
hybrid: true

---

Come suggerisce il nome, la logica proposizionale è una branca della logica matematica che studia le relazioni logiche tra proposizioni (o affermazioni, enunciati, asserzioni) prese nel loro insieme e connesse tramite connettivi logici.

Nella logica proposizionale un enunciato (o proposizione) è rappresentato da una lettera, il cui rapporto con altri enunciati è definito tramite un insieme di simboli (o connettivi). L'affermazione è descritta dal suo valore di verità che è vero o falso.

## Proposizioni

Una proposizione è un'affermazione per cui può essere stabilito, senza ambiguità, se sia vera o falsa. Ad esempio, una proposizione potrebbe essere:

$\texttt{7 è dispari.}$

Nella logica proposizionale, questa affermazione è presa nella sua interezza, solitamente rappresentata da un simbolo, e ci preoccupiamo solo di sapere se è vera o falsa, non dei singoli termini nell'affermazione.

Per convenzione, una proposizione è rappresentata da una lettera maiuscola, tipicamente in grassetto. Ad esempio, la proposizione enunciata prima potrebbe essere rappresentata dalla lettera $\mathbf{A}$; in tal caso, si scrive:

$\mathbf{A}:\texttt{ 7 è dispari.}$

Si dice valore di verità di una proposizione $\textbf{P}$ il valore "vero" o "falso", a seconda che $\textbf{P}$ sia rispettivamente vera o falsa.

Ad esempio, il valore di verità di $\textbf{A}$ è "vero".

## Connettivi logici e tabelle di verità

Nella logica proposizionale, le relazioni tra proposizioni sono espresse da connettivi.

Un connettivo $c$ associa a due proposizioni $\textbf{P}$ e $\textbf{Q}$ una terza proposizione, denotata con $\textbf{P} \; c \; \textbf{Q}$, il cui valore di verità dipende dai valori di $\textbf{P}$ e $\textbf{Q}$.

I connettivi principali sono riportati di seguito:

$\begin{array}{|c|c|}
\hline
\textbf{Connettivo} & \textbf{Simbolo} \\\\\
\hline
   \textsf{Congiunzione} & \wedge \\\\\
\hline
   \textsf{Disgiunzione} & \vee \\\\\
\hline
   \textsf{Condizionale} & \rightarrow \\\\\
\hline
   \textsf{Biondizionale} & \leftrightarrow \\\\\
\hline
\end{array}$

Un quarto connettivo, detto negazione e indicato con $\neg$, opera su una sola proposizione $\textbf{P}$; la proposizione risultante si denota con $\neg\textbf{P}$, con $\not \textbf{P}$ o con $\overline{\textbf{P}}$.

Per mostrare come agisce un dato connettivo sulle proposizioni, viene utilizzata una tabella di verità.

La tabella di verità è uno strumento che permette di visualizzare come agisce un connettivo sulle proposizioni in base ai loro valori di verità. Un valore di "vero" è rappresentato da un "1", mentre un valore di "falso" è rappresentato da uno "0".

### Negazione
Data una proposizione $\textbf{P}$, la sua negazione $\overline{\textbf{P}}$ si pronuncia "non $\textbf{P}$" oppure "$\textbf{P}$ negato", e ha per definizione il valore di verità opposto a quello di $\textbf{P}$; la tabella di verità associata alla negazione è allora: 

$\begin{array}{|c|c|}
\hline
\textbf{P} & \overline{\textbf{P}} \\\\\
\hline
   0 & 1 \\\\\
\hline
   1 & 0 \\\\\
\hline
\end{array}$

### Congiunzione
Date due proposizioni $\textbf{P}$ e $\textbf{Q}$, la loro congiunzione $\textbf{P} \wedge \textbf{Q}$ si pronuncia "$\textbf{P}$ e $\textbf{Q}$", ed è per definizione vera quando entrambe $\textbf{P}$ e $\textbf{Q}$ sono vere, e falsa altrimenti; la tabella di verità associata alla negazione è allora: 

$\begin{array}{|c|c|c|}
\hline
\textbf{P} & \textbf{Q} & \textbf{P} \wedge \textbf{Q} \\\\\
\hline
   0 & 0 & 0 \\\\\
\hline
   0 & 1 & 0 \\\\\
\hline
   1 & 0 & 0 \\\\\
\hline
   1 & 1 & 1 \\\\\
\hline
\end{array}$

### Disgiunzione
Date due proposizioni $\textbf{P}$ e $\textbf{Q}$, la loro disgiunzione $\textbf{P} \vee \textbf{Q}$ si pronuncia "$\textbf{P}$ oppure $\textbf{Q}$", ed è per definizione vera quando almeno una tra $\textbf{P}$ e $\textbf{Q}$ è vera, e falsa altrimenti; la tabella di verità associata alla negazione è allora: 

$\begin{array}{|c|c|c|}
\hline
\textbf{P} & \textbf{Q} & \textbf{P} \vee \textbf{Q} \\\\\
\hline
   0 & 0 & 0 \\\\\
\hline
   0 & 1 & 1 \\\\\
\hline
   1 & 0 & 1 \\\\\
\hline
   1 & 1 & 1 \\\\\
\hline
\end{array}$

### Condizionale
Date due proposizioni $\textbf{P}$ e $\textbf{Q}$, il condizionale $\textbf{P} \rightarrow \textbf{Q}$ si pronuncia "$\textbf{P}$ implica $\textbf{Q}$" oppure "se $\textbf{P}$ allora $\textbf{Q}$", ed è per definizione falso quando $\textbf{P}$ è vera e $\textbf{Q}$ è falsa, e vero altrimenti; la tabella di verità associata alla negazione è allora: 

$\begin{array}{|c|c|c|}
\hline
\textbf{P} & \textbf{Q} & \textbf{P} \rightarrow \textbf{Q} \\\\\
\hline
   0 & 0 & 1 \\\\\
\hline
   0 & 1 & 1 \\\\\
\hline
   1 & 0 & 0 \\\\\
\hline
   1 & 1 & 1 \\\\\
\hline
\end{array}$

### Bicondizionale
Date due proposizioni $\textbf{P}$ e $\textbf{Q}$, il bicondizionale $\textbf{P} \leftrightarrow \textbf{Q}$ si pronuncia "$\textbf{P}$ se e solo se $\textbf{Q}$", ed è per definizione vero quando $\textbf{P}$ e $\textbf{Q}$ hanno lo stesso valore di verità, e falso altrimenti; la tabella di verità associata alla negazione è allora: 

$\begin{array}{|c|c|c|}
\hline
\textbf{P} & \textbf{Q} & \textbf{P} \leftrightarrow \textbf{Q} \\\\\
\hline
   0 & 0 & 1 \\\\\
\hline
   0 & 1 & 0 \\\\\
\hline
   1 & 0 & 0 \\\\\
\hline
   1 & 1 & 1 \\\\\
\hline
\end{array}$

## Proposizioni atomiche ben definite

Finora abbiamo discusso le seguenti semplici proposizioni:

$\mathbf{P}$

$\overline{\mathbf{P}}$

$\mathbf{P} \wedge \mathbf{Q}$

$\mathbf{P} \vee \mathbf{Q}$

$\mathbf{P} \rightarrow \mathbf{Q}$

$\mathbf{P} \leftrightarrow \mathbf{Q}$

Tuttavia, possiamo combinare queste per costruire proposizioni molto più complesse, come ad esempio:

$\overline{( \mathbf{P} \wedge \mathbf{Q} )\vee \mathbf{R}}$.

Una proposizione $\textbf{P}$ si dice atomica quando non è connettivo di alcuna coppia di proposizioni.

Ad esempio, la proposizione $\textbf{P}:\texttt{7 è minore di 10 e 7 è positivo} \,$  non è atomica, in quanto è congiunzione delle proposizioni $\textbf{Q}:\texttt{7 è minore di 10} \,$ e $\, \textbf{R}:\texttt{7 è positivo}$, che invece sono atomiche. 

Una proposizione composta si dice formula ben formata quando è costruita con il seguente insieme di regole:

1. Qualsiasi proposizione atomica è considerata una formula ben formata.
2. Se $\mathbf{F}$ è una formula ben formata, anche $\overline{\mathbf{F}}$ è una formula ben formata.
3. Se $\mathbf{F}$ e $\mathbf{G}$ sono formule ben formate, anche $\mathbf{F} \wedge \mathbf{G}$ è una formula ben formata.
4. Se $\mathbf{F}$ e $\mathbf{G}$ sono formule ben formate, anche $\mathbf{F} \vee \mathbf{G}$ è una formula ben formata.
5. Se $\mathbf{F}$ e $\mathbf{G}$ sono formule ben formate, anche $\mathbf{F} \rightarrow \mathbf{G}$ è una formula ben formata.
6. Se $\mathbf{F}$ e $\mathbf{G}$ sono formule ben formate, anche $\mathbf{F} \leftrightarrow \mathbf{G}$ è una formula ben formata.

## Tautologia