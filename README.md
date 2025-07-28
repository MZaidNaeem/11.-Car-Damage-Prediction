# 11.-Digit-Classification

# Try the Web App 
[try web app](https://cardamagepredictionbyzaidnaeem.streamlit.app/)

![screenshot](gitimg.png)
 I’m genuinely excited about this project! I trained a deep learning image classification model on 2,300 car damage photos to automatically identify the exact type of damage. My laptop nearly gave up during the training process—but it made it through, and the results were worth it.

📊 Classes Predicted:

Front Breakage
Front Crushed
Front Normal
Rear Breakage
Rear Crushed
Rear Normal

📈 Model Performance:
 Precision | Recall | F1-Score
Front Breakage: 0.73 | 0.93 | 0.82 
Front Crushed: 0.82 | 0.69 | 0.75 
Front Normal: 0.96 | 0.81 | 0.88 
Rear Breakage: 0.84 | 0.65 | 0.74 
Rear Crushed: 0.70 | 0.71 | 0.71 
Rear Normal: 0.75 | 0.92 | 0.83 

📌 Model Highlights:
 ✅ Built using ResNet architecture for strong performance
 ✅ Trained on a custom dataset of 2,300 labeled car damage images
 ✅ Performed extensive hyperparameter tuning for optimal results
 ✅ Used data augmentation to improve real-world generalization

➡️ These results show that the model accurately classifies multiple types of car damage, making it an excellent candidate for insurance and automotive applications.

🔍 Techniques Applied:
 ✅ Transfer Learning with ResNet, EfficientNet
 ✅ Hyperparameter Optimization (learning rate, batch size, optimizer)
 ✅ Image Preprocessing & Augmentation
 ✅ Model Evaluation: Precision, Recall, F1-Score, Confusion Matrix

🛠️ Tech Stack:
 Python | TensorFlow/Keras | NumPy | scikit-learn | Matplotlib

🌐 Use Case Impact:
 Ideal for insurance companies, auto repair shops, and fleet operators, this system can reduce manual inspections, speed up claim approvals, and bring consistency to damage classification.
