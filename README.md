Currently runs various services for my homelab

It is currently in a proof of concept, with more automation coming later once I get charts set how I'd like

Hardware:
  - Thinkcenter Micro PC 8th Gen: Controlplane
  - Thinkcenter Micro PC 8th Gen: Worker
  - Thinkcenter Micro PC 10th Gen: Worker - Tagged for intel GPU
  - Intel NUC11: Worker - Tagged for intel GPU

Oddly enough my weaker machine is a controlplane node, mainly because I disagree with scheduling on the control plane, and I want to utilize the GPU for streaming
