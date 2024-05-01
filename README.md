# VADER Sentiment Analysis der Pressemitteilungen und Tweets der Hindu-nationalistischen Akteure zum Konflikt zwischen Meiteis und Kukis
Das ist mein Portfolio mit der Datenanalyse für die Bachelorarbeit in der Religionswissenschaft.
Die Forschungsfrage meiner Arbeit ist: Welche Argumentationsmuster benutzen Hindu-Nationalisten im Netz, um die Machtdynamiken im ethnischen Konflikt zwischen den Meiteis und Kukis in Manipur zu beeinflussen?

Die Sentimentanalyse ist nützlich für Wissenschaftler*innen, um verschiedene Probleme zu verstehen, die zwischen Menschen und Computern entstehen. VADER (Valence Aware Dictionary of sEntiment Reasoning) ist ein ,,simple rule-based model for general sentiment analysis” (Hutto/Gilbert 2014: 216). Sentimentanalyse oder ,,opinion mining” ist ein aktiver Teil der Forschung im Bereich Natural Language Processing. Hierbei geht es um die Analyse der Meinungen, Sentimente, Bewertungen, Emotionen durch computergestützte Bearbeitung des Texts. Eine beträchtliche Anzahl von Analysen stützt sich in hohem Maße auf ein zugrundeliegendes Stimmungslexikon (Sentiment Lexicon). Ein Sentiment Lexicon ist eine Liste lexikalischer Merkmale (z.B. Begriffe), die wegen der semantischen Orientierung entweder negativ oder positiv sein können (Hutto/Gilbert 2014: 218.).
VADER Sentiment Analysis könnte über Python 3  durchgeführt werden. Um Texte auszuwerten, werden die Scores berechnet. Der Compound Score wird durch Summierung der Valenzwerte jedes Wortes im Lexikon berechnet, entsprechend den Regeln angepasst und dann so normalisiert, dass er zwischen -1 (extrem negativ) und +1 (extrem positiv) liegt. Dies ist die nützlichste Metrik, wenn man ein einziges eindimensionales Maß der Stimmung für einen bestimmten Satz sucht. Die Bezeichnung "normalisierter, gewichteter Composite Score" ist zutreffend. Es gibt positive, negative und neutrale Scores. Bei positiven Stimmungen kann der Score höher oder gleich 0,05 sein. Negative Stimmungen liegen unter -0,05. Ein neutrales Sentiment könnte entweder über -0,05 oder unter 0,05 bewertet werden.

