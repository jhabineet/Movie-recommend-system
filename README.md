<h1>Project: Movie Recommender System Using Machine Learning!</h1>

Recommendation systems are becoming increasingly important in today’s extremely busy world. People are always short on time with the myriad tasks they need to accomplish in the limited 24 hours.
Therefore, the recommendation systems are important as they help them make the right choices, without having to expend their cognitive resources.

The purpose of a recommendation system basically is to search for content that would be interesting to an individual. Moreover, it involves a number of factors to create 
personalised lists of useful and interesting content specific to each user/individual. Recommendation systems are Artificial Intelligence based algorithms that skim through all possible options and create a customized list of items that are interesting and relevant to an individual. These results are based on their profile, search/browsing history, what other people with similar traits/demographics are watching, and how likely are you to watch those movies. This is achieved through predictive modeling and heuristics with the data available.


<h1>About the project!</h1>
This is a streamlit web application that can recommend various kinds of similar movies based on an user interest. here is a demo,

<h2>Demo:</h2>
<br>
<img src="/demo/Screenshot 2024-07-09 090051.png"/>
<br>
<img src="/demo/Screenshot 2024-07-09 092157.png"/>
<br>
<img src="/demo/Screenshot 2024-07-09 092147.png"/>
<br>
<img src="/demo/Screenshot 2024-07-09 090115.png"/>



<h2>Concept used to build the model.pkl file : cosine_similarity</h1>

1 . Cosine Similarity is a metric that allows you to measure the similarity of the documents.
<br>
2 . In order to demonstrate cosine similarity function we need vectors. Here vectors are numpy array.
<br>
3 . Finally, Once we have vectors, We can call cosine_similarity() by passing both vectors. It will calculate the cosine similarity between these two.
<br>
4 . It will be a value between [0,1]. If it is 0 then both vectors are complete different. But in the place of that if it is 1, It will be completely similar.
<br>

<h1>Download the models</h1>
<a href="https://drive.google.com/drive/folders/1lNdWWJx3LIKNr0Re6YDwBdl_8BWXE_VW?usp=sharing">Click Here</a>

<h1>How to Run?</h1>

<p>1. Clone the repository</p>

<p>2. Run the Following</p>
conda create -n movie python=3.7.10 -y

conda activate movie

<p>3. install the requirements</p>
pip install -r requirements.txt
<BR>
#run this file to generate the models
<BR>
Movie Recommender System Data Analysis.ipynb
<BR>
<p>4. Now run,</p>
streamlit run app.py
<BR>
OR,
<BR>

python -m streamlit run app.py























