
## Flix Part 2

### Overview
I am going to extend our Flicks app to allow users to get more information about a particular movie in a movie details screen. Then, we'll add a tab bar to allow users to view movies in a grid view (Collection View) from different endpoints of the MovieDB API.

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [x] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src= "https://i.imgur.com/0M9FrFy.gif" width=250><br>

### Notes
1. getting the error of (Thread 1 :breakpoint 1.1) when I expected to see the additional page with full description of an individual movie. 
2. encountering error message of thread1:signal SIGABRT, which indicating I might have an extra outlet there, a duplicate, or an extra one that's not connected. Therefore, I realized it is very important to indicate the controller before coding on the panel. 
3. Layout is the most challenging part of this project. 
