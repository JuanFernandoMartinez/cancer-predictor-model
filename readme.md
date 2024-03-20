# Title
Cancer predictor model
### Problem

Disease detection through the use of images and Artificial Intelligence (AI) is an innovative approach in the field of medicine. This approach is based on supervised learning, a branch of machine learning, where an AI model is trained with a set of labeled data. In this context, diagnostic images, such as X-rays or MRIs, are used as inputs for the model, and the labels correspond to the presence or absence of a disease.

This method has the potential to significantly improve the accuracy and efficiency of disease detection. However, it is crucial to remember that these AI models must be validated and thoroughly tested before their clinical implementation to ensure their accuracy and reliability. Moreover, these models are intended to be used as a support tool for healthcare professionals, complementing, but not replacing, their clinical judgment. AI in disease detection promises to be a valuable tool in the future of healthcare.

### Methodology

#### Business Understanding

This stage is about fully comprehending the project’s objectives. For disease detection using AI, the goal is to enhance the accuracy and efficiency of disease diagnosis. This involves understanding the specific diseases to be detected, the types of images to be used (X-rays, MRIs, etc.), and the performance metrics for the AI model. It’s also about understanding the potential impact of the project, such as how it could improve patient outcomes, reduce diagnostic errors, or save time for healthcare professionals.

In this case we are dealing with breast cancer. It is a type of cancer that can occur in both men and women but it's more common in women. It begins when cells undergo abnormal growth and multiplication, normally happening in the ducts or the lobules. This growth can cause tumors to be formed, that can be benign or malignant, the first doesn't spread while the second can invade nearby tissues. If the cells manage to get into the bloodstream and spread to other parts of the body, that's known as metastasis.

There are two common types of breast cancer: Invasive Ductal Carcinoma and Invasive Lobular Carcinoma. Invasive Ductal Carcinoma originates in the milk ducts, while Invasive Lobular Carcinoma begins in the lobules.

One way to diagnose breast cancer is through mammograms, which are X-ray images used to detect cancer in its early stages. Cancerous tissue typically appears white on mammograms. Some indicators of breast cancer include:

Areas of high-density white tissue, where size, shape, and borders are observed.
Small white spots, which can be harmless, but radiologists examine their shape and pattern as they may signal cancer.
The presence of cysts, which are fluid-filled sacs, usually non-cancerous.
Calcifications, which are calcium deposits. Microcalcifications are common in aging, but their appearance can indicate cancer.
Fibroadenomas, benign tumors that are round and palpable like marbles, more common in young women.
Scar tissue, appearing white on mammograms. It's important to inform the doctor about any prior breast scars.

#### Data Understanding

This phase involves collecting and familiarizing with the data. For this task, a large dataset of labeled medical images is needed. The labels indicate the presence or absence of the disease. The data must be explored to understand its structure, quality, and potential issues. This could involve visualizing the images, checking for class imbalance in the labels (e.g., are there enough examples of each disease?), and identifying any potential sources of bias in the data.

#### Data Preparation

In this phase, the collected data is prepared for modeling. This could involve preprocessing the images (resizing, normalization), handling missing or inconsistent data, and splitting the data into training, validation, and test sets. This stage is crucial as the quality of the data directly impacts the performance of the model. It’s also about ensuring that the data is representative of the real-world scenario where the model will be deployed.

#### Modeling

In this phase, suitable classifiers are selected and trained. This could involve choosing appropriate classification algorithms, training them on the prepared data, and tuning their parameters to improve performance. This stage is about finding the best classifier that can accurately detect diseases from the images. It’s also about understanding the trade-offs between different classifiers (e.g., accuracy vs. computational cost) and choosing the one that best fits the project’s requirements.


#### Evaluation

At this stage, the performance of the model is evaluated. This involves testing the model on unseen data, assessing its performance using the defined metrics, and comparing it to existing diagnostic methods. This stage is not just about quantifying the model’s performance, but also about understanding its strengths and weaknesses. For example, does the model perform equally well for all diseases, or are there certain diseases where it struggles?

#### Deployment
In the final phase, the model is deployed for practical use. This could involve integrating the model into a clinical decision support system, where it can assist healthcare professionals in diagnosing diseases from medical images. The model should be monitored and updated as necessary, based on its performance in the real world. This stage is about ensuring that the model can be effectively used in practice and that it continues to deliver value over time.

### Metrics

Several metrics can be used to measure the progress of a project:

1. Project Scope Definition: Measure the clarity and thoroughness of project objectives by reviewing project documentation and discussions with team members.
2. Data Collection and Annotation: valuate the effectiveness of the data collection process by examining factors such as the size of the dataset, the representativeness of the samples, and the quality of annotations provided. Using specific metrics such as dataset size, data diversity, and inter-rater agreement for annotation quality.
3. Model Evaluation:  
3.1. Accuracy: This is the proportion of true results (both true positives and true negatives) among the total number of cases examined.
3.2. Precision: Also called the positive predictive value, this is the proportion of true positives among the total outcomes predicted as positive.
3.3. Recall: Also known as sensitivity, hit rate, or true positive rate, this is the proportion of true positives among the total actual positive outcomes.
3.4. F1 Score: This is the harmonic mean of precision and recall, and it provides a balance between the two metrics.
4. Documentation: Review completness and clarity of project documents.

### Datos disponibles

### Estrategias para recolectar más datos

### Análisis aspectos éticos

It is crucial to address the ethical aspects of our project, such as sensitivity to biases and uncertainties. We must strive to refine the data, if possible, to make it as equitable as possible and to represent diverse populations and demographic groups. Similarly, it is essential to evaluate and be transparent about the limitations and uncertainties of the model, as well as its potential impacts on clinical practice. We are aware that this project is not aimed at replacing human labor, but rather supporting it to streamline processes and serve a larger number of people. Finally, it is worth emphasizing that this project, being closely related to medicine, must be approached with great rigor due to the responsibility it entails, including the privacy and confidentiality of the data used in model training and in future scenarios (hypothetically)