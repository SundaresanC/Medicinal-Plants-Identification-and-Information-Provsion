# Medicinal Plants Identification and Information Provision

## 📌 Overview

This project focuses on the **identification and information provision of medicinal plants** using **machine learning and deep learning models**. The system classifies medicinal plants based on their images and provides detailed information about their medicinal properties, uses, and benefits.

## 🚀 Features

- **Image Classification**: Uses pre-trained deep learning models for plant identification.
- **Information Retrieval**: Provides medicinal properties, usage, and benefits of identified plants.
- **User Interface**: Web-based or CLI-based system for easy interaction.
- **Dataset Handling**: Supports a diverse dataset of medicinal plants.

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/medicinal-plants-identification.git
   cd medicinal-plants-identification
   ```
2. Install dependencies

## 📂 Dataset

- The dataset consists of **87 different medicinal plants** with labeled images.
- Sources include **Kaggle datasets, herbarium collections, and self-collected images**.

## 🏗️ Usage

1. **Run the identification script**:
   ```bash
   python plant_identification.py --image sample.jpg
   ```
2. **Test with a custom input**:
   ```python
   from model import identify_plant
   
   image_path = "sample.jpg"
   plant_info = identify_plant(image_path)
   print(plant_info)
   ```

## 📊 Sample Output

Example of identification output:
```json
{
  "plant_name": "Neem",
  "scientific_name": "Azadirachta indica",
  "medicinal_uses": "Treats skin disorders, boosts immunity, has antibacterial properties."
}
```

## 📈 Visualization

- The system provides visualization for **classification confidence, dataset distribution**, and **plant properties**.

## 📜 Dependencies

- Python 3.11
- `tensorflow`
- `torch`
- `pandas`
- `opencv-python`
- `flask` (if using a web interface)

## 🤝 Contribution

Feel free to **fork** this repository, submit issues, or create pull requests!

## 🔗 Connect

- LinkedIn: [Sundaresan C](https://www.linkedin.com/in/sundaresan-c-55991b236/)
- GitHub: [Sundaresan C](https://github.com/SundaresanC)

