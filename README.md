# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="https://user-images.githubusercontent.com/58148243/133022956-8d76b5e6-297a-41ec-bac1-b1dae7d3f516.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.

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
<img src="https://user-images.githubusercontent.com/58148243/132628690-0e1393dc-97c2-4df7-a556-a3734cc989e5.gif" width=250> <br>

### Notes
Towards the end of Unit 1, I encountered a roadblock when attempting to render the "AlamofireImage" files onto the posterView. It turned out that the posterView's outlet (UIImageView) was not connected to the MovieCell. After reconnecting the posterView correctly, my build finally succeeded. Shoutout to the CodePath Tech Fellows who helped me resolve this issue during the process!
