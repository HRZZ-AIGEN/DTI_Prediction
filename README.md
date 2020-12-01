# Drug-Target Interaction Prediction

create_data.py - racunanje reprezentacija molekula i proteina te oblikovanje podataka u pytorch formatu
utils.py - definiranje DataLoadera za prosljedjivanje podataka u manjim skupovima prilikom treniranja
training.py  - treniranje neuronskih mreza baziranim na graf reprezentacijama za molekule
models - sadrzi GCN, GINConv, GAT, GAT-GCN modele

Navedena metodologija i podjela podataka baziraju se na DeepDTA [1] i GraphDTA [2] pristupu, radi lakse reproducibilnosti.

[1] Öztürk, H., Özgür, A., Ozkirimli, E., 2018. DeepDTA: deep drug–target binding affinity prediction. Bioinformatics 34, i821–i829. https://doi.org/10.1093/bioinformatics/bty593
[2] Nguyen, Thin, Le, H., Quinn, T.P., Nguyen, Tri, Le, T.D., Venkatesh, S., n.d. GraphDTA: Predicting drug–target binding affinity with graph neural networks. Bioinformatics. https://doi.org/10.1093/bioinformatics/btaa921
