Stroke Sense Project

Welcome to the Stroke Sense: AI Brain Stroke Detection System! 🧠✨This project uses deep learning to detect and classify strokes (ischemic and hemorrhagic) from MRI and CT scans with high accuracy.

🔗 Open in Google Colab

## 📥 Dataset Download

👉 [Brain Stroke MRI Images Dataset](https://www.kaggle.com/datasets/mitangshu11/brain-stroke-mri-images)


📂 Project Structure

stroke-sense-project/
├── notebook.ipynb                # Main Jupyter Notebook
├── Stroke_classification.zip     # Dataset (compressed)
├── Final_Report.pdf              # Project final report
└── README.md                     # Project description and instructions

🚀 How to Run

1️⃣ Open the notebook in Colab using the badge above.2️⃣ Run all cells to download, extract, and use the dataset.3️⃣ Follow the steps inside the notebook to train, evaluate, or test the model.

🛠️ Requirements

Python 3 (Colab pre-installed)

TensorFlow, Keras, OpenCV (Colab pre-installed)

🧪 Model Summary

The model uses EfficientNetB0 trained on a combined dataset of MRI and CT brain scans. It classifies images into:

No Stroke

Ischemic Stroke

Hemorrhagic Stroke

Accuracy achieved:

MRI Model: ~92%

CT Model: ~90%

📊 Results

Strong performance on validation sets.

Confusion matrices and metrics are included in the notebook.

Gradio interface included for interactive predictions.

📝 Contributors

Hisham Molawi (2141067)

Abdul Raheem Faden (2041533)

📄 License

This project is academic and shared for educational purposes.

✨ Ready to help hospitals make faster, more accurate stroke diagnoses! ✨
