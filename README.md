# CV_project
Analyzing the Impact of Dataset Size and Image Resolution on Robustness of Diabetic Retinopathy Classification
## 📂 Dataset

The dataset used in this project is hosted externally due to GitHub’s storage limitations.
🔗 **Download Dataset:** [https://your-google-drive-link](https://drive.google.com/drive/folders/149RnzNtkAHQlG_vkZO2paI7jQU8P13Kw?usp=sharing)

### 📁 Dataset Structure
After downloading, ensure the dataset is placed in the following directory:
dataset/
 class_0/
 class_1/
 class_2/
 class_3/
 class_4/

- Each class folder contains **678 images**.
- Total classes: **5**

### 📥 Setup Instructions

1. Download the dataset from the link above.
2. Upload it to your Google Drive.
3. Mount your Google Drive in Colab:

```python
from google.colab import drive
drive.mount('/content/drive')


