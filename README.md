# 🧔 VIP-Face-Recognition  
A deep learning project leveraging **Metric Learning** and **Triplet Loss** for robust face recognition across 31 celebrities.

---

## 🚀 Overview  
This project explores and compares advanced deep learning strategies for face recognition, focusing on **embedding-based models**. The main objectives are:

- 🎯 Train CNNs for direct identity classification  
- 🧬 Learn similarity-based embeddings using **Siamese Networks**  
- 🧲 Apply **Triplet Loss** with a multi-task objective for **state-of-the-art performance**

---

## 📦 Dataset  
The dataset is sourced from [Kaggle - Face Recognition Dataset](https://www.kaggle.com) and includes:

- **2,562 images** across **31 celebrity classes**  
- **RGB images**, resized to **160×160 pixels**  
- Addressed class imbalance via **weighted loss functions**

---
## 📊 Results  

| Model                     | Strategy                          | Validation Accuracy |
|--------------------------|-----------------------------------|---------------------|
| CustomCNN                | Standard Classification           | 71.25%              |
| EnhancedCNN              | Standard Classification           | 68.20%              |
| Pretrained ResNet-18     | Transfer Learning                 | 86.54%              |
| ResNet-18 + Triplet Loss | Metric Learning + Multi-task      | **93.88%**          |

---

## 💡 Key Insights  
- ✅ **Transfer Learning Works**: Pretrained backbones dramatically outperform models trained from scratch  
- 🔁 **Metric Learning Enhances Embeddings**: Triplet Loss improves not just similarity queries but classification itself  
- ⚖️ **Smart Training > Complex Models**: Effective training strategies beat adding architectural complexity  



