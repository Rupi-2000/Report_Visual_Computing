## Empfohlene Kernliteratur

| Nr. | Quelle                                                                                                       | Verwenden für                                                                                                                                                                                                                                      |
| --: | ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | **Li et al. (2020): Object Detection in Optical Remote Sensing Images: A Survey and A New Benchmark**        | Überblick, Related Work, Remote-Sensing-spezifische Herausforderungen, DIOR-Datensatz. Die Arbeit ist sehr passend als Hauptquelle für den Einstieg und beschreibt DIOR mit 23,463 Bildern, 192,472 Instanzen und 20 Klassen. ([ScienceDirect][1]) |
|   2 | **Ding et al. (2021): Object Detection in Aerial Images: A Large-Scale Benchmark and Challenges**            | DOTA, Herausforderungen in Luftbildern, Scale/Orientation-Variation, Benchmarks und Evaluation. DOTA-v2.0 enthält 11,268 Bilder, 1,793,658 Instanzen und 18 Kategorien mit oriented bounding boxes. ([arXiv][2])                                   |
|   3 | **Lam et al. (2018): xView: Objects in Context in Overhead Imagery**                                         | xView-Datensatz, Satellitenbilder, kleine Objekte, viele Klassen, starke Scale-Variation. xView nutzt WorldView-3-Bilder mit 0.3 m GSD und enthält über 1 Million Objekte in 60 Klassen. ([arXiv][3])                                              |
|   4 | **Lin et al. (2017): Feature Pyramid Networks for Object Detection**                                         | Scale Variation und theoretische Lösung durch Multi-Scale-Features/FPN. Die Quelle erklärt, warum Feature Pyramids für Objekte unterschiedlicher Größe wichtig sind. ([arXiv][4])                                                                  |
|   5 | **Lin et al. (2017): Focal Loss for Dense Object Detection**                                                 | Background imbalance / foreground-background imbalance. Focal Loss wird hier als Lösung für das Problem vieler einfacher negativer Beispiele bei Dense Detection eingeführt. ([arXiv][5])                                                          |
|   6 | **Ding et al. (2018): Learning RoI Transformer for Detecting Oriented Objects in Aerial Images**             | Limitierungen von horizontal bounding boxes, Motivation für OBB, dense scenes, Key Model RoI Transformer. Die Arbeit argumentiert, dass horizontale RoIs bei gedrehten und dicht angeordneten Objekten zu Misalignment führen. ([arXiv][6])        |
|   7 | **Yang & Yan (2020): On the Arbitrary-Oriented Object Detection: Classification based Approaches Revisited** | Angle regression challenges, boundary discontinuity, Circular Smooth Label. Besonders gut für den Abschnitt zu 0°/180°-Periodizität und Winkel-Klassifikation. ([arXiv][7])                                                                        |
|   8 | **Xie et al. (2021): Oriented R-CNN for Object Detection**                                                   | Key Model Oriented R-CNN. Gut als moderneres Two-Stage-OBB-Modell, das oriented proposals effizienter erzeugt als frühere Methoden. ([arXiv][8])                                                                                                   |

## Wenn du nur 6 Quellen willst

Dann würde ich diese nehmen:

1. **Li et al. (2020)** – Overview + DIOR
2. **Ding et al. (2021)** – DOTA + Challenges + Evaluation
3. **Lam et al. (2018)** – xView
4. **Lin et al. (2017), FPN** – Scale Variation
5. **Lin et al. (2017), Focal Loss** – Background Imbalance
6. **Ding et al. (2018), RoI Transformer** – HBB vs. OBB + Oriented Detection

Das wäre die kompakteste Variante.
Für dein Kapitel mit **Angle Regression Challenges** würde ich aber wirklich mindestens **7 Quellen** nehmen und **Yang & Yan (2020)** noch ergänzen.

## Meine Empfehlung

Nimm **7 Quellen**:

1. Li et al. – Survey + DIOR
2. Ding et al. – DOTA Benchmark
3. Lam et al. – xView
4. Lin et al. – FPN
5. Lin et al. – Focal Loss
6. Ding et al. – RoI Transformer
7. Yang & Yan – CSL / Angle Regression

**Oriented R-CNN** kannst du dann im Text kurz als Weiterentwicklung erwähnen, aber nicht zwingend ausführlich zitieren. So bleibt die Literatur schlank und deckt trotzdem fast alles ab.

[1]: https://www.sciencedirect.com/science/article/pii/S0924271619302825?utm_source=chatgpt.com "Object detection in optical remote sensing images: A survey and a new benchmark - ScienceDirect"
[2]: https://arxiv.org/abs/2102.12219?utm_source=chatgpt.com "Object Detection in Aerial Images: A Large-Scale Benchmark and Challenges"
[3]: https://arxiv.org/abs/1802.07856?utm_source=chatgpt.com "xView: Objects in Context in Overhead Imagery"
[4]: https://arxiv.org/abs/1612.03144?utm_source=chatgpt.com "Feature Pyramid Networks for Object Detection"
[5]: https://arxiv.org/abs/1708.02002?utm_source=chatgpt.com "Focal Loss for Dense Object Detection"
[6]: https://arxiv.org/abs/1812.00155?utm_source=chatgpt.com "Learning RoI Transformer for Detecting Oriented Objects in Aerial Images"
[7]: https://arxiv.org/abs/2003.05597?utm_source=chatgpt.com "On the Arbitrary-Oriented Object Detection: Classification based Approaches Revisited"
[8]: https://arxiv.org/abs/2108.05699?utm_source=chatgpt.com "Oriented R-CNN for Object Detection"
