# guardrails-against-toxicity
Dieses Repository stellt den Code und die Dateien bereit, die im Rahmen meiner Projektarbeit mit dem Namen "Vergleich verschiedener modellbasierter Guardrail-Ansätze zur Bekämpfung toxischer Sprache in Transformer-basierten Large-Language-Modellen" verwendet werden.

-   'config' enthält die einzelnen nemoguardrails-Konfigurationen. Für jedes Modell wurde eine Konfiguration erstellt, um das Wechseln des LLMs während des Experiments zu erleichtern.
-   'rails' enthält die Spezifikation der Input- und Output-Rails in 'Colang'-Format.
-   'data' enthält die beiden verwendeten Sub-Datensätze (sind bereits formatiert und auf 200 samples verkleinert worden; hierfür wurde das Notebook 'formatting-datasets.ipynb' verwendet).
-   'evaluation-results' enthält die Excel-Tabelle mit den Resultaten der Experimente.
-   Das Experiment wurde in 'evaluation-nb.ipynb' durchgeführt. Für den Wechsel zwischen den einzelnen Guardrail-Modellen muss zu Beginn des Notebooks die entsprechende Zeile auf die gewünschte Konfiguration gesetzt werden (durch Angeben des Ordnerpfads). Ein Durchlauf des Notebooks entspricht einer Runde (für jedes der 4 LLMs werden je 4 Runden durchlaufen und nach jeder Runde die Ergebnisse manuell in die Excel eingetragen).
