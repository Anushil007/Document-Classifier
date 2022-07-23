# Document-Classifier

This project was taught to us by [Siddant Sir](https://github.com/Siddhant128-bit).


Here, different files are collected which are about either AI or about web development. The files are in PDF format. They are then classified according to their type and put in 2 seperate lovations. Then, the pdfs are accessed and documents are marked. 1 for AI and 0 for wed. Then the texts are merged all in one common CSV file (Dataset.csv) for easier operation in the future.

Then we use NLTK and with its help remove the stopwords and also use count vectorizer to convert the text into a vector format for easier processing. We use Multinomial Naive Bayes algorithm and train it. The model is stored as a pickle form for further use. Also, the vectorizer has a pickle file.

For testing, we input a new file in PDF format and by looking at its content, the nodel decides whether the file is about AI or about web.

This project was done in a virtual environment.
