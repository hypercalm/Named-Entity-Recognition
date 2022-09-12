# Named-Entity-Recognition

#### Overview of the domain and problem statement

Now, let’s consider a hypothetical example of a health tech company called ‘BeHealthy’. Suppose ‘BeHealthy’ aims to connect the medical communities with millions of patients across the country.

‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.
So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.
Let’s take a look at the following snippet of medical data that may be generated when a doctor is writing notes to his/her patient or as a review of a therapy that he or she has done.

“The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.”

As you can see in this text, a person with a non-medical background cannot understand the various medical terms. We have taken a simple sentence from a medical data set to understand the problem and where you can understand the terms ‘cancer’ and ‘chemotherapy’. 
Suppose you have been given such a data set in which a lot of text is written related to the medical domain. As you can see in the dataset, there are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text, which you saw in the aforementioned example that the disease mentioned is cancer and its treatment can be identified as chemotherapy using the sentence.
But, note that it is not explicitly mentioned in the dataset about the diseases and their treatment, but somehow, you can build an algorithm to map the diseases and their respective treatment.

Suppose you have been asked to determine the disease name and its probable treatment from the dataset and list it out in the form of a table or a dictionary like this.
 
#### Key                    Value

##### Disease_1	treatment_1, treatment_2, treatment_3…

##### Disease_2	treatment_4, treatment_1, treatment_5…

##### Disease_3	treatment_3, treatment_4, treatment_7…

…	
 After discussing the problem given above, you need to build a custom NER to get the list of diseases and their treatment from the dataset.
There are four datasets provided to you to process, which are as follows:

•	train_sent

•	test_sent

•	train_label

•	test_label

You have the train and the test datasets; the train dataset is used to train the CRF model, and the test dataset is used to evaluate the built model. 
