## 311-translation

This repository tracks the development of a new translation model for service requests submitted through Boston's 311 system. 

For a deeper understanding of how we implemented the different models trained on local data to achieve better translations, please refer to the wiki: wiki link.

**Project Goals:**

* Create new, accurate bi-directional machine translation models for English-Spanish and English-Vietnamese, specifically focused on grievance data.
* Achieve improved translation accuracy.

**Training Progress:**

| Epoch | Accuracy | Loss | Val. Accuracy | Val. Loss |
|---|---|---|---|---|
| 1 | 0.7120 | 2.2110 | 0.8057 | 1.2232 |
| 2 | 0.8139 | 1.1869 | 0.8524 | 0.8881 |
| 3 | 0.8532 | 0.8974 | 0.8670 | 0.7856 |
| 4 | 0.8680 | 0.7832 | 0.8736 | 0.7394 |
| 5 | 0.8785 | 0.7047 | 0.8758 | 0.7126 |
| ... | ... | ... | ... | ... |
| 25 | 0.9296 | 0.4128 | 0.8860 | 0.8036 |
| 26 | 0.9305 | 0.4098 | 0.8860 | 0.8118 |
| 27 | 0.9317 | 0.4037 | 0.8859 | 0.8258 |
| 28 | 0.9327 | 0.3974 | 0.8862 | 0.8363 |
| 29 | 0.9331 | 0.3970 | 0.8852 | 0.8457 |
| 30 | 0.9346 | 0.3902 | 0.8868 | 0.8467 |
