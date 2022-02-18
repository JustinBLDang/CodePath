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
![flix part 2](https://user-images.githubusercontent.com/57662868/154613263-d6b32d2e-e75c-4a7c-9316-9640f83a98b7.gif)


### Notes
Unknown error, maybe with referencing to movie details push navigation, caused crashing each time a movie cell was tapped on.
- Solved by remaking view controller for movie details

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF
![flix preview](https://user-images.githubusercontent.com/57662868/153679888-025facac-f35c-42b1-89d0-e168215155a7.gif)


### Notes
- MovieCell object creating errors due to inherit module from target being unselected under custom class in Identity Inspector
- Unsure as to how to align text to the top left of label for synposis on higher resolutions
