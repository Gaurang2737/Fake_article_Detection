# Fake_article_Detection
The aim of the fake article project is to help news readers to identify bias and misinformation in news articles in a quick and reliable way. We have collected news articles from kaggle and used them to train text classification systems to detect fake or real news. You can paste a piece of text from our article and examine its similarity to our collection of true vs. false news articles.Enjoy testing!
## 📂 Dataset

The full dataset used in this project is too large to be hosted directly on GitHub.  
You can download it from the link below:

👉 [Download Dataset from Google Drive](https://drive.google.com/file/d/1BOc9yvW-cF2NxUiU3yEOWw5-wRuADZEy/view?usp=sharing)


---

## 🛠 How to Load the Dataset in Code

You can directly read the dataset from the link using `pandas`:

```python
import pandas as pd

# Replace with your actual Google Drive file ID
url = 'https://drive.google.com/uc?id=YOUR_FILE_ID'
df = pd.read_csv(url)

print(df.head())
