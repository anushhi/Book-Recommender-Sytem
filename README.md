

## Data Flow Diagram
<img src="https://github.com/anushhi/Book-Recommender-Sytem/assets/65493890/8d841792-ee9a-4e85-b8c1-85f37f923601" width="500">


## System Architecture:

1. **User Interface (Web Browser)**: Users interact with the recommender system through a web browser by accessing the Flask web application deployed on AWS.

2. **Flask Web App**: The Flask application serves as the front-end of the system. It receives user input, preprocesses it, and communicates with the back-end for recommendations.

3. **Back-End Processing**: This component consists of the back-end server and the recommender system logic.

    + Recommender System Logic: Utilizes a collaborative filtering approach and NLP techniques for recommendation. It processes user input, tokenizes and cleans the text, and identifies relevant book titles.
    + Book Database: Stores book data, including titles, authors, popularity metrics, and similarity scores.

4. **NLP Module**: Handles Natural Language Processing tasks such as text cleaning, tokenization, stopword removal, and stemming to enhance the accuracy of user query processing.

5. **Fuzzy Matching**: Incorporates the fuzzywuzzy library to perform fuzzy matching on user queries, finding the closest matching book titles even with slight variations.

6. **AWS (Amazon Web Services)**: The entire system is hosted on AWS, including the Flask web application and the back-end server, ensuring scalability and availability.



## Result: 
As a result of this project, I gained valuable experience in building recommender systems, data analysis, and data management. The system I developed was capable of providing tailored book recommendations to users, improving their reading choices and overall satisfaction. Additionally, the ability to save data and models for future use demonstrated my commitment to efficiency and practicality in data-driven projects.

## Snapshots:
## 1. Enter your fav book

![Screenshot (6)](https://user-images.githubusercontent.com/37416550/235061761-e050f641-0eae-42af-ae10-8f6de54d52e4.png)

## 2. Get similar book recommendations

![Screenshot (5)](https://user-images.githubusercontent.com/37416550/235061766-938a381f-52c5-42f9-a32d-0f1c8eb43126.png)
