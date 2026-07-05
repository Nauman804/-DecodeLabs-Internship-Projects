# DecodeLabs AI/ML Internship - Complete Projects Repository

**Batch:** 2026 | **Program:** Artificial Intelligence & Machine Learning  
**Institution:** DecodeLabs | **Duration:** 4 Weeks

---

## 📋 Repository Overview

This repository contains all 4 projects completed during the DecodeLabs AI/ML Internship program (Batch 2026). Each project progressively builds AI/ML skills from foundational to advanced levels.

---

## 📂 Project Structure

```
DecodeLabs-Internship-Projects/
│
├── README.md                          (This file)
├── .gitignore
├── requirements.txt
│
├── Project_1_Rule_Based_Chatbot/
│   ├── README.md
│   ├── chatbot.ipynb
│   ├── chatbot.py
│   └── sample_outputs/
│
├── Project_2_Data_Classification/
│   ├── README.md
│   ├── classification.ipynb
│   ├── data/
│   └── results/
│
├── Project_3_Recommendation_System/
│   ├── README.md
│   ├── recommendation_system.ipynb
│   ├── data/
│   └── evaluation_results/
│
└── Project_4_Image_Recognition/
    ├── README.md
    ├── image_recognition.ipynb
    ├── sample_images/
    └── detection_results/
```

---

## 🎯 Projects Summary

### **Project 1: Rule-Based AI Chatbot** (Week 1)
**Level:** Foundation | **Status:** ✅ Complete

A simple rule-based chatbot using if-else logic and dictionary-based responses.

**Key Skills:**
- Control Flow (if-elif-else)
- While Loops
- Dictionary Data Structure
- Functions and Classes
- String Operations

**Technologies:**
- Python 3.8+
- No external libraries required

**Run Locally:**
```bash
python Project_1_Rule_Based_Chatbot/chatbot.py
```

**Run in Google Colab:**
- Open `chatbot.ipynb`
- Run all cells sequentially

---

### **Project 2: Data Classification Using AI** (Week 2)
**Level:** Intermediate | **Status:** ✅ Complete

Classification of data using 5 different machine learning models with comprehensive EDA and evaluation.

**Key Skills:**
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Model Training and Evaluation
- Cross-Validation
- Performance Metrics (ROC-AUC, Precision, Recall)

**Models Implemented:**
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)
5. Support Vector Machine (SVM)

**Technologies:**
- Python 3.8+
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

**Requirements:**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

### **Project 3: AI Recommendation System** (Week 3)
**Level:** Advanced | **Status:** ✅ Complete

Recommendation system using content-based filtering, collaborative filtering, and hybrid approach.

**Key Skills:**
- Feature Vectorization
- Similarity Metrics (Cosine, Euclidean, Manhattan)
- Content-Based Recommendation
- Collaborative Filtering
- Hybrid Algorithms
- Evaluation Metrics (Precision@5, Recall@5, MAP)

**Algorithms Implemented:**
1. Content-Based Filtering
2. User-Based Collaborative Filtering
3. Hybrid System (60% Content + 40% Collaborative)

**Technologies:**
- Python 3.8+
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

**Requirements:**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

### **Project 4: Image Recognition & Text Extraction** (Week 4)
**Level:** Mastery Phase | **Status:** ✅ Complete

Image recognition system with OCR and object detection using pre-trained models.

**Key Skills:**
- Optical Character Recognition (OCR)
- Object Detection
- Image Pre-Processing (Grayscale, Blur, Thresholding)
- Transfer Learning
- Confidence Thresholding
- Bounding Box Detection

**Two Implementation Paths:**
1. **Path 1:** OCR using Pytesseract
2. **Path 2:** Object Detection using MobileNet-SSD

**Technologies:**
- Python 3.8+
- OpenCV (cv2)
- Pytesseract
- PIL/Pillow
- Matplotlib

**Requirements:**
```bash
pip install opencv-python pytesseract pillow matplotlib
```

**Additional System Dependencies (Linux/Mac):**
```bash
# Ubuntu/Debian
sudo apt-get install tesseract-ocr

# macOS
brew install tesseract
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Git

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/DecodeLabs-Internship-Projects.git
cd DecodeLabs-Internship-Projects
```

2. **Create a virtual environment (optional but recommended):**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install all dependencies:**
```bash
pip install -r requirements.txt
```

---

## 💻 Running the Projects

### Using Google Colab (Recommended)
All projects are optimized for Google Colab. Simply:
1. Open the `.ipynb` file
2. Click "Open in Colab"
3. Run cells sequentially

### Local Development
Each project has a Python script or Jupyter notebook that can be run locally.

---

## 📊 Project Progression

| Project | Type | Complexity | Skills | Status |
|---------|------|-----------|--------|--------|
| **1** | Chatbot | ⭐ Basic | Logic, Loops, Classes | ✅ |
| **2** | Classification | ⭐⭐⭐⭐ | ML, EDA, Models | ✅ |
| **3** | Recommendation | ⭐⭐⭐⭐⭐ | Algorithms, Math | ✅ |
| **4** | Image Recognition | ⭐⭐⭐⭐⭐⭐ | Computer Vision, DL | ✅ |

---

## 🎓 Learning Outcomes

By completing all 4 projects, you will have mastered:

### Programming Fundamentals
- Control flow and decision making
- Loops and iteration
- Functions and object-oriented programming
- Data structures (lists, dictionaries, arrays)

### Data Science
- Exploratory Data Analysis
- Data preprocessing and normalization
- Feature engineering
- Model selection and evaluation

### Machine Learning
- Supervised learning algorithms
- Unsupervised learning concepts
- Model evaluation metrics
- Cross-validation and hyperparameter tuning

### Advanced AI
- Recommendation systems
- Computer vision basics
- Text extraction (OCR)
- Object detection
- Transfer learning
- Confidence thresholding

---

## 📝 Documentation

Each project folder contains:
- **README.md** - Project-specific documentation
- **Jupyter Notebook (.ipynb)** - Complete implementation with explanations
- **Python Script (.py)** - Standalone executable code
- **Sample Data/Results** - Example outputs and visualizations

---

## 🔧 Technologies Used

### Languages
- **Python 3.8+**

### Libraries
- **Data Science:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Computer Vision:** OpenCV, PIL
- **Visualization:** Matplotlib, Seaborn
- **Text Processing:** Pytesseract

### Platforms
- **Jupyter Notebook** - Interactive development
- **Google Colab** - Cloud-based execution
- **GitHub** - Version control and collaboration

---

## 📈 Results Summary

### Project 1: Chatbot
- ✅ 15+ predefined responses
- ✅ Natural conversation flow
- ✅ Error handling

### Project 2: Classification
- ✅ 5 different models
- ✅ Cross-validation implemented
- ✅ ROC-AUC curves generated

### Project 3: Recommendation
- ✅ 3 recommendation approaches
- ✅ 15+ similarity metrics tested
- ✅ Precision, Recall, MAP calculated

### Project 4: Image Recognition
- ✅ OCR text extraction
- ✅ Object detection with 80% threshold
- ✅ Pre-processing pipeline implemented

---

## 🤝 Contributing

This is an internship project portfolio. Contributions and improvements are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

---

## 📞 Contact & Support

**DecodeLabs**
- Email: decodelabs.tech@gmail.com
- Phone: +91 89330 06408
- Website: www.decodelabs.tech

---

## 📄 License

These projects are part of the DecodeLabs AI/ML Internship Program (Batch 2026).
All rights reserved to DecodeLabs.

---

## 🎉 Acknowledgments

Special thanks to:
- DecodeLabs team for comprehensive curriculum
- Community libraries and open-source projects
- All contributors and reviewers

---

## 📚 Additional Resources

- [Python Official Documentation](https://docs.python.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [OpenCV Documentation](https://docs.opencv.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Google Colab Guide](https://colab.research.google.com/)

---

**Last Updated:** July 2026  
**Status:** All Projects Complete ✅  
**Ready for Submission:** YES ✓

---

For detailed information about each project, navigate to the respective project folder and read the individual README.md file.

**Happy Learning! 🚀**
