## Welcome to Movie-Ratings' project page

### About the project

If you find yourself constantly wondering about new movie ideas or assessing box-office revenues - or in general have even wathced movies in the 21st century or searched movie recommendations from the web in the recent past - you've probably at least heard of **IMDB** and **Rotten Tomatoes**. 

These sites have very widely acknowledged rating systems and thus many people rely on them when searching new films to add to their watchlists.

These sites serve also as great source of data about movies and their reception among audiences. Our goal is to use this data to train a **Machine Learning model** which predicts the rating of a movie based on the description of movie idea. If this sounds like a service you have been missing for the past 10 years then look no further!

### Our Product

Let’s say you have an amazing blockbuster movie idea. Maybe you want to convince other people - possible investors and producers - about how great your idea actually is. Numerical data is always a great addition to sales pitches and from our service you can get a prediction of your movies Tomatometer rating - all you have to do is deliver a short text description of your idea!

We have trained a machine learning model with data of over 17 000 movies stored in the Rotten Tomatoes and IMDB databases. Our model is able to give you a precise prediction based on just the text description of your idea. How much detail you want to give in the prediction phase is totally up to you - so don’t be afraid of stealing your original idea (but bear in mind that this might affect the accuracy too)!

### Interested?

> That's good. 
> You've taken your first step into a larger world.

Unfortunately we have not made our product yet publicly available in the form of an online application. While we are working on it, this blog post is intended to give our project the publicity it deserves.

Please contact us in order to get your ideas boosted by ML predictions. In the meantime, here’s a demonstration how our model predicted the tomatometer rating of Paddington 2:


> Paddington, now happily settled with the Brown family and a popular member of the local community, picks up a series of odd jobs to buy the perfect present for his Aunt Lucy's 100th birthday, only for the gift to be stolen.

```
Predicted tomatometer score: 58.9
```

### Your script...the next Star Wars or Titanic?

Would you like to compare your script with the scripts of the best movies of all time? With our solution, that will be possible. Below, you can see the similarity of the movie scripts of the 79 movies (0 = low similarity, 1 = high similarity).

{%  include similarity_plot.html  %}

