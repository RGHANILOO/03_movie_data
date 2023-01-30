# 03_Movie_Data

For this project, we’d like you to build a user interface, using HTML, and populate that with data from a JavaScript object. We’ve given you a data object below.

Make this project your own, what you build as an interface and how you choose to display the data is up to you.

We’d like you to include ways for the user to interact with the data. For example, you might allow the user to sort the movies by the year they were released, or add a new movie to the movieData object.

This week, we’d like you to start using Git in your terminal.

## Requirements 
- [ ] Store the object below in a JavaScript file in your codebase
- [ ] Render the data onto the webpage with DOM Manipulation
- [ ] Allow the user to affect the display of the data by interacting with the webpage
- [ ]Allow the user to update the data stored in the object by interacting with the webpage

## Data 
In your JavaScript file, start by including the movieData object. Here we have four films, which are keys in the movieData object (e.g. “The Darjeeling Limited”). Each of these keys relates to a value with more detail about that particular movie.

```
let movieData = {
  "The Darjeeling Limited": {
    plot: "A year after their father's funeral, three brothers travel across India by train in an attempt to bond with each other.",
    cast: ["Jason Schwartzman", "Owen Wilson", "Adrien Brody"],
    runtime: 151,
    rating: 7.2,
    year: 2007,
  },
  "The Royal Tenenbaums": {
    plot: "The eccentric members of a dysfunctional family reluctantly gather under the same roof for various reasons",
    rating: 7.6,
    year: 2001,
    cast: ["Gene Hackman", "Gwnyeth Paltrow", "Anjelica Huston"],
    runtime: 170,
  },
  "Fantastic Mr. Fox": {
    year: 2009,
    plot: "An urbane fox cannot resist returning to his farm raiding ways and then must help his community survive the farmers' retaliation.",
    cast: [
      "George Clooney",
      "Meryl Streep",
      "Bill Murray",
      "Jason Schwartzman",
    ],
    runtime: 147,
    rating: 7.9,
  },
  "The Grand Budapest Hotel": {
    rating: 8.1,
    runtime: 159,
    year: 2014,
    plot: "A writer encounters the owner of an aging high-class hotel, who tells him of his early years serving as a lobby boy in the hotel's glorious years under an exceptional concierge.",
    cast: ["Ralph Fiennes", "F. Murray Abraham", "Mathieu Amalric"],
  },
};

```
