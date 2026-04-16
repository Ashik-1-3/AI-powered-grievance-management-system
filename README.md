# AI-powered-grievance-management-system
    
    This project aims to automatically classify public grievances into appropriate categories using Natural Language Processing (NLP) and Machine Learning. In large-scale grievance systems, manual categorization is time-consuming, error-prone, and inefficient.

  By automating this process, the system helps in faster routing of complaints to the correct departments, improves response time, and enhances overall efficiency in grievance redressal systems.

  The dataset used in this project is a real-world public grievance dataset collected from government grievance portals (CPGRAMS-like data). It contains approximately 175,784 records, which were cleaned and reduced to around 63,498 valid entries, and further sampled to 20,000 records for efficient processing. After filtering meaningful categories and removing noise, the final dataset used for training consisted of approximately 3,000–8,000 high-quality samples.

The dataset includes features such as grievance text (remarks and subject), category codes, dates, and user-related metadata. For this project, only textual fields (remarks_text and subject_content_text) and category labels were used.

Preprocessing steps applied include:

* Text cleaning (removal of null and short entries)
* Combining multiple text fields into a single input
* Tokenization and lemmatization
* Stopword removal
* TF-IDF vectorization with n-grams (1 to 2/3 words)
* Removal of rare categories and dataset balancing to handle class imbalance

Dataset Link: https://drive.google.com/drive/folders/1ZLtPl29TGnc-yyt_WqqG7NRFn7BWd5ih?usp=sharing
