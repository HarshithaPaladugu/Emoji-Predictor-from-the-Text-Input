# Emoji-Predictor-from-the-Text-Input
Taking the text as input, corresponding emoji is predicted
Based on your uploaded files (`Emotion_Detection_1.ipynb` and `New_Emoji_Predictor.py`), here's a recommended `README.md` for your GitHub repository:

---

## 🧠 Emotion and Emoji Prediction App

This project is a **Streamlit-based web application** that predicts the **emotion** conveyed in a sentence and displays the corresponding **emoticon**. It uses a **CNN-based deep learning model** trained on preprocessed text data and utilizes Keras, TensorFlow, and other NLP tools.

---

### 🚀 Demo

Enter a sentence like:

> "I just got a new puppy!"
> ...and the app will return:
> **Emotion:** joy
> **Emoticon:** 😊

---

### 📂 Project Structure

* `Emotion_Detection_1.ipynb` – Notebook for training and testing the CNN model on text data.
* `New_Emoji_Predictor.py` – Streamlit app that loads the model and tokenizer to predict emotions.
* `emotion_cnn_model.h5` – Pre-trained CNN model (path referenced in `.py`).
* `tokenizer.json` – Tokenizer used during training.
* `label_encoder.pkl` – Label encoder for decoding prediction labels.

---

### 🧪 Model Info

* Model: **CNN (Convolutional Neural Network)**
* Input: Tokenized & padded sequences of text
* Output: One of the 6 emotion classes

  * `joy` 😊
  * `sad` 😢
  * `anger` 😠
  * `fear` 😱
  * `love` ❤️
  * `surprise` 😲

---

### ⚙️ How to Run the App

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/emotion-emoji-predictor.git
   cd emotion-emoji-predictor
   ```

2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:

   ```bash
   streamlit run New_Emoji_Predictor.py
   ```

4. Upload or place the following files in the appropriate path (adjust the paths in `New_Emoji_Predictor.py` if needed):

   * `emotion_cnn_model.h5`
   * `tokenizer.json`
   * `label_encoder.pkl`

---

### 📦 Dependencies

* `tensorflow`
* `keras`
* `numpy`
* `streamlit`
* `pickle`
* `scikit-learn`

