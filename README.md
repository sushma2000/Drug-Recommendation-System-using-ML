

# Drug Recommendation System based on Sentiment Analysis of Drug Reviews using Machine Learning 
ABSTRACT

Since coronavirus has shown up, inaccessibility of legitimate clinical resources is at its peak, like the shortage of specialists and healthcare workers, lack of proper equipment and medicines etc. The entire medical fraternity is in distress, which results in numerous individual’s demise. Due to unavailability, individuals started taking medication independently without appropriate consultation, making the health condition worse than usual. As of late, machine learning has been valuable in numerous applications, and there is an increase in innovative work for automation. This paper intends to present a drug recommender system that can drastically reduce specialists heap. In this research, we build a medicine recommendation system that uses patient reviews to predict the sentiment using various vectorization processes like Bow, TF-IDF,Word2Vec, and Manual Feature Analysis, which can help recommend the top drug for a given disease by different classification algorithms. The predicted sentiments were evaluated by precision, recall, f1score, accuracy, and AUC score. The results show that classifier LinearSVC using TF-IDF vectorization outperforms all other models with 93% accuracy.

EXISTING SYSTEM

The study [9] presents GalenOWL, a semantic-empowered online framework, to help specialists discover details on the medications. The paper depicts a framework that suggests drugs for a patient based on the patient’s infection, sensitivities, and drug interactions. For empowering GalenOWL, clinical data and terminology first converted to ontological terms utilizing worldwide standards, such as ICD-10 and UNII, and then correctly combined with the clinical information. Leilei Sun [10] examined large scale treatment records to locate the best treatment prescription for patients. The idea was to use an efficient semantic clustering algorithm estimating the similarities between treatment records. Likewise, the author created a framework to assess the adequacy of the suggested treatment. This structure can prescribe the best treatment regimens to new patients as per their demographic locations and medical complications. An Electronic Medical Record (EMR) of patients gathered from numerous clinics for testing. 

The result shows that this framework improves the cure rate. In this research [11], multilingual sentiment analysis was performed using Naive Bayes and Recurrent Neural Network (RNN). Google translator API was used to convert multilingual tweets into the English language. The results exhibit that RNN with 95.34% outperformed Naive Bayes, 77.21%.

The study [12] is based on the fact that the recommended drug should depend upon the patient’s capacity. For example, if the patient’s immunity is low, at that point, reliable medicines ought to be recommended. Proposed a risk level classification method to identify the patient’s immunity. For example, in excess of 60 risk factors, hypertension, liquor addiction, and so forth have been adopted, which decide the patient’s capacity to shield himself from infection. A web-based prototype system was also created, which uses a decision support system that helps doctors select first-line drugs. Xiaohong Jiang et al. [13] examined three distinct algorithms,
decision tree algorithm, support vector machine (SVM), and backpropagation neural network on treatment data. SVM was picked for the medication proposal module as it performed truly well in each of the three unique boundaries - model exactness, model proficiency, model versatility. Additionally, proposed the mistake check system to ensure analysis, precision and administration quality. Mohammad Mehedi 

Hassan et al. [14] developed a cloudassisted drug proposal (CADRE). As per patients’ side effects, CADRE can suggest drugs with top-N related prescriptions.
This proposed framework was initially founded on collaborative filtering techniques in which the medications are initially bunched into clusters as indicated by the functional description data. However, after considering its weaknesses like computationally costly, cold start, and information sparsity, the model is shifted to a cloud-helped approach using tensor decomposition for advancing the quality of experience of medication suggestion.
Disadvantages
o	In the existing work, the system did not implement an exact sentiment analysis for large data sets.
o	This system is less performance due to lack Data Classification and Data Fragmentation technique.

PROPOSED SYSTEM

A recommender framework is a customary system that proposes an item to the user, dependent on their advantage and necessity. These frameworks employ the customers’ surveys to break down their sentiment and suggest a recommendation for their exact need. In the drug recommender system, medicine is offered on a specific condition dependent on patient reviews using sentiment analysis and feature engineering. Sentiment analysis is a progression of strategies, methods, and tools for
distinguishing and extracting emotional data, such as opinion and attitudes, from language [7]. On the other hand, Featuring engineering is the process of making more features from the existing ones; it improves the performance of models.
Advantages
	The system is more effective since it presents the proposed algorithm used in natural language processing responsible for counting the number of times of all the tokens in review or document..
	The system has exact sentiment analysis prediction techniques for Data Cleaning and Visualization.




SYSTEM REQUIREMENTS


➢   H/W System Configuration:-


➢    Processor                      -   Pentium –IV

➢   RAM                              - 4 GB (min)
➢   Hard Disk                      -   20 GB
➢   Key Board                     -    Standard Windows Keyboard
➢   Mouse                            -    Two or Three Button Mouse
➢   Monitor                          -   SVGA


SOFTWARE REQUIREMENTS:
	Operating system 	:   Windows 7 Ultimate.
	Coding Language		:   Python.
	Front-End			:   Python.
	Back-End			:   Django-ORM
	Designing			:   Html, css, javascript.
	Data Base			:   MySQL (WAMP Server).
