# machine_learning_projects
Here you can find interesting ML template to do Sentiment An. , Predictive An. and so on.


Source of method:  https://www.researchgate.net/publication/382851188_A_whole_method_to_do_Data_Analysis 


------------------------------- italian -----------------------------------------------------------------
# italian
Usando la mia precedente pubblicazione (URL: https://www.researchgate.net/publication/382851188_A_whole_method_to_do_Data_Analysis), questo lavoro mette in risalto come tale metodo di analisi di dati si possa usare per svolgere una Sentiment Analysis. Ho analizzato delle recensioni di Amazon da un database Kaggle contenente recensioni e rating da 1 a 5. L'analisi del sentiment è stata svolta utilizzando le seguenti librerie: from sklearn.feature_extraction.text import TfidfVectorizer from sklearn.ensemble import RandomForestClassifier from sklearn.linear_model import LogisticRegression from sklearn.svm import SVC from nltk.classify import NaiveBayesClassifier Punti Chiave Trattati: Preprocessing: È stato sottolineato l'importanza di gestire in modo coerente i casi "lowercase" e "uppercase". Sono state discusse tecniche per progettare una maschera di stringa in grado di filtrare i dati in modo più efficace. La lingua è stata evidenziata come un aspetto cruciale dell'analisi del sentiment. Confronto tra Modelli: Sono stati confrontati quattro classificatori: SVC, Random Forest, Naive Bayes e Logistic Regression. È stato dimostrato che Naive Bayes è il modello meno efficace. Test di Accuratezza e Robustezza: La performance del sistema è stata testata utilizzando recensioni ambigue per valutarne accuratezza e robustezza. Estrazione delle Feature e Sfide: I rating maggiori di 3 sono stati etichettati come positivi, mentre quelli inferiori a 3 come negativi, semplificando inizialmente l'estrazione della feature Sentiment. Tuttavia, la classificazione binaria del sentiment (Positivo/Negativo) diventa complessa quando si lavora solo con recensioni testuali. Parole come "but", "however" e simili creano spesso un contrasto tra affermazioni leggermente positive e leggermente negative, complicando la determinazione del sentiment.

------------------------------- english -----------------------------------------------------------------
# english
I analyzed Amazon Reviews from a Kaggle database containing reviews and ratings ranging from 1 to 5. The sentiment analysis was conducted using the following libraries:

    from sklearn.feature_extraction.text import TfidfVectorizer
    from sklearn.ensemble import RandomForestClassifier
    from sklearn.linear_model import LogisticRegression
    from sklearn.svm import SVC
    from nltk.classify import NaiveBayesClassifier

Key Points Covered:

    Preprocessing:
        Emphasis was placed on handling "lowercase" and "uppercase" cases consistently.
        Techniques for designing a string mask to filter data more effectively were discussed.
        Language choice was highlighted as a crucial aspect of sentiment analysis.

    Model Comparison:
        Four classifiers were compared: SVC, Random Forest, Naive Bayes, and Logistic Regression.
        Results demonstrated that Naive Bayes was the least effective model.

    Accuracy and Robustness Testing:
        The system's performance was tested using ambiguous reviews to evaluate its accuracy and robustness.

    Feature Extraction and Challenges:
        Ratings greater than 3 were labeled as positive, while those less than 3 were negative, making it straightforward to derive the Sentiment feature initially.
        However, binary sentiment classification (Positive/Negative) becomes challenging when working only with textual reviews.
        Words such as "but", "however", and similar terms often create a contrast between mildly positive and mildly negative statements, complicating the sentiment determination.


