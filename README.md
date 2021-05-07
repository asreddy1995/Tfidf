# Tfidf
Extracting Important Keywords from Text with TF-IDF and Python's Scikit-Learn
Back in 2006, when I had to use TF-IDF for keyword extraction in Java, I ended up writing all of the code from scratch as Data Science nor GitHub were a thing back then and libraries were just limited. The world is much different today. You have several libraries and open-source code on Github that provide a decent implementation of TF-IDF. 
If you don't need a lot of control over how the TF-IDF math is computed then I would highly recommend re-using libraries from known packages 
The one problem that I noticed with these libraries is that they are meant as a pre-step for other tasks like clustering, topic modeling and text classification.
TF-IDF can actually be used to extract important keywords from a document to get a sense of what characterizes a document. For example, 
if you are dealing with wikipedia articles, you can use tf-idf to extract words that are unique to a given article. 
These keywords can be used as a very simple summary of the document,
it can be used for text-analytics (when we look at these keywords in aggregate), as candidate labels for a document and more.
