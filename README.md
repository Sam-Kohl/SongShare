# SongShare
A web app where users can create an account, access a feed of user-posted audio, upload audio to the feed themselves, comment on each sound, etc. 

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, Node.js, EJS, Express, Passport, MongoDB, Cloudinary

The backend uses the MVC architecture to function. I used Node.js and Express to configure the routing and executing of controllers. MongoDB Atlas is used as the database, while Cloudinary is used for Cloud-based storage of both images and audio.

The views are rendered using EJS, populated with different data retrieved from MongoDB including UserID, SoundID, comments, number of likes, etc.


## Optimizations


Right now the aesthetics of the web app aren't great. With more time, I'd probably find some better-suited templates for the layouts/color scheme.
I'd eventually like from rendering views with EJS to using JSX and React, turning the whole thing into a React application.

## Lessons Learned:

It was really interesting dealing with Cloudinary and learning about the Upload process/data retrieving process in regard to Cloud-based storage. 


