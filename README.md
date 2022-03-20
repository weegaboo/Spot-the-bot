# Spot-the-bot
This is my graduation work in HSE. 
## The main idea
Representing words using word-to-vec transformation allows you to match a natural language word to a multidimensional vector and thereby turn a literary text into a time series. By evaluating the characteristics of this series, it is possible to evaluate the literary text, both globally and locally. On the other hand, using this approach, you can try to distinguish between sequences generated by humans and bots.
## Already Done:
1. Swedish and Uzbek languages will be considered in my work
2. It was decided to compile a corpus of texts based on pages from Wikipedia
3. After that, the texts were preprocessed, namely: exclusion of unnecessary characters, lemmatization / stemming and removal of stop words
4. TF-IDF vectorization of the cleaned corpus of texts
5. SVD decomposition of TF-IDF matrix. Getting a [dictionary of words](https://drive.google.com/file/d/1gHR9wJ6eXoPBmU8NMJjtQCHuF0_tnLOn/view?usp=sharing) {word: vector}
6. Words are replaced by vectors, n-grams are taken and a data set is obtained
7. Compilation of Data-driven graphs
## Plan:
1. Data-driven graph analysis
2. Create LSTM bot
3. Create clustering algorithm
4. ...
