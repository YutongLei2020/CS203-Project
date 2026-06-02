# CS203-Project

## Notebook Descriptions

- `extract_window_features.ipynb`: Extracts fixed-window traffic features from raw PCAP files and saves the feature CSVs used by the classification and defense notebooks.
- `device_classification.ipynb`: Trains and evaluates a Random Forest classifier on extracted traffic-window features for same-day and cross-day IoT device identification.
- `feature_ablation.ipynb`: Compares device classification performance across feature groups to determine which traffic features contribute most to accuracy and macro-F1.
- `packet_signature_baseline.ipynb`: Builds a simple packet-sequence signature baseline that classifies devices using exact and prefix matches of direction-and-size packet patterns.
- `defense_simulation.ipynb`: Simulates lightweight traffic-shaping defenses, including packet padding and smoothing, to measure how they reduce IoT device classification performance.
