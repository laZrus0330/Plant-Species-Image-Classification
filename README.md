# 🌿 Plant Species Image Classification

## 📌 Project Overview
This project aims to develop an image classification model that can recognize and differentiate 20 related plant species using Google Teachable Machine. A dataset of at least 250 images per species was collected, focusing primarily on leaf-based images captured from different angles and lighting conditions to improve model accuracy and generalization.

The purpose of this model is to automatically identify plant species based on visual features such as leaf shape, vein structure, texture, and overall appearance. This demonstrates how machine learning can be applied to real-world problems in agriculture, environmental monitoring, and plant identification, while showcasing the process of dataset preparation, model training, evaluation, and deployment.

---

## 🌱 Plant Species List

### 1️⃣ Mango (*Mangifera indica*)
![](Image_Plant_Introduction/mango.png)

Mango is a tropical fruit-bearing tree widely cultivated in warm climates. It has long, glossy green leaves and is known for producing sweet, nutritious fruits rich in vitamins A and C.

---

### 2️⃣ Banana (*Musa acuminata*)
![](Image_Plant_Introduction/banana.png)

Banana is a fast-growing tropical plant characterized by large, broad leaves. It is widely cultivated for its edible fruit and is an important agricultural crop worldwide.

---

### 3️⃣ Papaya (*Carica papaya*)
![](Image_Plant_Introduction/papaya.png)

Papaya is a tropical plant with deeply lobed leaves and a soft trunk. It produces sweet orange fruits and is valued for its nutritional and medicinal properties.

---

### 4️⃣ Jackfruit (*Artocarpus heterophyllus*)
![](Image_Plant_Introduction/jackfruit.png)

Jackfruit is a large tropical tree known for producing the biggest tree-borne fruit. Its leaves are thick, dark green, and oval-shaped.

---

### 5️⃣ Durian (*Durio zibethinus*)
![](Image_Plant_Introduction/durian.png)

Durian is a tropical tree famous for its strong-smelling fruit. It has elongated leaves with a glossy upper surface and a golden-brown underside.

---

### 6️⃣ Rambutan (*Nephelium lappaceum*)
![](Image_Plant_Introduction/rambutan.png)

Rambutan is a tropical fruit tree with compound leaves and hairy red fruits. It thrives in humid environments.

---

### 7️⃣ Lanzones (*Lansium parasiticum*)
![](Image_Plant_Introduction/lanzones.png)

Lanzones is a tropical tree producing small round fruits. It has pinnate leaves and grows well in Southeast Asian climates.

---

### 8️⃣ Guava (*Psidium guajava*)
![](Image_Plant_Introduction/guava.png)

Guava is a small tropical tree with oval leaves and aromatic fruits. It is rich in vitamin C and commonly grown in tropical regions.

---

### 9️⃣ Cacao (*Theobroma cacao*)
![](Image_Plant_Introduction/cacao.png)

Cacao is the source of chocolate. It has broad, smooth leaves and grows best in tropical rainforests.

---

### 🔟 Neem (*Azadirachta indica*)
![](Image_Plant_Introduction/neem.png)

Neem is a medicinal tree known for its antibacterial and antifungal properties. It has compound leaves and is widely used in traditional medicine.

---

### 1️⃣1️⃣ Corn (*Zea mays*)
![](Image_Plant_Introduction/corn.png)

Corn is a staple agricultural crop with long narrow leaves and tall stalks. It is cultivated globally for food and industrial use.

---

### 1️⃣2️⃣ Sugarcane (*Saccharum officinarum*)
![](Image_Plant_Introduction/sugarcane.png)

Sugarcane is a tall grass species used for sugar production. It has long, blade-like leaves and thick fibrous stalks.

---

### 1️⃣3️⃣ Betel (*Piper betle*)
![](Image_Plant_Introduction/betel.png)

Betel is a vine plant with heart-shaped leaves. It is widely used in traditional practices and herbal medicine.

---

### 1️⃣4️⃣ Sweet Potato (*Ipomoea batatas*)
![](Image_Plant_Introduction/sweet_potato.png)

Sweet potato is a root crop plant with heart-shaped leaves. It is grown for its edible tuber rich in carbohydrates and vitamins.

---

### 1️⃣5️⃣ Cassava (*Manihot esculenta*)
![](Image_Plant_Introduction/cassava.png)

Cassava is a drought-resistant root crop with palm-like leaves. It is an important food source in tropical regions.

---

### 1️⃣6️⃣ Taro (*Colocasia esculenta*)
![](Image_Plant_Introduction/taro.png)

Taro is a tropical plant known for its large heart-shaped leaves. It is cultivated for its edible underground corm.

---

### 1️⃣7️⃣ Eggplant (*Solanum melongena*)
![](Image_Plant_Introduction/eggplant.png)

Eggplant is a vegetable plant with broad leaves and purple fruits. It belongs to the nightshade family.

---

### 1️⃣8️⃣ Narra (*Pterocarpus indicus*)
![](Image_Plant_Introduction/narra.png)

Narra is a hardwood tree native to Southeast Asia. It has compound leaves and is valued for its durable timber.

---

### 1️⃣9️⃣ Mahogany (*Swietenia macrophylla*)
![](Image_Plant_Introduction/mahogany.png)

Mahogany is a large tropical tree known for its high-quality wood. It has pinnate leaves and is commonly used in furniture making.

---

### 2️⃣0️⃣ Avocado (*Persea americana*)
![](Image_Plant_Introduction/avocado.png)

Avocado is a fruit-bearing tree with dark green oval leaves. It produces nutrient-rich fruits widely consumed worldwide.

---

## 📊 Dataset Information

- Total Classes: 20
- Images per Class: 250–300
- Total Images: ~5,000+
- Image Type: Leaf-based plant images
- Image Size: Default Teachable Machine preprocessing

---

## ⚙️ Model Training Details

- Epochs: 30
- Batch Size: 16
- Learning Rate: 0.001
- Validation Split: Default (Teachable Machine)

### 📸 Training Settings Screenshot
![Training Settings](training_screenshots/training_settings.png)

---

## 📈 Model Evaluation

### 🔍 Confusion Matrix
![Confusion Matrix](evaluation_screenshots/confusion_matrix.png)

### 📊 Accuracy Per Class
![Accuracy Per Class](evaluation_screenshots/accuracy_per_class.png)

### ✅ Overall Accuracy
(Write the percentage here, e.g., 89%)

---

## 🧪 Model Testing (Preview Section)

Below are 10 real-time prediction tests:

![Test 1](preview_tests/test1.png)
![Test 2](preview_tests/test2.png)
![Test 3](preview_tests/test3.png)
![Test 4](preview_tests/test4.png)
![Test 5](preview_tests/test5.png)
![Test 6](preview_tests/test6.png)
![Test 7](preview_tests/test7.png)
![Test 8](preview_tests/test8.png)
![Test 9](preview_tests/test9.png)
![Test 10](preview_tests/test10.png)

---

## 📦 Exported Model

The trained model was exported in:
- TensorFlow format
- Saved in the `exported_model/` folder

---

## 🧠 Reflection

### 1️⃣ How did the number of images affect accuracy?
Having 250–300 balanced images per class improved generalization and reduced bias.

### 2️⃣ Which plants were misclassified?
(Some species with similar leaf shapes were occasionally confused due to visual similarity.)

### 3️⃣ How did parameter changes affect training?
Increasing epochs improved accuracy until overfitting began. Batch size 16 gave stable training.

### 4️⃣ Challenges encountered
- Finding diverse, non-duplicate images
- Similar-looking plant species
- Cleaning mislabeled data

### 5️⃣ Future Improvements
- Add background removal
- Increase dataset diversity
- Use a more advanced CNN architecture
- Collect real-world field images

---

## 🚀 Tools Used
- Google Teachable Machine
- Google Drive
- GitHub
