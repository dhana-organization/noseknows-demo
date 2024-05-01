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

- [Using GitHub Copilot in your IDE: Tips, tricks, and best practices](https://github.blog/2024-03-25-how-to-use-github-copilot-in-your-ide-tips-tricks-and-best-practices/)
- [10 unexpected ways to use GitHub Copilot](https://github.blog/2024-01-22-10-unexpected-ways-to-use-github-copilot/)
- [How to use Github Copilot in the CLI](https://www.youtube.com/watch?v=fHwtrOcLAnI&t=32s)
- [Prompt crafting with GitHub Copilot](https://www.youtube.com/watch?v=GPLUGJsVx0s)

---
## You can find the slides in [this pdf](https://github.com/LadyKerr/gh-copilot-talk/blob/main/vscode-day/gh-copilot-vscode.pdf)

![slide-1](https://github.com/LadyKerr/try-streamlit/assets/47188731/1af40df6-89a8-41bd-b7e0-dfa48682e652)
