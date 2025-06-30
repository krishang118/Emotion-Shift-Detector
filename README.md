# Emotion-Shift Detector using BERT
 
A robust emotion analysis system that leverages BERT transformers to detect and analyze emotional transitions in conversations. Built with support for the GoEmotions dataset, the system provides real-time emotion detection and comprehensive conversation analysis.

## Features

- BERT-based Emotion Classification: Fine-tuned BERT model for accurate emotion detection across 28 categories
- Emotion-Shift Detection: Automatic identification of significant emotional transitions in conversations
- Real-time Analysis: Process new messages as they arrive with immediate emotion classification
- Conversation Chunking: Flexible text processing with message-based or sentence-based chunking
- MPS/GPU Support: Automatic detection and optimization for MPS (Apple Silicon), CUDA (NVIDIA GPU), and CPU with seamless fallback
- Elaborate Visualizations: Timeline plots, distribution charts, and emotion transition matrices
- Flexible Preprocessing: Supports both single-label and multi-label emotion approaches

### Supported Emotions

The model recognizes 28 distinct emotions from the GoEmotions dataset:
- **Positive**: admiration, amusement, approval, caring, excitement, gratitude, joy, love, optimism, pride, relief
- **Negative**: anger, annoyance, disappointment, disapproval, disgust, embarrassment, fear, grief, nervousness, remorse, sadness
- **Ambiguous**: confusion, curiosity, desire, realization, surprise
- **Neutral**: neutral

## How to Run

1. Make sure you have Python 3.8+ installed.
2. Install the required dependencies:
```bash
pip install pandas numpy torch transformers scikit-learn matplotlib seaborn openpyxl
```
3. Clone this repository on your local machine.
4. The Dataset:
   - This project uses the GoEmotions dataset, which is already provided in the repository in the form of three csv files: `goemotions_1.csv`, `goemotions_2.csv`, `goemotions_3.csv`.
   - Alternatively (if required), you may download it yourself from [Kaggle](https://www.kaggle.com/datasets/debarshichanda/goemotions).
5. Open and run the `Emotion Detector.ipynb` Jupyter Notebook.

## Contributing

Contributions are welcome!

## License

Distributed under the MIT License.  
