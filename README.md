
---

## 📈 Results

| Metric | Training | Validation |
|---------|-----------|-------------|
| **Accuracy** | ~70% | ~65% |
| **Loss Trend** | Decreasing | Stable and slightly lower than training loss |

**Observation:**  
The model shows **steady convergence** with balanced training and validation performance, indicating **no major overfitting** and strong generalization.

![Training and Validation Results](plots/resnet50_training.png)

---

## 🧪 How It Works

1. **Dataset Preparation:**  
   - Images are preprocessed (resize, normalize, augment).  
   - Divided into training and validation sets.

2. **Model Training:**  
   - Fine-tuning ResNet50 on the tea leaf dataset.  
   - Early stopping and learning rate reduction to optimize training.

3. **Evaluation:**  
   - Accuracy and loss metrics plotted per epoch.  
   - Confusion matrix (optional) for class-wise performance.

4. **Extension (Optional):**  
   - Integrate yield estimation using regression on features like leaf area, color, and disease severity.  

---

## 🧰 Technologies Used

- **Python 3.x**  
- **TensorFlow / Keras**  
- **NumPy, Pandas, Matplotlib, Seaborn**  
- **OpenCV** for image preprocessing  
- **Google Colab / Jupyter Notebook**

---

## 📊 Future Enhancements

- Add **YOLO or Faster R-CNN** for real-time detection.  
- Integrate **IoT sensor data** for yield prediction.  
- Deploy as a **web dashboard** for farmers (Streamlit / Flask).  

---

## 🌾 Real-World Impact

This model supports **precision agriculture** by providing:
- Early disease detection → timely treatment.  
- Yield monitoring → better resource management.  
- Quality control → improved market value.  

---

## 👩‍💻 Author

**Y. Gnaneshwar**  
AI & Deep Learning Enthusiast
📧 *dygnaneshwar@gmail.com*  

---

## 📜 License

This project is released under the **MIT License** — free to use and modify with attribution.

---

## ⭐ Acknowledgements

- **ResNet50** model by *Kaiming He et al., 2015*.  
- Dataset references from open agricultural image repositories.  
- TensorFlow & Keras for model training framework.

---

> “Empowering agriculture with intelligence — one leaf at a time.” 🌱
