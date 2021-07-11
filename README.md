# Smart-Brain-API

1. Clone this repo

2. run `npm install`

3. Make sure you have docker installed and running on your computer

4. Run `docker-compose up` ( you may have to run `docker-compose up --build` for the first setup phase)

5. You must add your own API key. Create a .env file in the root of the project and place the API key as such:
   REACT_APP_CLAIRFAI_KEY=yourApiKeyGoesHere

6. You will also need to update Line 22 in server.js to your client app port (i.e. 3001)

You can grab Clarifai API key [here](https://www.clarifai.com/)
