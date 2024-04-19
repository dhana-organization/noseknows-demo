# NoseKnows: Fragrance Recommendation API 🌸 

NoseKnows analyzes your favorite perfumes and makes a recommendation for other fragrances you may like.

## Features 
**Personalized Recommendations**: Leveraging KNN Algorithm, NoseKnows provides users with personalized fragrance recommendations that align with their unique preferences and past selections.

## Tech Stack

- **AI & Machine Learning**: Python with Scikit-learn
- **Backend**: Python with Flask
- **Database**: TBD

> The initial dataset is from Kaggle and can be found by [clicking here](https://www.kaggle.com/datasets/nandini1999/perfume-recommendation-dataset). 

## Local Development

1. Clone the repository
2. Install the dependencies by running `pip install -r requirements.txt`
3. `cd` into the `server` directory and run the Flask app with `python app.py`
4. Navigate to to the endpoint `/api/recommend` to perform a `GET` request

In the body of the request, include the following JSON object:
```
{
    "fav_perfumes": [
        "Sola Parfum",
        "Amber Eau de Parfum",
        "Black Citrus Eau de Parfum"
    ]
}
```

## Resources to learn more
- blog posts
- youtube videos
