---
permalink: /projects/
author_profile: true
---

<span style="font-size:19px; color:RoyalBlue"><strong>Action Segmentation of Figure Skating Competition Videos</strong></span>  
**Topics: action segmentation, deep learning, lstm, cnn, keras**  
**Link:** [[GitHub]](https://github.com/mayupei/figure-skating-action-segmentation)  
In figure skating judging, judges often need to replay a technical element to determine its difficulty and execution. Under the current system, a replay operator is responsible for marking the start and end time of each element as it is being performed, allowing for quick access to replays during the review process. This project aims to automate this process via action segmentation using a deep learning approach. I developed a two-stage LSTM-CNN framework that segments jumps and spins in competition videos using skeleton-based features. The model was trained and evaluated on 222 routines, achieving 0.92 frame-wise accuracy and 0.89 segment-level F1@50 via 5-fold cross-validation, significantly outperforming a baseline LSTM model (0.31 segment-level F1@50).

<span style="font-size:19px; color:RoyalBlue"><strong>Investigating Bloc Judging in Figure Skating Competitions</strong></span>  
**Topics: web scraping, pdf scraping, biclustering, network analysis, econometrics**  
**Links:** [[Data Collection]](https://github.com/mayupei/isu-figure-skating-competitions-web-scraper); [[Analysis]](https://github.com/mayupei/figure-skating-bloc-judging)  
Bloc judging in figure skating refers to a pattern in which judges from a group of countries ("blocs") systematically assign higher scores to athletes from the same group and lower scores to athletes from outside the group. This project quantifies the extent of bloc judging and identifies the composition of judging blocs using biclustering, an unsupervised machine learning approach. I developed a data engineering pipeline to scrape and extract competition results from the International Skating Union's official website, producing a final dataset of approximately 1.5 million observations. I then constructed a skater-country–by–judge-country matrix that captures cross-country scoring tendencies using fixed-effects econometric models and network analysis. Applying spectral biclustering to this matrix reveals clear bloc-judging structures. Compared with skaters from the same bloc (excluding the judge’s home country), judges assign scores 0.11 standard deviations lower to skaters outside their blocs.