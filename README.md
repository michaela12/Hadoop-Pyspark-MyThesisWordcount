# Hadoop-Pyspark-MyThesisWordcount


Code written by Michaela Mohl michaela.mohl@t-online.de

The first goal was to count the word occurrences of my Master Thesis. The goal was to create intermediate files that have for each word a line like ("Thesis":2) meaning that the word "Thesis" occurred twice in the written version of my thesis.This was done with pyspark.

The final goal was to aggregate these results and to finally show the distribution of word frequencies in my thesis. As how many words were used only once, twice, thrice (...) and to plot these results. This was using the libraries pandas, seaborn, matplotlib and more.

Ersteller dieses Projektes war Michaela Mohl michaela.mohl@t-online.de

Zuerst wurden die Wort Häufigkeiten meiner Master Arbeit gezählt, dies wurde mit Hilfe von Pyspark umgesetzt. Das erste Stück Code erstellt Hilfsdateien die für jedes Wort eine Zeile die wie folgt aussah (“Thesis”, 2). Dies würde bedeuten, dass das Wort “Thesis” zwei mal in dem ganzen Text meiner Masterarbeit vor kommen würde.

Im zweiten Teil wurden dann diese Ergebnisse aggregiert. Das Ziel war darzustellen wie viele Wörter nur einmal, zweimal, dreimal (…) vorkommen. Dies wurde dann mit Seaborn in einem Graphen veranschaulicht.
