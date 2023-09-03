# Raccomandazione di Film (NLP)

This project provides a movie recommendation function based on cosine similarity. The function utilizes the `sklearn.feature_extraction.text.TfidfVectorizer` and `sklearn.metrics.pairwise.cosine_similarity` modules to calculate similarity between movies based on genre, keywords, and other criteria.

## Requirements

Before using this project, make sure you have Python installed, along with the following libraries:

- `scikit-learn` for `TfidfVectorizer` and `cosine_similarity`,
- `rich` for text formatting.
- `ast`  for working with dictionaries and lists.
  
You can install them using the following commands:
- `pip install scikit-learn`
- `pip install rich` 
- `pip install ast`.

## Usage

To use the recommendation function, follow these steps:

`. Run the various cells in the Python program..

2. Enter the title of a movie in the  `raccomandation('Film Title')` function.

## Example Usage:
After running all the cells and reaching the last one, simply replace the example movie title in the notebook:
```
raccomandation('Men in Black 3')

[Output]:
raccomantation for: Men in Black 3
Based on the Genre, I recommend these films:

The Time Machine
Time Changer
Safety Not Guaranteed
Project Almanac
Somewhere in Time

based on the Production Company I recommend these films:

The Singles Ward
The Lovers
Men in Black II
The Brothers Solomon
Hot Rod

```
