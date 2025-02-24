
---
## **Overview**  
This project explores metaphor detection in text using NLP techniques and deep learning models. The approach involves preprocessing text, extracting key phrases, and training models to classify sentences as metaphorical or literal.  

## **Dataset**  
- Collected and processed a dataset containing sentences with and without metaphors.  
- Applied lemmatization and keyword extraction for feature engineering.  

---

### **Setup**  

**Install dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```

**Download the required NLP models:**  
   ```bash
   python -m spacy download en_core_web_sm
   ```

To train the model, run:  
```bash
python train.py
```

To evaluate on test data:  
```bash
python test.py
```

## **Methodology**  
1. **Data Preprocessing**: Tokenization, lemmatization, and feature extraction.  
2. **Embedding Generation**: Used BERT embeddings for text representation.  
3. **Model Training**:  
   - LSTM-based neural network trained for classification.  
   - Fine-tuned hyperparameters for optimal performance.  
4. **Evaluation**: Classification report with accuracy and other metrics.  

## **Results**  
- Achieved high accuracy in detecting metaphorical vs. literal sentences.  
- Improved interpretability by analyzing attention weights.  

## **Future Improvements**  
- Expand dataset for better generalization.  
- Experiment with transformer-based models like GPT.  

---