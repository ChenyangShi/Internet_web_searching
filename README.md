# Internet_web_searching
the final project of a course

Project Requirements 1    
=======================
Automatically download at least 500 English documents/web pages and 50 Chinese documents/web pages through the download engine (Web Crawler/Spider). Keep the original document/web backup (eg News_1_Org.txt).
Programming automatically preprocesses the downloaded document:
1. Characterize each word to complete the operation of deleting special characters.
2. Investigate and select appropriate Chinese word segmentation techniques and tools to implement Chinese word segmentation. See "Lucene tokenizer comparison"
3. Delete English stop words (Stop Word)
4. Delete Chinese stop words
5. Call or program to implement Porter Stemming function
6. Characterize the Chinese document, which can be indexed by the search engine.
7. For the English document, after the above processing, the simplified document formed after processing (for example, News_1_E.txt) is saved for later index processing.
8. For Chinese documents, after the above processing, the simplified documents formed after processing are saved (for example, News_1_C.txt) for later index processing.

Notes:
---------
Integrate all steps as much as possible into a complete automation system. If not, program each step (module) and pass the results using an intermediate file.
The download engine has extra points if it is written by itself.
Try to download and process more pages for later search.
Use the stop vocabulary provided, or the stop vocabulary generated by yourself based on different apps.



Requirements 2
======================    
Establish and implement a text search function    
1. Use / call the open source search engine Lucene or Lemur to implement a text search engine. Check the relevant information to install the software.    
2. Search and implement search function on 500 pre-processed English and Chinese documents/web pages.    
3. Index the document through the above software, and then enter the keyword through the front interface or the provided interface to display the search function.    
4. The front desk can be displayed via web form, application form, or using existing interface tools.    
5. English search must be implemented. The Chinese search function is available as an option.     
    
Comparing similarities between documents    
1. The similarity between any two documents is calculated by the Cosine Distance. List the original text of the document and give the similarity value.      
    
Clustering the downloaded documents using the K-Means clustering algorithm
1. Gather the downloaded 500 Chinese/English documents into 20 categories and display the three largest classes formed after clustering, and the representative documents in each class (ie, the five closest to the class center) Documentation).
2. The distance calculation formula can use cosine distance or Euclidean metric.
