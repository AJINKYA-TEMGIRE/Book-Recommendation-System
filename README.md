<h1>Book Recommendation System</h1>
<h2>This project is made with two approaches: Popularity based recommnedation and Collaborative filtering based recommendation.</h2>
<p>The dataset is been taken from the kaggle platform</p>
<a href="https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset">Here's the link for the dataset</a>
<p>There are three files in the dataset: book , users and ratings. First goal was to 
    take up the 10 most popular books and show them on the home page. Again the condition
    for choosing the books was that we will take those books only which is rated by atleast
    250 people. Then we are storing those popular books in one dataframe with the data
    of their author , image and rating
</p>
<p>Second goal was to build collaborative filtering based filtering. Here we are actually assuming that
    each book is a single point in number of users rated dimensions. Again we have applied
    certain conditions like we will choose that books only which are rated by more than 200
    people and the most important we will choose those users only who have rated more than 
    50 books. We are creating the pivot table for the same and then finding the distance of
    each book with others and saving it in the dataframe. Now this dataframe is useful 
    for recommendation which will check the closest point to it and collect the data about that point.
</p>
<p>The First page that is home page will show the top 10 books and there will be an option 
    of recommend. When one will click that button that user will be directed to other page
    where he or she have to enter the full name book and accordingly the recommendation will
    be generated.
</p>