# Twitter Topic Modelling using LDA

In this project, Topic modelling with Gensim was applied to create an intuitive model using LDA (Latent Dirichlet Allocation) algorithm. Dataset used was an extracted tweets from CityNews Toronto – a popular news program in Canada.

### Topic Modelling
Topic modelling is a process of determining the conceptual “Topic” of a document or sentence. LDA is one of the popular statistical models that are used for this process. In this section, the following steps were performed to determine the associated Topic and word tags of each extracted CityNews tweets.
1. Create Bag of words<br>
2. Create TF-IDF Model <br>
3. Create LDA model <br>
4. Generate Top 5 topics based on their dominance and weight <br>

![image](https://user-images.githubusercontent.com/22542662/129275943-93791d08-12df-44d9-8b63-09c7a38ea3a1.png)


### Word Cloud
Word cloud or tag cloud is a visualization of set of words based on their corresponding weight. In this project, WordCloud API was utilized to generate graphs per topic. The font of each word corresponds to the weights defined by the LDA model. <br>

Here are the generated wordcloud samples for each topic:<br>
![image](https://user-images.githubusercontent.com/22542662/129276161-acf32420-77b2-44ca-b3c2-975a8a4049f5.png)


### Finding the related Tweets
Ipywidgets was applied to create an interface that consist of clickable and functional buttons. GridspecLayout allowed flexible layout which in this case 5x6 grid of ‘info’
buttons that pertains to each word per topic.

![image](https://user-images.githubusercontent.com/22542662/129276270-848c4e71-18ad-45c6-90ac-c648dc352b83.png)





