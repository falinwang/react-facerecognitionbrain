![Smart Brain Cover](public/Smart-app-cover.png)

# Smart Brain: Face Detection App
By Roy Fa-Lin Wang

[Play with Smart Brain click here](https://smart-brain-roy.herokuapp.com/) 
- Demo account
  - email: testme@mail.com
  - password: `testme`

[Link to front-end repo](https://github.com/falinwang/react-facerecognitionbrain)

[Link to back-end repo](https://github.com/falinwang/react-facerecognitionbrain-api)

---
## About Smart Brain

Smart brain is a web app that detects the human face present in the image whose URL you submitted.

## Project Description

This project is about using Clarifai API to detect the human faces in the image the user uploaded after they registered and save the counts of their uploaded image. In this app, I use React.js to build the front-end with Tachyons CSS, use Node.js and express.js, and cooperate with Clarifai face detection API, and use PostgreSQL to build the user login system and database that keeps track of the entries number.


## How to Use

This website is now deployed on Heroku: [Smart Brain by Roy](https://smart-brain-roy.herokuapp.com/). (The first loading might require 30-second of wait.)
1. Register a user account with name, email and password

![Register](public/register.png)

2. Paste an image URL in the box and click Detect Button.

- In case you don't know where to find image URL, you can try: `https://thispersondoesnotexist.com/image`. [This Person Does Not Exist](https://thispersondoesnotexist.com/) created by [Phillip Wang](https://www.producthunt.com/posts/this-person-does-not-exist) presents a random, computer generated photo of a fictional person. Refresh the page each time for a new face.

![Paste URL](public/pasteurl.png)

1. Ta-DA! Did you see the face?

![Face Detection](public/detectface.png)

4. You can sign out and sign in to earn more entries!
