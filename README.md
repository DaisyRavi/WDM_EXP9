### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 24.08.2024
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
![361129197-94185c0b-d77c-43fa-a4e2-c23ed80be7ef](https://github.com/user-attachments/assets/f9076acb-5794-40f1-a888-9d925f5f8eaa)

![361129202-9ad54fe6-2998-4d2b-ae0b-7369ac1ac645](https://github.com/user-attachments/assets/139527cf-adb6-40dd-853e-93bba1cf9f25)

![361129207-f43305ad-7d4f-4f11-8061-4221ae255627](https://github.com/user-attachments/assets/417d5779-dec8-4580-8236-935d8e82763d)

### Result:
The Preprocessing on Twitter Data using Rapidminer is successfull.
