# TalkValley [Task]

### Create a search page with a search bar that on input should show ads matching the keyword entered. Also, display the ads in a grid format. Prefer to create functional component(s). Mongo collections can be like mentioned in excel sheet.

## Folders Walk Through

There are two folder [1] expressbackend [2] reactfronted, to seperate the frontend and backend logic.

## Getting started

To run the development server (expressbackend)

```
npm run dev
```

To start development server (reactfrontend)

```
npm start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Note:

I have compared the ads companyId to companies Id to check if they match and if so then returned the fields as response (json response). After the response is received, I've check if the searched value matches to (primaryText) of ads, if so then rendered the matched ones on screen.

# Regarding Ads Images

The imageUrl for ads shows (URL signature expired) when shared link was tested.<br>
So in UI it wont show the image instead it will show alternative information for an image.
