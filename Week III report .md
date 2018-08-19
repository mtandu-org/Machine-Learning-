# Week III ParrotAi IPT report
I had review in details in Transfer Learning to aquire more skills concerning my project ,These are some of take aways
Tranfer Learning: is ML method in which the existing model are as the initial point to perform other task,like ResNet
  VG19, and AlexNet
### Why Tranfer Learning 
* Few  ML enginer train CNN from sqrach since in real problem its hard to find huge dataset
* Deep Neural Network its hard to train
* To datamine hyperparameters its difficult it has no much theory
### Tranfer Learning stategics
* Fine turning.Using pretrained network on the large dataset,its used for a new dataset which is different from original
(here we extract the features of Network and training the new task on top of that)
* Freeze all layer except the output layer,work in idea consist of leaving all layers except last layer and train last layer

Also I learned about sentimental analysis,here we train Mchine learning model to detect a sentiment(whether its positive or 
negative comments on data review),Using a pytoch and TorchText our case we were using the IMDb movies datasets.
* Here are some take aways I learned about 
  * TorchText define how your data will processed 
  * Tokenizer this is used split strings into descete tokens which are done by spacy tokenizer
  * Use RNN model with three layers which one for emberding seconds for vectorizing and last is for output layer

Apart from that i had a gentle summary on recomandations system ,Recomandations system is the system used to boost salles 
by predicting user interest and recomend iterms that user likely to be intersting in
(by cheking user ratings,purchasing history,implicit search query).
### Advantages of recomender system
* Focus on increasing sales as the result of personalized offer
* Speed up search and make easier for user to access content they are interesting in
* The user start to fill known which make them more likely to buy products
* Allow company to be position ahead of compitators

### Types of recommendor systems
* Content based which deals with infomation about items like keywords and user preference or profile
* collaborative Filltering uliterlize user interactions of fillteritems of interest deals with iterms 
such as ratings,number of purchasing history

Lastly I had a interesting session about planning and wringing ML experment,what i have got solving ML problem 
is not about coding and has some stategics or plan to follow which are.
* Understand your problem is it classification or regression |supervised or unsupervised
* Understand your data is it binary or multiclass ,timeserries or seqeunce data
* Understand which algorithm will use to your problem
* Be familiar on which metrics you will use to acess perfomance of your model

On top of that i got alot about ML code management first have your git repository,recommended to have private repository 
to work with your data before publishing which consist of different folders for your project like
* /Data folder for your dataset
* /figures for all figures in your project
* /log to control your log
* /notebook all note book to work with
* /result here we store our results
* /src for all source codes  and modules to be used in your projectfor your project
* /readme mantain the read me to express your project

