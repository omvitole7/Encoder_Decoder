# Encoder_Decoder

# 📰 News Headline Generation using GRU

This project demonstrates a deep learning approach to automatically generate news headlines based on article content using a GRU-based Recurrent Neural Network. The model is trained to predict the first word of the headline given the body of the news article.

---

## 📂 Dataset

- The dataset contains two columns:
  - content_text: Body of the news article
  - generated_headline: Corresponding headline

- File Used: news_headline_generator.csv

---

## 🔧 Project Structure

- Text Preprocessing: Clean text, remove punctuation, lowercase conversion
- Tokenization: Convert text into integer sequences using Keras Tokenizer
- Padding: Pad sequences to uniform length
- Model Architecture:
  - Embedding Layer
  - GRU Layer (256 units)
  - Dense Output Layer (Softmax)
- Training: Model trained using sparse_categorical_crossentropy loss and Adam optimizer
- Prediction: Given article content, predict the most likely first word of the headline

---

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- TensorFlow / Keras
- Regular Expressions for cleaning
- Scikit-learn for train/test split

---

## 🚀 How to Run

1. Clone this repository or download the .ipynb notebook.
2. Install required libraries:
   bash
   pip install tensorflow pandas numpy scikit-learn
`

3. Load the dataset (news_headline_generator.csv)
4. Run the notebook cells sequentially.
5. Interact with the user input loop to test headline generation.

---

## 🧪 Sample Input/Output

Input:


content_text: "the government announced a new plan to tackle climate change"


Model Output:


📰 Generated Headline: "government"


---

## 🔮 Limitations

* The model only predicts the first word of the headline.
* More advanced architectures like Seq2Seq or Transformers can be used for full headline generation.

---

## 📌 Future Improvements

* Implement full sequence-to-sequence decoding
* Use attention mechanism for better performance
* Expand dataset for better generalization
* Deploy as a web or API-based app

---

## 👤 Author

Om Vitole
Mechanical engineering Student
MIT Academy of Engineering, Pune

---

## 📄 License

This project is for academic use only.
