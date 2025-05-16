# 🎧 Voice Analysis for Digital Forensics

## 📌 Project Title
**Detection of Emotional Variation Using Acoustic Features Using PRAAT and Voice Cloning Detection**

## 🎯 Objective

This project aims to analyze human speech under different emotional states (anger, sadness, fear, and neutrality) using acoustic features like pitch, intensity, formants, and spectrograms extracted through PRAAT software. Additionally, we compared real voices to AI-cloned voices (generated via Play.ht) to identify subtle yet important acoustic differences. This helps in identifying deepfakes and validating speaker authenticity in forensic audio investigations.

> ✅ **Goal**: Enhance digital forensics with accurate emotional and authenticity detection of speech data.

## 🛠️ Tools & Technologies

| Tool        | Purpose                                           |
|-------------|---------------------------------------------------|
| **PRAAT**   | Acoustic feature extraction (pitch, formants, etc.) |
| **Play.ht** | Generate synthetic (cloned) voice samples         |
| **GitHub**  | Version control and collaboration                 |

## 📋 Methodology

1. **Voice Data Collection**
   - 3 Real speakers recorded 5 types of emotional speech samples.
   - 1 AI-generated clone created for each speaker using Play.ht.

2. **Feature Extraction via PRAAT**
   - Features analyzed: Pitch, Intensity, RMS, Energy, Formants, Spectrograms.

3. **Comparison & Analysis**
   - Real vs AI voices
   - Emotion-wise comparison
   - Cross-speaker feature trends

4. **Visualization**
   - Graphs plotted for RMS, Intensity (dB), and Energy across speakers.
   - Comparative tables included in report.

## 📊 Results Summary

- **AI-cloned voices** showed exaggerated acoustic values (higher RMS, energy, and intensity), indicating potential markers for synthetic voice detection.
- **Sad and neutral tones** had consistently lower energy and intensity, which may be useful in psychological profiling.
- Feature distribution patterns were **speaker-specific**, indicating the need for personalized voice profiles in forensic use.

## 📁 Files in This Repository

| File / Folder                     | Description                                            |
|-----------------------------------|--------------------------------------------------------|
| `README.md`                       | This file (project overview)                           |
| `Voice_Analysis_Final_Report.pdf` | Detailed project report with analysis and tables       |
| `samples/`                        | Contains sample WAV files (real + synthetic)           |

## 🔮 Future Scope

- Train a classifier to predict emotional tone based on PRAAT-extracted features.
- Expand dataset with multilingual or stress-induced samples.
- Apply methods in law enforcement, threat detection, and forensic validation.

## 🙌 Credits

- **Author**: Arfa (arfa3)
- **Project Partners**: Maha, Nabiha

