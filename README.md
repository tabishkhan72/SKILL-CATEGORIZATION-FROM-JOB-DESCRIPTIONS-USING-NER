Training a model to accurately identify key entities (Soft and Technical Skills) within text data.

Introduction and background of the planned work:
Using sophisticated NLP methods, namely Named Entity Recognition (NER) and a well-tuned BERT model, this project examines how employment needs are changing over time. I will generate a BIO-tagged training data of phrases from a collection of web-scraped job descriptions in order to optimize the BERT model.
Using the wide list of abilities from O*NET OnLine and the skills expressly stated in the job descriptions, I will further enhance my method by creating a thorough taxonomy of skills. Both soft skills and technology skills are included in this classification.

Discussion of current understanding and relevant literature:
Extricating imperative highlights from information and plans valuable for machine learning calculations. Show determination: try with distinctive machine learning calculations, counting but not restricted to profound learning, arbitrary timberlands, back vector machines, and clustering methods to construct exception discovery models. Show preparing: preparing chosen models employing a subset of the dataset to guarantee appropriate approval and tuning of hyperparameters. Assessment measurements: assess the execution of the models
utilizing assessment measurements such as accuracy, review, F1 score and range beneath the ROC bend (AUC-ROC). Cross-validation: utilizing k-fold cross-validation for demonstrate approval and evaluate their generalizability. 

Progress of the planned work:

Job Description Dataset:
Size and Source: Utilizing a dataset of 187,853 web-scraped job descriptions from various websites.
Unique Identification: Each job description is marked with a 'Job ID'.
Dataset Content:
Job Description: A 'Job Description' column providing comprehensive details about each role.
Skills Recognition: A 'Skills' column that identifies skills required for the job within the description.
Skills Database: A web-scraped list of 8,904 essential skills from onetonline.org, including 35 soft skills and 8,869 technical skills.
Model's Role:
Entity Recognition: Trained to identify skills and technology skills within job descriptions.
Broad Matching: Capable of recognizing variations and related terms for entities (e.g., "machine learning" in different forms).
