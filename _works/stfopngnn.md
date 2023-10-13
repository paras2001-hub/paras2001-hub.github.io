---
layout: post
title: Congestion Control GNN
id: stfopngnn
description: Spatiotemporal forecasting of traffic data using Graph Neural Networks
image1: assets/images/stfopngnn1.png
image2: assets/images/stfopngnn2.png
image3: assets/images/stfopngnn3.png
image4: assets/images/stfopngnn4.png
learn_more: https://github.com/Vishesh-Mittal/CongestionControl-GNN
---

- Generated the DIVE dataset by utilizing the TomTom API to gather traffic speed data from 40 nodes at regular 15‑min intervals.
- Conducted a comparative analysis to assess the performance of 4GNN models with time‑lags of 15, 30, and 45 mins on three datasets: PeMSD7, PeMSD8, and DIVE.
- Developed a prototype application (Omega Nav) that provides the most optimal route between the 20 selected nodes incorporating future traffic speed patterns predicted by the GNN models.
- Best Model: DCRNN, RMSE values: 5.231, 4.25, 2.59 km/hr for 15, 30, and 45 mins respectively.