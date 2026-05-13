# Self-Supervised-CNN-BiGRU-Attention-for-Multi-Label-Lung-Sound-Classification
 A two-stage deep learning framework for multi-label lung sound classification. It uses SimCLR self-supervised pretraining on the ICBHI 2017 dataset and fine-tunes a CNN–BiGRU–Attention model on HF Lung V1 to detect overlapping respiratory events such as wheeze, crackle, rhonchi, and stridor.

The work focuses on three main challenges in respiratory audio analysis: overlapping labels, strong class imbalance, and noisy recording conditions. To address these, it applies log-mel spectrogram preprocessing, strong spectrogram augmentations, Asymmetric Loss, and ensemble inference with per-class threshold calibration.

The proposed system achieves strong validation performance and improved ensemble results on HF Lung V1, showing better Macro-F1, Micro-F1, and CAS-F1 than single-model inference. The dissertation also emphasizes interpretability through attention weights and practical clinical relevance for respiratory disease monitoring.
