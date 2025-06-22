# Garbage-classification
Alright Lokesh, let's get that README popping with some clean structure, proper vibes, and a touch of professional flair for your **Week 1: Preprocessing Task** in the **AICTE Shell Green AI Internship**. Here's a full-blown `README.md` draft you can drop straight into your project folder like a boss:

---

```markdown
# ♻️ Garbage Classification using Deep Learning  
**AICTE – Shell Green AI Internship (Week 1 Task)**  

## 📅 Week 1: Preprocessing Task  
This repository contains the first milestone of the Green AI Internship project, focused on image classification of various types of garbage to support sustainable AI solutions. The goal is to prepare and preprocess the dataset for a deep learning model that can accurately classify waste into predefined categories.

---

## 📂 Dataset Overview  
The dataset used for this project is organized into **training** and **validation** sets.

- **Training Data:**
  - `Found 2024 images`
  - Belongs to **6 classes** of waste
- **Validation Data:**
  - `Found 503 images`
  - Belongs to the same **6 classes**

### 🗃️ Classes:
The waste is categorized into the following six classes:
1. Cardboard
2. Glass
3. Metal
4. Paper
5. Plastic
6. Trash

---

## 🔧 Preprocessing Steps

Preprocessing is the backbone of building a robust model. Here's what was accomplished during Week 1:

### 1. **Image Resizing**  
All images were resized to a uniform dimension (e.g., 224x224) to maintain consistency and reduce computational cost.

### 2. **Normalization**  
Pixel values were scaled to the range `[0, 1]` using standard normalization techniques (e.g., dividing by 255).

### 3. **Directory-Based Label Encoding**  
Each image was automatically labeled based on its folder name, following a structured dataset directory format:
```

/dataset/
/train/
/cardboard/
/glass/
...
/validation/
/cardboard/
/glass/
...

````

### 4. **Data Augmentation**  
To prevent overfitting and improve generalization, basic augmentations were applied (e.g., horizontal flip, random rotation, zoom).

### 5. **Train-Validation Split Check**  
Verified that both training and validation sets are balanced and cover all classes proportionately.

---

## 📊 Output (Console Logs)

```bash
Found 2024 images belonging to 6 classes.
Found 503 images belonging to 6 classes.
````

This confirms successful loading and recognition of the class structure by the image data generator.

---

## ✅ Next Steps

🔜 **Week 2:** Model Building & Training
In the upcoming week, we’ll build a CNN model using frameworks like TensorFlow/Keras or PyTorch and start training the model on this preprocessed data.

---

## 🤝 Credits

This project is part of the **AICTE – Shell Green Skills Internship Program**, focused on using Artificial Intelligence for solving sustainability challenges.

Mentors: Provided by Edunet Foundation, Shell, and AICTE.
Contributors: \[Your Name Here]

---

## 🌱 Let's build Green AI. Save Earth, one image at a time.

```

---

Let me know if you want me to tailor this for PyTorch, TensorFlow, or a Jupyter notebook format — or if you’ve got code or logs to include too. Let’s make Week 1 shine! 💡🧠💚
```
