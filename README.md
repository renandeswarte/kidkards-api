# Kidkards SERVER API Application
---

Kidkards application Server REST API.

Get the application on appstore here: [AppStore](https://itunes.apple.com/us/app/kidkards/id1088182089)

Check the website here: [Website](https://kidkards.herokuapp.com/#/)

Check the Kidkard Application repo: [Github](https://github.com/renandeswarte/kidkards-app)

## Application
---
Kidkards is an application available for iOS devices, iPhone and iPads.<br>

* Learn and play with new English words and flashcards<br>
* Discover new words, try to guess the flashcard answer and listen to the definition of the card.<br>
* Play a matching card game with several card.
* Choose the category you want to learn or play with

Admins can add, update or delete flashcards.

Each flashcard contains a term (picture) and a definition(text).<br>
The pictures are uploaded directly to AWS S3.

## Technologies Stack
---

* BACKEND
	* **Node.js/Express** Server
* DATABASE
	* **Firebase**
* OTHER
	* **AWS S3 CDN** for picture storage
	
	
## Server
---
	
### Configuration file

You need to add a .env file in the root folder.

You can find an example of the file in the documentations folder: [.env](Documentations/dotenvfile.json).

### Local installation
---

Install dependencies `npm install`<br>
Run the server with `nodemon`



