# Diabetic Retinopathy Detection using Artificial Intelligence
This project aims to address the critical need for an efficient and automated method to detect diabetic retinopathy (DR), a serious complication of diabetes that can lead to blindness if left untreated. Currently, DR detection relies on time-consuming manual evaluation of digital color fundus photographs by trained clinicians, which can cause delays in treatment and patient follow-up.

The main contributions of this project are as follows:

1)Data Splitting and Architecture Exploration: We explore the impact of data splitting, changing architectures, and tuning hyperparameters on prediction accuracy. By experimenting with different configurations, we aim to identify the optimal setup for accurate prediction.

2)Ensemble Learning: We leverage ensemble learning techniques to improve the performance of the predictive models. By combining multiple models' predictions, we can enhance the overall accuracy and reliability of diabetic retinopathy detection.

3)Hyperparameter Tuning: We carefully select and tune hyperparameters to optimize the performance of our models. By finding the right combination of hyperparameters, we aim to achieve higher accuracy in predicting diabetic retinopathy.

4)Knowledge Distillation: We employ the knowledge distillation technique to transfer knowledge from our best-performing model (the teacher model) to a simpler model, such as AlexNet (the student model). This approach helps improve the accuracy of the student model by leveraging the expertise of the teacher model.

5)Deployment and Application: We deploy the trained model and create an application that can be used for testing or practical implementation. The model can be accessed and utilized through the Hugging Face platform.

