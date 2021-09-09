# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF
<img src="(https://user-images.githubusercontent.com/58148243/132628588-35bf9dd3-9b62-4dd7-a096-1b48b68df400.gif)" width=250><br>




### Notes
Describe any challenges encountered while building the app.
<br>
<br>
Towards the end of Unit 1, I encountered a roadblock when attempting to render the "AlamofireImage" files onto the posterView. It turned out that the posterView's outlet (UIImageView) was not connected to the MovieCell. After reconnecting the posterView correctly, my build finally succeeded. Shoutout to the CodePath Tech Fellows who helped me resolve this issue during the process!
