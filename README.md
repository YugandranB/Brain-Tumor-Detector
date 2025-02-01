# 🧠 Brain Tumor Detection using VGG16 CNN with Data Augmentation

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.4-orange.svg)](https://www.tensorflow.org/)

🚀 *A deep learning-based approach for detecting brain tumors from MRI scans using VGG16 and data augmentation techniques.*

📄 *Published in IEEE:* [Brain Tumor Detection Using VGG16 CNN with Data Augmentation](https://ieeexplore.ieee.org/abstract/document/10698772)

---
## ✨ Features
✅ *Deep Learning for MRI Classification* using CNNs  
✅ *Pre-trained Models*: VGG16, EfficientNetB0, MobileNetV2, DenseNet121  
✅ *Data Augmentation*: Enhances training with rotation, flipping & zooming  
✅ *Simple Deployment*: Ready-to-use scripts for training & inference  

---
## 📂 Dataset
- *Source:* [Kaggle - Brain MRI Images](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)
- *Size:* 6,532 images (after augmentation)
- *Classes:* Tumor 🟥 | No Tumor 🟩

---
## 🛠 Installation
bash
# Clone this repository
git clone https://github.com/yourgithubusername/brain-tumor-detection.git
cd brain-tumor-detection

# Install dependencies
pip install -r requirements.txt



## Sample Detection Results

- **✅ Positive Detection (Tumor)**  
  Sample Image: [Positive Tumor Sample](https://drive.google.com/file/d/1SiTb7Oo0mHFV69iQTxxutTRG-fXRIzVX/view?usp=sharing) 

- **❌ Negative Detection (No Tumor)**  
  Sample Image: [Negative Tumor Sample](https://drive.google.com/file/d/1J4_V-yH9lqAxhVODWF1HKBP9gTvENVB7/view?usp=sharing) 



---
## 🎯 Usage
### 🔍 Training the Model
bash
python train.py


### 📊 Evaluating the Model
bash
python evaluate.py


### 🏷 Making Predictions
bash
python predict.py --image path/to/image.jpg


---
## 📈 Model Performance
| Model         | Accuracy | Precision | Recall | F1 Score |
|--------------|----------|------------|--------|---------|
| *VGG16*       | 🏆 *97.0%*    | 0.988      | 0.964  | 0.976   |
| EfficientNetB0 | 95.8% | 0.970      | 0.964  | 0.967   |
| MobileNetV2 | 95.1%    | 0.975      | 0.946  | 0.960   |
| DenseNet121 | 94.3%    | 0.987      | 0.922  | 0.954   |

---
## 👨‍💻 Contributors
- *P. Sri Sathwik*  
- *Yugandran B.*  
- *Om Bandyopadhyay*  
- *B. Prakash*  
- *Selvanayaki Kolandapalayam Shanmugam*

---
## 📜 Citation
If you use this work, please cite:
bibtex
@article{Sathwik2024BrainTumor,
  author    = {P. Sri Sathwik, Yugandran B., Om Bandyopadhyay, B. Prakash, Selvanayaki Kolandapalayam Shanmugam},
  title     = {Brain Tumor Detection using VGG16 CNN with Data Augmentation},
  journal   = {IEEE},
  year      = {2024},
  doi       = {10.1109/NMITCON.2024.10698772}
}


---
## 📜 License
📖 This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).


