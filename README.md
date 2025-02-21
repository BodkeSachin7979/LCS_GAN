# CT Scan Image Enhancement for Liver Cancer Detection
 Developed a GAN-based system improving CT scan quality for liver cancer detection.
<h1>Hi 👋, I'm  Sachin Bodke</h1>
<p>Motivated Python Developer skilled in Flask, Django, and REST APIs, with a passion for building scalable web applications.</p>
<h2>🚀 Languages and Tools I Use</h2>
<p><a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="42" height="42" /></a>
<a target="_blank" href="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="42" height="42" /></a>
<a target="_blank" href="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="42" height="42" /></a>
<a target="_blank" href="https://cdn.worldvectorlogo.com/logos/django.svg" style="display: inline-block;"><img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="42" height="42" /></a>
<a target="_blank" href="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="42" height="42" /></a>
<a target="_blank" href="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="42" height="42" /></a>
<a target="_blank" href="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="42" height="42" /></a></p>
<hr><br>

## 🚀 Overview
Liver cancer is one of the deadliest forms of cancer, with early detection playing a crucial role in effective treatment. Our project leverages **Generative Adversarial Networks (GANs)** to enhance CT scan images, improving diagnostic accuracy and assisting healthcare professionals in identifying malignant tissues more effectively.

🔬 **Key Contributions:**
- Enhancing CT scan images to improve contrast and reduce noise.
- Implementing a GAN-based approach for **tumor segmentation and localization**.
- Developing a **real-time web-based diagnostic platform** for liver cancer detection.

---

## 🏗️ Project Architecture

### 🔹 **How it Works**
1️⃣ **Data Preprocessing**: CT images are normalized, noise is reduced, and artifacts are removed.<br>
2️⃣ **GAN Model**: The GAN consists of:
   - **Generator**: Enhances low-contrast images.
   - **Discriminator**: Evaluates the quality of enhanced images.<br>
3️⃣ **Image Enhancement**: The GAN refines CT scans for better visualization.<br>
4️⃣ **Tumor Segmentation**: Improved detection accuracy using **Dice Similarity Coefficient (DSC)**.<br>
5️⃣ **Classification**: CNN-based classifier distinguishes between malignant and normal tissues.<br>

### 🛠️ **Technology Stack**
- **Machine Learning Frameworks**: TensorFlow, PyTorch<br>
- **Backend**: Flask/Django (for web integration)<br>
- **Frontend**: React.js (for interactive UI)<br>
- **Database**: PostgreSQL (for medical record storage)<br>
- **Cloud Integration**: AWS/GCP (for scalable deployment)<br>

---

## 📊 Results & Performance
📌 **Image Quality Improvement**
- Structural Similarity Index (SSIM) increased from **0.72 → 0.91**<br>
- Peak Signal-to-Noise Ratio (PSNR) improved from **22.5 dB → 31.8 dB**<br>

📌 **Tumor Segmentation Accuracy**
- Dice Similarity Coefficient (DSC) improved from **0.68 → 0.85**<br>

📌 **Classification Performance**
- Accuracy improved from **78% → 92%** for distinguishing malignant vs. normal tissues.<br>

---

## 🔍 Dataset
We utilized publicly available medical datasets:
- **Liver Tumor Segmentation Challenge (LiTS)**<br>
- **Sliver07**<br>
- **IRCAD 3D Image Database (3D-IRCADb)**<br>

---

## 🖥️ Setup & Installation
Clone the repository and install dependencies:
```bash
$ git clone https://github.com/your-repo/liver-cancer-gan.git
$ cd liver-cancer-gan
$ pip install -r requirements.txt
```
Train the GAN model:
```bash
$ python train.py --epochs 100 --batch_size 16
```
Run the web application:
```bash
$ python app.py
```

---

## 📌 Future Enhancements
- Optimize GAN for **faster processing** in clinical settings.
- Expand dataset to include diverse imaging conditions.
- Integrate other imaging modalities (**MRI, PET scans**).
- Improve explainability for better doctor-patient interaction.

---

## 🏥 Impact & Clinical Significance
✅ **Early Diagnosis**: Potentially life-saving by improving early cancer detection.
✅ **AI-Powered Medical Imaging**: Enhancing existing radiology workflows.
✅ **Scalable & Accessible**: A web-based platform accessible worldwide.

🚀 Join us in revolutionizing medical imaging with AI! 🌍


