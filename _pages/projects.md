---
permalink: /projects/
author_profile: true
---

Action Segmentation of Figure Skating Competition Videos {: style="font-size:18px; color:RoyalBlue" }  
**Topics**: action segmentation, deep learning, lstm, cnn, keras [[Github Link]](https://github.com/mayupei/figure-skating-action-segmentation)  
In figure skating judging, judges often need to replay a technical element to determine its difficulty and execution. Under the current system, a replay operator is responsible for marking the start and end time of each element as it's being performed, allowing for quick access to replays during the review process. This project aims to automate this process via action segmentation using a deep learning approach. I developed a two-stage LSTM-CNN framework that segments jumps and spins in competition videos using skeleton-based features. The model was trained and evaluated on 222 routines, achieving 0.92 frame-wise accuracy and 0.89 segment-level F1@50 via 5-fold cross-validation, outperforming a baseline LSTM model (0.88 / 0.31).
