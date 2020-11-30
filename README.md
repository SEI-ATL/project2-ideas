# Project 2 Planning

Fork & Clone this repo.

## Part 1

Review the [Project 2 requirements](https://romebell.gitbook.io/sei-1019/projects/project-2) and check out some [examples](https://tmdarneille.gitbook.io/seirfx/11-projects/past-projects/project2).

In this space below, list **THREE** ideas for your Project 2. For each idea, include [user stories](https://revelry.co/user-stories-that-dont-suck/) for each idea and a link to the API(s) you want to use for it.

--------------------------------------------------------
1. An app that randomly recommends vacation ideas. After logging in, the app would use Google Maps API to determine the user's location, then Delta's API to find the nearest airport to that location as well as all flights leaving that airport in the near future, then recommend one of those flights (at random) to the user. The app would help "sell" the user on the vacation destination by providing images of the location using the first images that pop up on Google Images API that happen to match the location. The user could potentially set a max budget to spend on the flight, which would narrow down the search results. They could also set a time window (e.g., flights leaving within a week, flights leaving within a month).
[Delta](https://pro.delta.com/content/agency/us/en/home.html)
[Google Maps](https://developers.google.com/maps/documentation)
[Google Images](https://developers.google.com/photos)
2. A Snapchat-esque app that deletes your messages after a certain amount of time. Used for swapping text messages between users, but the activity log is automatically cleared after an hour (or some other unit of time). Not sure what specific API's I would use for this one. Perhaps NodeMailer.
[NodeMailer](https://nodemailer.com/about/)
3. Similar to the above, something with cipher text. The user would type a sentence to send, then the text would be changed to a cipher of some sort, then the recipient would receive the ciphered message. In order to reply, they have to sign up to the site to decode the ciphered message, then they could send a new message back to whoever originally messaged them.
[NodeMailer](https://nodemailer.com/about/)
4. Books. Upload a list of your books, then get recommendations of how to sort them (e.g., alphabetically by author, alphabeticallys by title, chronologically by publication date, based on how well they have been rated by fellow users).
[Google Books](https://developers.google.com/books/)
[Goodreads](https://www.goodreads.com/api)
5. What should I read next? This app would recommend books for you to read based on your what books you've liked in the past. Upon creating an account, users would rate, on a scale of 1 to 5, at least 10 books representing a variety of genres (e.g., one would be a play, another a mystery novel, another an essay collection). After rating at least 10 books, they would have the choice to get a recommendation. The recommendation would be a book chosen at random that is in some way similar to at least one of the books the user has rated. For instance, if a user rated "Peter Pan" with 5 stars, then the app might recommend "The Wizard of Oz," since both books are examples of children's literature. The user can also pass on a recommended book to see a different book or add the recommended book to their reading list. At any time, the user can view all the books they've rated so far as well as their reading list; they can always change their ratings or remove books from their reading list. Making the AI intelligent enough to make insightful recommendations could be a flex goal. For instance, if you like a horror novel and a romance novel, it would recommend a novel that was both a horror and a romance. In the initial stages, the AI would just arbitrarily focus on one of the subjects of one of the books the user rated. The user can also read books via the app. To get all the book data, I will use the Gutendex API, which pulls information from Project Gutenberg (a site that publishes every public domain book it can find).
[Gutendex](https://github.com/garethbjohnson/gutendex)

---------------------------------------------------------

Make a PR when you're done!

---

## Part 2

In the space below:
* either embed or link a completed ERD for your approved P2 idea
* if there are any changes/additions to your user stories, place your full set of revised user stories here
* either embed or link wireframes for every page of your app

----------------------------------------------------------
### ERD

----------------------------------------------------------
### User Stories

----------------------------------------------------------
### Wireframes

----------------------------------------------------------

Make a PR when you're done!
