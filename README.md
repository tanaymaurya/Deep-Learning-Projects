# Deep-Learning-Projects
# Multi-Modal Deep Learning Experiments

This repository presents a collection of deep learning projects targeting classification tasks across different data modalities: tabular data, images, and audio. It is designed for learners and practitioners looking to gain hands-on experience with PyTorch and explore the differences and similarities in processing and modeling diverse data types.

---

## 📁 Repository Structure

| Notebook | Description |
|----------|-------------|
| `Ex_1_Tabular_Classification.ipynb` | Classifies rice types using a feedforward neural network on tabular data. Includes preprocessing, custom dataset class, and performance evaluation. |
| `Ex_2_Image_Classification.ipynb` | Builds a Convolutional Neural Network (CNN) from scratch for image classification. Demonstrates data loading, training loop, and accuracy tracking. |
| `Ex_3_Image_Classification_Pretrained.ipynb` | Applies transfer learning with a pretrained ResNet model. Shows how to fine-tune on a new image dataset efficiently. |
| `Ex_4_Audio_Classification.ipynb` | Uses audio signal processing (e.g., spectrograms or MFCCs) and trains a neural network for classifying audio samples. |

---

## 🧠 Concepts Covered

- Supervised classification using PyTorch  
- Data preprocessing techniques for tabular, image, and audio formats  
- Custom PyTorch `Dataset` and `DataLoader` usage  
- Building and training neural networks (from scratch and pretrained)  
- Use of `torchvision` and `torchaudio` libraries  
- Evaluation using accuracy and other metrics  

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/multi-modal-deep-learning-experiments.git
cd multi-modal-deep-learning-experiments
```
2. Install Required Packages
It's recommended to use a virtual environment:

```bash
pip install -r requirements.txt
```
If requirements.txt is missing, you can manually install the packages:

```bash
pip install torch torchvision torchaudio scikit-learn matplotlib pandas opendatasets
```

💻 Running the Notebooks
You can run the notebooks using any of the following:

Jupyter Notebook / JupyterLab

VS Code with Python and Jupyter extensions

Google Colab (for cloud execution with GPU support)


⚠️ Make sure to adjust file paths and dataset locations as needed when not using Colab.


🔬 Example Use Cases
Benchmarking different neural network architectures

Comparing performance across different input modalities

Establishing a baseline for multimodal AI projects

📚 Recommended Knowledge
Python programming

Basics of neural networks

Familiarity with PyTorch (or eagerness to learn through practical examples)

