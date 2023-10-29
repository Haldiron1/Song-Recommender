# Song Recommender

This Python script recommends songs based on user input. It uses data from official music charts and Billboard's top songs of the last decade.

## How to Use

1. **Install Dependencies**
   - Make sure you have Python installed.
   - Install necessary libraries by running: `pip install pandas scikit-learn`.

2. **Run the Script**
   - Execute the Python script.
   - Enter a song title or keyword when prompted.

3. **Get Recommendations**
   - The system will provide a list of recommended songs.

## Example Usage

```python
# Example Usage
search_term = input("Enter a song title or keyword: ")
recommended_songs = get_recommendations(search_term)

if recommended_songs is not None:
    print(recommended_songs)
