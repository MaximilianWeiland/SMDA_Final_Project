# Party Political Communication on Bluesky
Repository for the final project of the seminar “Social Media Data Analysis.” This project examines how German politicians change the sentiment of their social media posts over the course of the election cycle. In particular, it examines whether and how members of parliament communicate differently during election campaigns. This project is a replication of the study [Modulation of Democracy: Partisan Communication During and After Election Campaigns](https://www.cambridge.org/core/journals/british-journal-of-political-science/article/modulation-of-democracy-partisan-communication-during-and-after-election-campaigns/0124647855F11EE6809B59EDA521020E) (Castanho Silva et al., 2024).

## Folder Structure

### 01_data
Contains all retrieved, preprocessed and labelled data.
* [clean_data](01_data/clean_data/) All extracted and cleaned Bluesky posts, cleaned MP-level dataframes and manually labelled sample posts
* [clean_labelled_data](01_data/clean_labelled_data/) All classified posts and grouped per weekly intervals
* [raw_data](01_data/raw_data/) The raw MP data for both legislatures with their potential handles

### 01_data_retrieval_preprocessing
Contains the code for retrieving data on Bundestag MPs as well as the retrieval of all of their Bluesky posts. \
**Note**: An app password is needed for post retrieval which is not shared in this repo.

### 02_figures_tables
Contains all exported plots as png and tables as tex files for the report.

### 02_exploratory_data_analysis
Contains code that performs preliminary data analysis both on both MP and post-level data.

### 03_sentiment_classification
Contains both the validation of different sentiment classifiers as well as the final classification script.

### 04_analysis
Contains the code for the main analysis and a robustness check.

### 05_report_presentation
Contains the main report and the initial project presentation.

