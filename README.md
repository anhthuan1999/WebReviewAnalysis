# WebAnalysis_University-Course
This is our project in Web Analysis Course. We used python to make a model which classified sentiment Vietnamese book reviews on an ecommerce website, our feature extraction is TF-IDF and Bag of Words with SVM model.

We used two kernel SVM model: linear and rbf and choose the best one
The linear model
![Image of Linear](https://raw.githubusercontent.com/anhthuan1999/Vietnamese-News-Classification/master/images/linear.png) 
<br/>
The rbf model
<br/>
![Image of Bag of Words Unigram](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/unibo.jpg)<br/>
Image of Bag of Words Unigram
<br/>
![Image of TF-IDF Unigram](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/unitf.jpg) <br/>
<br/>
Image of TF-IDF Unigram
<br/>
![Image of Bag of Words Bigram](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/bibo.jpg)<br/>
<br/>
Image of Bag of Words Bigram
<br/>
![Image of TF-IDF Bigram](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/bitf.jpg) <br/>
<br/>
Image of TF-IDF Bigram
<br/>
The best model is linear SVM model with F1_Score is 79.44%, C is 100 or 1000. After that, we apply this model with book "Nhà Giả Kim" which has more than 3000 comments and analyze product features
