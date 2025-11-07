🧠 Comparative Study Between an Unsupervised Autoencoder and a Supervised ResNet-50 Classifier for Detection of Brain Tumours

📘 Overview
This project presents a comparative study between two deep learning approaches — an unsupervised Autoencoder and a supervised ResNet-50 classifier — for detecting brain tumours from MRI images.
The objective is to analyze performance differences between unsupervised and supervised models in terms of reconstruction accuracy, classification metrics, and detection capability.

📂 Project Structure
├── brain_tumor_comparative_study.ipynb   # Main code file (Autoencoder & ResNet-50 implementation)
├── Brain_Tumor_Report.pdf                # Project report with methodology and results
└── README.md                             # Project documentation

⚙️ Requirements
Install the following Python libraries before running the notebook:
pip install numpy pandas matplotlib tensorflow keras opencv-python scikit-learn

🚀 How to Run
Open the Jupyter notebook brain_tumor_comparative_study.ipynb.
Run all cells sequentially to train both models (Autoencoder and ResNet-50).
Compare evaluation metrics and visualization outputs for performance analysis.

🧬 Model Summary
| Model           | Type         | Purpose                                                      | Framework          |
| --------------- | ------------ | ------------------------------------------------------------ | ------------------ |
| **Autoencoder** | Unsupervised | Learns to reconstruct normal MRI images and detect anomalies | TensorFlow / Keras |
| **ResNet-50**   | Supervised   | Classifies MRI images as tumor / non-tumor                   | TensorFlow / Keras |

🧾 Files Description
| File                                  | Description                                                                  |
| ------------------------------------- | ---------------------------------------------------------------------------- |
| `brain_tumor_comparative_study.ipynb` | Code for both Autoencoder and ResNet-50 models                               |
| `Brain_Tumor_Report.pdf`              | Detailed research report including methodology, experiments, and conclusions |
| `README.md`                           | Project documentation (this file)           📄 Note

📄 Note
All materials in this repository were authored by Swetha Sathees as part of a student academic support project.
The report is included for demonstration of technical documentation and presentation skills.                                 |


