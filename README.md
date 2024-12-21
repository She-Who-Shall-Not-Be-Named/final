My Project is an Anime Search app that lets users sign up, log in, and search for anime by uploading images. After logging in, users can upload an image, and the server uses Trace.moe's API to find matching anime. If a match is found, it also queries AniList for more detailed titles and shows the result. The app saves the search history in a database, so users can view past searches. There’s also a file upload feature with a size limit, and error handling for issues like invalid input or API failures. Finally, users can log out, which clears their authentication token, logging them out from the app.


Commands needed:
npm install
npx nodemon app.js
