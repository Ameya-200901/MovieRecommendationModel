# MovieRecommendationModel
Movie recommendation model - Python
logic:  every movie is a vector, and five other closest vectors will be recommended
Vector based on a bag of words (text vectorization)
The top 5000 repeated words are chosen as dimensions, and each movie gets a vector based on this dimension
Stop words are not used to form dimensions 
Skleran CountVectorization is used 
Euclidean distance is not used as it fails in higher dimensions 
Cosine distance is found(angle between the two movies)
Sklearn cosine similarity is used 
Step 1: keeping relevant data
Step 2: preprocessing 
Step 3: words are stemmed so that root words are not repeated in the dimensions 
Step 4: Vectors are formed using CountVectorization
Step 5: Top 5 movies with highest dimesion for the given movie is recommended
