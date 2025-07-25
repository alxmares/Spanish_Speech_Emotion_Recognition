# Spanish Speech Emotion Recognition (SER)

[Main Page 🔗](https://alxmares.github.io/HUB_Spanish_SER_HCI/)

## Part 1: [Advancing Spanish SER: A Comprehensive Benchmark of Pre-Trained Models](https://www.mdpi.com/2076-3417/15/8/4340)

This repository is part of a broader research initiative in affective computing, focused on advancing **SER** technologies in the Spanish language. Our research, as presented in the MDPI article [“Multitask Learning for Spanish Speech Emotion Recognition” (MDPI, 2024)](https://www.mdpi.com/2076-3417/15/8/4340), explores the development of robust and generalizable models, with this main contributions:

 * First comprehensive benchmarking of PTMs for Spanish SER, covering six diverse databases
 * Robust evaluation combining LOSO with layer-wise feature extraction
 * **Superpassing the Spanish SER's State-of-the-Art**

Our main results are sumarized in these tables and images:

<img src="https://alxmares.github.io/Spanish_Speech_Emotion_Recognition/assets/ser_results_summary.png" alt="Alt text" title="Title" height="300"/>

<img src="https://alxmares.github.io/Spanish_Speech_Emotion_Recognition/assets/mean_f1_by_layer.png" alt="Alt text" title="Title" height="300"/>

<img src="https://alxmares.github.io/Spanish_Speech_Emotion_Recognition/assets/mean_f1_by_ptm_loso.png" alt="Alt text" title="Title" height="300"/>


---

## Part 2: Multitask Learning

This work introduces the first MTL approach for Spanish SER, trained on six diverse corpora. Using a frozen Wav2Vec2 XLSR encoder and an MLP classifier, the proposed system surpasses the single-task baseline by 2.37 WF1 points, reaching **90.56%** in emotion classification, while also achieving near-perfect scores in speaker profiling (**99.39%**) and regional accent detection (**99.91%**). 

Notably, this performance was obtained **without any data augmentation or resampling**, demonstrating the intrinsic benefits of **multitask regularization**. The system adheres to **rigorous and reproducible evaluation protocols**, including **weighted F1, Recall and Precision metrics** and **cross-corpus validation** — addressing key methodological gaps in prior Spanish SER studies.


<img src="https://alxmares.github.io/Spanish_Speech_Emotion_Recognition/assets/WF1_tesis.png" alt="Alt text" title="Title" height="300"/>

---
