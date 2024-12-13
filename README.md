# Machine Learning  
**CheckMATE Learning Path Documentation**  

CheckMATE is an application designed for school environments. It serves as a smart attendance system, school attribute checker, and mood tracker for all students. CheckMATE aims to assist teachers and parents in monitoring student discipline effectively.  

The CheckMATE application is built with three machine learning model architectures, all based on the CNN algorithm:  

1. **Model1_Attendance**  
   The `TF100.keras` model is designed for student attendance tracking and consists of four classes: Liza, Nabila, Zain, and NoFace. This model utilizes the pre-trained MobileNetV2, where the final layers are fine-tuned for retraining. The dataset was created independently by capturing personal photos with an equal number of images for each class.  

2. **Model2_Tie**  
   The `dasidasi.keras` model detects school attributes, specifically ties, with a binary output (wearing a tie or not wearing a tie). This model employs the MobileNetV2 pre-trained model with all layers retrained. The dataset was created independently by capturing personal photos with an equal number of images for each class.  

3. **Model3_Expression**  
   The `ekspresi.keras` model classifies four expressions: happy, sad, neutral, and angry. It was developed using a simple CNN architecture without a pre-trained model. The dataset was sourced from the FER2013 dataset on Kaggle, which originally contained seven expressions.  

These models collectively enable CheckMATE to provide robust functionality, enhancing the school monitoring system with intelligent machine learning solutions.
