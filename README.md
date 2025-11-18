#📡 Complex-Valued Differential Autoencoder (CVDAE)
## Temporal CSI Compression for Massive MIMO Systems
CVDAE is a feedback-driven temporal CSI compression framework that operates natively in the complex domain, explicitly modeling amplitude–phase coupling and temporal continuity in wireless channels.

The model significantly reduces CSI feedback overhead while achieving state-of-the-art reconstruction accuracy, especially under high compression ratios and time-varying channels.

## 🌟 Key Features

- Complex-Valued Processing:
  Uses complex linear layers and complex tanh activation to preserve amplitude–phase relationships in CSI.

- Differential Learning:
  Encodes only the difference between consecutive CSI frames, leveraging strong temporal correlation.

- Memory-Based Architecture:
  Maintains encoder and decoder memories to track temporal evolution across CSI frames.

- Enhanced Robustness Across Mobility Conditions:
  Demonstrated superiority under UE speeds of 40 km/h, 100 km/h, and 360 km/h.

- Superior to Conventional Methods:
  Outperforms CsiNet, CRNet, and a baseline CVAE in both NMSE and cosine similarity metrics.
