# FilmDecker Documentation

## Overview

FilmDecker is a platform for sharing and rating all kinds of movies.
It connects to an API developed by **TheDropIndustry**.

You can switch between **Offline** and **Online** API modes using the slider in the bottom-left corner (the online mode provides access to over 100 movies).

---

## Movies – How It Works

Each movie contains:

* a name
* a description
* an author
* a category
* an image
* a YouTube video (trailer)

### Interactions

* Click on a movie to view more details.
* Use the **like** or **dislike** buttons to rate a movie.
* Click the **trash icon** to open a confirmation menu for deleting a movie.
* Click the **pencil icon** to open the right-side panel and edit the movie (fields are pre-filled).
* Click the **cross icon** to add the movie to your **User Collection**.

---

## Tools – How It Works

The tools are located at the bottom right of the application. From bottom to top:

1. **Specific Search**

   * Allows filtering and searching by category or other parameters.
   * Designed to keep the UI clean and easy to use.

2. **Add a Movie**

   * Adds a new movie (requires an image URL and a YouTube video URL).

3. **Edit a Movie**

   * Edits an existing movie by ID (automatically triggered when clicking the pencil icon).

4. **Add a Category**

   * Creates a new category by specifying its name.

5. **Delete a Category**

   * Removes a selected category.

6. **Edit a Category**

   * Renames an existing movie category.

---

## User Collection – How It Works

* The collection opens with the small arrow on the left side of the screen.
* Add a movie to the collection by clicking the **plus icon** that appears when hovering over a poster.
* Click a movie in the left collection navigation to view its details.
* Hover over a movie to display a **cross icon** for removing it from the collection.

---

## Recommendations – How It Works

* On startup, if your User Collection is empty, recommendations are random.
* Once you have movies in your collection, recommendations are based on your most common category.
* You can refresh the recommendations using the icon in the top-right corner.
* Press the search button to display the recommended movie card.

---

## Additional Information

* The search bar highlights the first matching movie based on the entered text.
* A scroll-to-top arrow appears if more than 10 movies are displayed.
* Offline and online modes can be seen as a light and dark theme toggle.
* The recommendations section uses a CSS “before” element to create a continuous glow animation.
* On desktop hover, movies rotate in 3D space using CSS perspective (no three.js).
* A small animated light with particles is present in the top-right corner for visual effect.
* When switching modes, the logo updates, and the “.online” label appears in online mode.


Would you like me to make it a `.md` file ready to drop into your GitHub repo?
