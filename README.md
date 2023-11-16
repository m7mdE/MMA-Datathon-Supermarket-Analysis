<img src="./Images/rotman-logo.png" alt="Rotman school Logo"/>

# MMA Datathon Fall 2023

### Optimizing The 'Instabasket' Aisle: A Data-driven Approach
 
#### Main Objective

<p>To enhance the MM&A Experience by responding to a high demand from Instabasket personal shoppers by populating a specialized aisle, optimizing both product selection and substitution based on data-driven insights.

We used 2 methodologies:</p>

#### 1. Product Selection

<ol>
<li>Counted and sorted in descending order how many times an item were purchased</li>
<li>Relabeled tagged ‘missing’ data for products Labelled products as ‘frozen’, ‘refrigerated’, or ‘other’ based on department</li>
<li>Selected the top 100 products in 'frozen' and 'refrigerated' categories, then filled the remaining 800 spots with products from the 'other' category</li>
<li>Calculated metrics</li>
</ol>

#### 2. Product Substitution - using Natural Language Processing (NLP)

<ol>
<li>Text Tokenization: Break down product names into individual components (tokens) for analysis.</li>
<li>POS Tagging: Assign a part-of-speech label to each token using the nltk package's 'pos_tag' function</li>
<li>Count Vectorization: Convert tokenized product names into a bag-of-words representation</li>
<li>Cosine Similarity Calculation: Quantify the similarity between different product names' count vectors.</li>
<li>Substitute Identification: Filter products with high cosine similarity scores as potential substitutes</li>
</ol>

#### Skills:
<ol>
 <li>Python</li>
 <li>EDA: Numpy, Pandas, Seaborn, Matplotlib</li>
 <li>Machine Learning: Scikit-learn, NLP</li>
 <li>Cloud: Google Colab</li>
 <li>Version Control: Github</li>
</ol>

<p>Our team consist of 4. It was pleasure to work and collaborated with</p>
<ul>
<li> <a href="https://github.com/Julian-Oppedisano/MMA-Datathon/tree/main">Julian Oppedisano</a></li>
<li> <a href="https://github.com/b8luong/MMA-Datathon-Supermarket-Analysis">Billy Luong</a></li>
<li> <a href="https://github.com/YAJAJ00/MMA_Datathon/tree/main">Emily Yuan</a></li>
</ul>
