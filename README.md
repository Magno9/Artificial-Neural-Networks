# Artificial-Neural-Networks
Small showcase of my progress. Based on the book: Deep Learning Illustrated (https://www.deeplearningillustrated.com/)


Sample scripts based on the ones from the book Deep Learning Illustrated (https://www.deeplearningillustrated.com/) by Jon Krohn. Some scripts have contain notes from when I was first writing them. A basic breakdown for each one of them:

Shallow_Net_Keras: A simple program which learns to recognize handwritten digits and classify them. It reached 86% accuracy. I later built a more complex model which reached almost 98% accuracy. 

Generative_Adversarial_Network: Two neural networks arranged in such a way that they manage to create brand new pictures. This one creates drawings of apples. The progress of the model can be observed in cell 41.

Natural_Language_Preprocessing_(Gutenberg): An in-depth look at how machines interpret human language: word-vector embeddings. All of the results were reached by the machine without any human input. This model was trained on 18 classic literary works. Notable cells to take a look at would be:
    1. Numer 51: The model has learned all by itself that the word "dog" shares a similar meaning to the words: "puppy", "pet", and "cage". 
    Similar simple tests are included in the next couple of cells with surprising results. 
    2. Number 67: A 2-dimensional visual representation of the 64-dimensional word-vector space, in which words were grouped together 
        by the model based on similarity.

Multi_ConvNet_Sentiment_Classifier_(Movie_Reviews): This model builds on the Natural language processing one and not only learns to interpret human language, but also classify IMDB movie reviews as positive or negative. This is an advanced model, so it performed really well compared to other models. It received a "Receiver operating characteristic score" of 96.15/100, proving its great accuracy understanding human language.

Contact me at alex@jaimes.net for questions.
