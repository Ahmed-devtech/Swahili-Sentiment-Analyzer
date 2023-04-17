# Swahili-Sentiment-Analyzer
his is an Natural Language processing Project. A swahili sentiment analyzer. which uses the swahili sentiment analysis dataset from github https://github.com/Neurotech-HQ/swahili-sentiment-analysis-dataset. 
This project also uses a custom swahili stopwords csv file from the "Enhancing text pre-processing for Swahili language: Datasets for common Swahili stop-words, slangs and typos with equivalent proper words" research article by Bernard Masua and Noel Masasi. The code preprocesses the data by removing the noise. Feature extraction using countvectorizer. It then trains the model using the naive bayes classifier algorithm to classify the texts into the sentiment categories.It then uses the gradio library to deploy the NLP application. The code launches the Gradio interface where you can input Swahili text and get the sentiment analysis result as output.
