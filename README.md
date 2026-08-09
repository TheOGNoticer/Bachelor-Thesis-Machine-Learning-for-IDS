# Machine-Learning-Verfahren in der Cybersecurity

Implementierung zur Bachelorarbeit von Eray Cayir
Hochschule Furtwangen University, 2026.

Vergleich von Decision Tree, Random Forest, VotingClassifier, einem
regelbasierten IDS und einem Hybrid-IDS auf dem CICIDS2017-Datensatz.
Inhaltliche Einordnung siehe schriftliche Arbeit.

## Datensatz

`dhoogla/cicids2017`, Version 3 (Parquet-Fassung)
Download erfolgt im Notebook über `kagglehub`, Kaggle-Zugangsdaten erforderlich.

## Umgebung

| Komponente         | Version                |
| ------------------ | ---------------------- |
| Python             | 3.12.13                |
| Betriebssystem     | Linux 6.6.122+, x86_64 |
| Logische CPU-Kerne | 2                      |
| Arbeitsspeicher    | 12,7 GB                |
| Plattform          | Google Colab           |
| NumPy              | 2.0.2                  |
| Pandas             | 2.2.2                  |
| Scikit-learn       | 1.6.1                  |
| Matplotlib         | 3.10.0                 |
| Seaborn            | 0.13.2                 |
| KaggleHub          | 1.0.2                  |

## Reproduzierbarkeit

`RANDOM_STATE = 42` für Sampling, Train-Test-Split und Modellinitialisierung.
Stichprobengröße 1.000.000 Flows.

Eine vollständige Reproduktion setzt dieselbe Datensatzversion, identische
Bibliotheksversionen und eine vergleichbare Ausführungsumgebung voraus.


