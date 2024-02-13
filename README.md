# natural-language-processing
This repository showcases a program designed for the analysis of XML files within a specified folder, with a primary focus on the recognition and classification of drug names through a sequence labeling machine learning algorithm. This innovative approach simplifies the task of semantic processing in pharmaceutical data, leveraging advanced neural network architectures for enhanced accuracy and efficiency.

**Key Features**:
- **B-I-O Schema Utilization**: Adhering to the traditional machine learning structure, the B-I-O (Begin-Inside-Outside) schema is meticulously applied, providing a robust framework for entity recognition.
- **Dual-Program Design**: The architecture comprises two main components - a trainer and a classifier, each serving a distinct purpose in the model training and classification processes.
- **Data Handling**: Emphasis is placed on proper data formatting and encoding, ensuring that both training and validation datasets are optimally prepared for model consumption.
- **Neural Network Insights**: Unlike conventional machine learning models, the neural network approach here benefits from an absence of manual feature extraction, relying instead on appropriate input encoding for processing.
- **Innovative Neural Architecture**: The program leverages LSTM (Long Short-Term Memory) networks, enriched with word and suffix embedding layers, to capture the nuanced semantics of drug names, providing a detailed analysis of each word's characteristics.
- **Customization and Experimentation**: Users are encouraged to experiment with various network configurations, exploring dimensions of embedding layers, pre-trained word embeddings (e.g., word2vec, GloVe, FastText), and LSTM units to refine model performance.
- **Evaluation and Optimization**: The project goes beyond mere accuracy metrics, focusing on F1 scores to truly gauge model effectiveness, especially in distinguishing drug names from non-drug text.

**Repository Contents**:
- Detailed **Jupyter Notebooks** describing all experiments conducted, offering a comparative analysis of different input features and the impact of network size on F1 scores, with insightful conclusions on model behavior and performance optimization strategies.
- **Codemaps Class**: Essential for mapping each word, label, or feature used within the model, facilitating seamless input processing and model training.
- **Function Code for 'learn', 'predict', 'Dataset', and 'build_network'**: Each script is integral to the program's functionality, from learning and prediction to dataset mapping and network construction, enabling users to understand and interact with the underlying machine learning processes.

This repository stands as a testament to the practical application of machine learning in pharmaceutical studies, offering a comprehensive toolkit for professionals and researchers aiming to leverage AI for drug name classification and semantic text similarity tasks.
