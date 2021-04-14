NewsNow is a simple news app 🗞️ which uses the API provided below  to fetch top trending news in India, 
The main aim of this app is to show how can one build a  Modern Android application having begineer to intermediate knowledge of Android.

This Application is made using Kotlin Programming Language.

API Documentation:-
BASE_URL = "https://saurav.tech/NewsAPI/"
top_headlines_api = "<BASE_URL>/top-headlines/category/<category>/<country_code>.json"
everything_api = "<BASE_URL>/everything/<source_id>.json"

RecyclerView is used to display news in list form(vertically)

Volley Library,Glide Library are Used.

Volley Library is used to retrieve data, either String, JSONObjects or Images and Glide Library is used for fast and efficient management of image loading/caching

Volley Singleton pattern is followed(recommend way).
