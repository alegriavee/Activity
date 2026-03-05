<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Veejay Alegria Adame</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600&family=Roboto&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: linear-gradient(to right, #2c3e50, #3498db);
      font-family: 'Roboto', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }
    .intro-container {
      text-align: center;
      color: white;
      animation: fadeIn 2s ease-in-out;
    }
    h1 {
      font-size: 3em;
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(90deg, #f39c12, #e74c3c);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: colorShift 5s infinite alternate;
    }
    p {
      font-size: 1.2em;
      margin-top: 10px;
      opacity: 0.8;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes colorShift {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }
  </style>
</head>
<body>
  <div class="intro-container">
    <h1>Hi, I am Veejay Alegria Adame</h1>
    <p># Hi there, I'm Veejay 👋

I am a BS Information Technology student at Batangas State University - TNEU Lipa City, passionate about data science, machine learning, and network infrastructure. I enjoy turning complex data into actionable insights and building systems that solve real-world problems.

### 🌐 Check out my full portfolio: (https://alegriavee.github.io/Activity/)

---

### 👨‍💻 What I'm currently working on
* 🏛️ **OJT at the Department of Agriculture (MIS Office):** Providing IT support, managing local networks, troubleshooting hardware, and assisting with satellite communications.
* 🥬 **Machine Learning in Agriculture:** Developing an image classification model (TensorFlow/Keras) to detect and diagnose diseases in lettuce leaves using computer vision.
* 💧 **Capstone Project:** Building an Automated Water Billing Management System for BAWASA, integrating a SARIMAX machine learning model for demand and sales forecasting.
* 💻 **Web Development:** Designing and deploying my personal developer portfolio.

### 🛠️ Tech Stack & Tools
*(This matches the marquee on your portfolio website!)*
* **Data Science & ML:** Python, TensorFlow, Keras, Pandas, NumPy, Scikit-learn
* **Data Analytics:** Power BI, Microsoft Fabric, T-SQL, Dimensional Modeling
* **IT Infrastructure:** Networking, Hardware Troubleshooting, Windows Server, Zone-Based Firewalls
* **Development:** HTML/CSS, Git, GitHub, Google Colab

---

### 🚀 Highlighted Repositories
* **[Lettuce Disease Classifier](link-to-repo):** A deep learning model built with EfficientNet/MobileNetV2 to identify plant diseases from images.
* **[BAWASA Billing & Forecasting System](link-to-repo):** A full-stack capstone project featuring predictive analytics using time-series decomposition.

---

### 📫 Let's Connect!
* **Portfolio:** (https://alegriavee.github.io/Activity/)
* **LinkedIn:** [Insert Link]
* **Email:** veejayadame@gmail.com.</p>
  </div>
</body>
</html>
