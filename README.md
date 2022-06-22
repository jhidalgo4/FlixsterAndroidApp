# Movie Android App

##Overview:
App 

### User Stories
- [x] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [x] Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] Allow video posts to be played in full-screen using the YouTubePlayerView.


### App Walkthough GIF
<img src="https://media.giphy.com/media/R10013oG6d4i4FgzJf/giphy.gif" width=250><br>
-
<img src="https://media.giphy.com/media/btsLrzi4gMwUn00hZe/giphy.gif" width=250><br>

### Notes
-When building the app, I need to use Async HTTP to recieve information from websites to fill my recyclerView. I used an API given, the issue would be would I need to make my own API key or can I continue to use the one CodePath gave, this is important to know if building off this same project.
-**Youtube API** Key gave me trouble when having to connect to the Google servers, the youtube API key is set as a string that may have to be updated because of the Youtube API KEY inorder to play the video player may/while change over time.

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android


Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## License

    Copyright [2020] [Joaquin Hidalgo]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

