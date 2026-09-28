# Exploratory Data Analysis and Visualization of Credit Card Fraud Data

## Overview

This project presents an Exploratory Data Analysis (EDA) and visualization workflow performed on a credit card transaction dataset.

The objective of the analysis is to understand the structure and characteristics of the transaction data, identify data-quality issues, examine the distribution of variables, investigate potential outliers, and explore patterns associated with fraudulent and legitimate transactions.

The analysis was implemented in Python using a Jupyter Notebook and includes data cleaning, statistical exploration, outlier analysis, and multiple visualizations designed to communicate important patterns in the dataset.

---

## Project Objectives

The main objectives of this project are to:

- Load and inspect the credit card transaction dataset.
- Understand the structure and characteristics of the data.
- Identify missing values and assess data completeness.
- Examine descriptive statistics for numerical variables.
- Detect and investigate potential outliers.
- Analyze the distribution of fraudulent and legitimate transactions.
- Explore relationships between important variables.
- Produce meaningful visualizations.
- Document important observations and insights from the analysis.

---

## Project Structure

The EDA folder contains the following files:

```
EDA/
│
├── README.md
│
├── [Dataset File]
│
└── [EDA Notebook].ipynb
```

# Retrieval-Augmented Generation (RAG) Pipeline

## Project Overview

This project implements a simple **Retrieval-Augmented Generation (RAG)** pipeline that allows a Large Language Model (LLM) to answer questions using information retrieved from a specific document.

The project demonstrates the complete RAG workflow:

1. Document ingestion
2. Text extraction
3. Text cleaning
4. Text chunking
5. Text embedding
6. Vector storage using FAISS
7. Similarity-based document retrieval
8. Context construction
9. LLM-based answer generation
10. Question-and-answer testing

The source document used in this project is:

**`History_and_Origin_of_Igbo_people_in_Nig.docx`**

The document is included in this project folder so that the RAG pipeline can be reproduced without needing to obtain the source document separately.

---

## Project Objectives

The main objectives of this project are to:

- Build a basic Retrieval-Augmented Generation system.
- Process a real-world `.docx` document.
- Divide the document into smaller text chunks.
- Convert text chunks into numerical embeddings.
- Store embeddings in a vector database.
- Retrieve the most relevant sections of the document for a user's question.
- Use an LLM to generate answers based on the retrieved information.
- Demonstrate the system using sample question-and-answer interactions.

---

## Project Structure

```text
RAG_Project/
│
├── History_and_Origin_of_Igbo_people_in_Nig.docx
│
├── RAG_Pipeline.ipynb
│
└── README.md
```
# YOLO Face Mask Detection

## Overview

This project implements a **fine-tuned YOLOv8 object detection model** for detecting face-mask usage in images.

The model identifies three classes:

* `with_mask`
* `without_mask`
* `mask_weared_incorrect`

The project was developed and executed using **Kaggle Notebook with GPU acceleration**.

## Project Objectives

* Prepare a face-mask detection dataset for YOLO.
* Convert Pascal VOC XML annotations to YOLO format.
* Fine-tune a pretrained YOLOv8 model.
* Evaluate the trained model using object-detection metrics.
* Generate sample predictions with bounding boxes.
* Discuss the model's performance and limitations.

## Technologies Used

* Python
* YOLOv8
* Ultralytics
* PyTorch
* OpenCV
* NumPy
* Matplotlib
* Kaggle Notebook

## Project File

The project folder contains:

```text
YOLO_Detection/
│
├── YOLO_Detection.ipynb
│
└── README.md
```

The **Jupyter Notebook (`.ipynb`)** contains the complete implementation, including dataset preparation, annotation conversion, model training, evaluation, and prediction.

The dataset, trained model, prediction outputs, training results, and other generated files are available in the project's Kaggle Notebook:

**Kaggle Notebook:**
https://www.kaggle.com/code/umehchimdiadi/yolo-detection

## How to Run

1. Open the Kaggle Notebook linked above.
2. Enable **GPU acceleration** in the Kaggle Notebook settings.
3. Add the required face-mask dataset.
4. Run the notebook cells from top to bottom.
5. The notebook will prepare the dataset, convert the annotations, train the YOLOv8 model, evaluate its performance, and generate sample predictions.

To run the notebook locally, install the required YOLO package:

```bash
pip install ultralytics
```

Then open `YOLO_Detection.ipynb` using Jupyter Notebook or JupyterLab.

## Model Evaluation

The trained model is evaluated using standard object-detection metrics, including:

* Precision
* Recall
* mAP@50
* mAP@50:95

Sample prediction images with bounding boxes are also generated to visually demonstrate the model's detection performance.

## Limitations

The model's performance may be affected by:

* Poor lighting or image quality
* Small or partially visible faces
* Occlusion
* Unusual camera angles
* Differences between the training dataset and real-world images
* Difficulty distinguishing correctly and incorrectly worn masks

## Conclusion

This project demonstrates how a pretrained YOLOv8 model can be fine-tuned for a specialized computer-vision task. The resulting model can detect and classify face-mask usage while providing bounding boxes around detected faces.

## Author

**Umeh Chimdiadi**
Computer Science, Veritas University Abuja

## License

This project is intended for educational and academic purposes. The dataset remains subject to its original license and terms of use.






